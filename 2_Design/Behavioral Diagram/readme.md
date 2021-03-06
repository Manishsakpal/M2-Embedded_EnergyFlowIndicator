## Behavioral Diagram:-
- Since we  are measuring room temperature, we don’t really need values beyond hundred degrees (1000mV output of LM35).
So we can set up maximum value or reference of ADC to 2.5V.

- The controller has a trigger conversion feature, that means ADC conversion takes place only after an 
external trigger, since we don’t want that we need to set the registers for the ADC to run in continuous
free running mode.
- For any ADC, frequency of conversion (Analog value to Digital value) and accuracy of digital output are 
inversely proportional. So for better accuracy of digital output we have to choose lesser frequency. 
For lesser ADC clock we are setting the presale of ADC to maximum value (128). Since we are using the 
internal clock of 1MHZ, the clock of ADC will be (1000000/128).
- First of all we need to enable the ADC feature in ADC.
These are the only four things we need to know to getting started with ADC. All the above four features are set by two registers.

## 
![image](https://user-images.githubusercontent.com/86291115/144382760-4c097146-7bee-4cf1-b3cc-723a6da21d70.png)
