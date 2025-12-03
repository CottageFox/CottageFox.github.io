---
title: Microcontroller Code
---

## Overview
My code starts with blinking my debugging LED to show that the code is working. Then it starts to read the analog signal from my sensor through my Op-Amp and print the result over serial. Then it determines if the value from my sensor is greater than 500 then it turns on my Debugging LED and turns off my 2 outputs. If the value is less than 500 then it turns off my Debugging LED and turns on my 2 outputs.


## Code
```
#include "mcc_generated_files/system/system.h"

#include <builtins.h>
#include <stdio.h>

/*
    Main application
*/


int main(void)
{
    SYSTEM_Initialize();
    ADC_Initialize();
    UART1_Initialize();
    
    int result;
    
    ADC_ChannelSelect(ADC_CHANNEL_ANA0);
    
    for(uint8_t i = 0; i < 3; i++)
    {
        DEBUG_LED_SetHigh();
        __delay_ms(200);
        DEBUG_LED_SetLow();
        __delay_ms(200);
    }
        

    while(1)
    {
              
        
        ADC_ConversionStart();
        result = ADC_ConversionResultGet();
        
        printf("ADC Value = %d \r\n", result);
        
        if(result >= 500)
        {
            
            DEBUG_LED_SetHigh();
            __delay_ms(10);
            
            IO_RF4_SetLow();
            __delay_ms(10);
            
            IO_RF5_SetLow();
            __delay_ms(10);
        }
            
         
        if(result < 500)
            {
                DEBUG_LED_SetLow();
                __delay_ms(10);
                
                IO_RF4_SetHigh();
                __delay_ms(10);
            
                IO_RF5_SetHigh();
                __delay_ms(10);
            }
                
                
        
        
    } 
    
    return 0;
}
```

The zip file with all of my code can be downloaded [*here*](https://github.com/user-attachments/files/23915081/EGR_304_Final_Project.zip)

