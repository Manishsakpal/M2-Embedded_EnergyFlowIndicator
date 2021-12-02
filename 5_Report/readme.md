# Requirements
## Introduction
- In this project the user can easily convert any number system such as: Binary to decimal, octal, hexadecimal. Decimal to binary, octal, hexadecimal. Octal to binary, decimal, hexadecimal. Hexadecimal to binary, decimal, octal.
## Research
- We communicate with each other in a particular language made of letters or words. We normally type letters or words through keyboard of the computer, but computer does not understand the words and letters. Rather, those words and letters are translated into numbers. This means that computers understand only numbers. We know the decimal (base 10) system, and are very comfortable with performing operations using this system, it is also important for us to understand that the decimal system is not the only system in the world. By studying other number systems such as binary (base 2), quaternary (base 4), octal (base 8), hexadecimal (base 16) and so forth, we will gain a better understanding of how number systems work in general. Number systems are the technique to represent numbers in the computer system architecture, every value that you are saving or getting into/from computer memory has a defined number system. As Computer architecture supports following number systems so we need to study them and also need to know the conversion technique between them.
## Defining Our System
- Binary Number System A Binary number system has only two digits that are 0 and 1. Every number (value) represents with 0 and 1 in this number system. The base of binary number system is 2, because it has only two digits.
- Octal number system Octal number system has only eight (8) digits from 0 to 7. Every number (value) represents with 0,1,2,3,4,5,6 and 7 in this number system. The base of octal number system is 8, because it has only 8 digits.
* Decimal number system Decimal number system has only ten (10) digits from 0 to 9. Every number (value) represents with 0,1,2,3,4,5,6, 7,8 and 9 in this number system. The base of decimal number system is 10, because it has only 10 digits.
* Hexadecimal number system A Hexadecimal number system has sixteen (16) alphanumeric values from 0 to 9 and A to F. Every number (value) represents with 0,1,2,3,4,5,6, 7,8,9,A,B,C,D,E and F in this number system. The base of hexadecimal number system is 16, because it has 16 alphanumeric values. Here A is 10, B is 11, C is 12, D is 13, E is 14 and F is 15.

## SWOT ANALYSIS

## Strenghts:
- With number system convertion users can convert a given number system to any other number system. 2.Users can save their time ,without finding it manually. 3.users can reduse the time and effort . 4.Easily get Output.
## WEAKNESS:
- Vulnerable to viruses. 2.May encounter with Bugs.

## Oprtunity:
- Can used for Teaching Purpose
## Threats:
- Application may crash somtimes.
- Can hit error when given huge value.

## 4W's and 1'H
### Who:
- Programers,Students,Enthusiast and for Teaching Purposes

### What:
- Used for easy and quick convertion

### When:
- Demand Basis

### Where:
- As a online tool or a application

### How:
- Purchase from store and DIY or Professional Installation

# Detail requirements
### High level requirements:

| ID	| Description	| Category	| Status |
| ----------------- | --------------- | ------------------------ | --------------------------- |
| HR01 | User shall be able to determine from which number system to which it should be converted. | Technical	| Implemented |
| HR02 | User shall be able to differentiate the input given. | Technical	| Implemented | 
| HR03 | User shall be able to convert one number system to other | Technical	| Implemented |
| HR04 | User shall be able to get the equivalent value in other number system | Technical	| Implemented |
| HR05 | User shall be able to get the desired output	| Technical | Implemented |

### Low level requirements:
 | ID | 	Description | 	HLR ID	 | Status (Implemented/Future) | 
| ----------------- | --------------- | ------------------------ | --------------------------- |
 | LR01	 | At least 1 User must choose the option for the convertion to start | 	HR01	 | Implemented | 
 | LR02 | 	User must give the correct option . | 	HR02	 | Implemented | 
 | LR03 | 	User must give the relevent inputs | 	HR03	 | Implemented | 
 | LR04	 | User desired Output. | 	HR04	 | Implemented | 

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


## Structural Diagrams:-
## 
![image](https://user-images.githubusercontent.com/86291115/144382881-fd8101b2-1e63-4894-9453-a8c36ef8d1f4.png)
## 
![image](https://user-images.githubusercontent.com/86291115/144382951-6c711a55-c504-4e3a-9df0-569a748fedc4.png)
## 
![image](https://user-images.githubusercontent.com/86291115/144382989-1eb0cdd7-1843-4466-b0ff-b7d337b07015.png)

# Images
![image](https://user-images.githubusercontent.com/86291115/144384813-6fca55ac-2e68-40e0-a876-440c04820720.png)
![3ea0826d-2ea2-4e03-a935-abfc663371ec](https://user-images.githubusercontent.com/86291115/144446199-589588a3-e000-4767-a331-296935ab4a76.jpg)

![d965272f-2c9b-4e66-a7f5-b4d1b6f9b94c](https://user-images.githubusercontent.com/86291115/144446144-46836845-2484-4c70-90a9-9e3e3fb67554.jpg)

![cccaf567-8bd8-4230-943b-a9ce6be77ab4](https://user-images.githubusercontent.com/86291115/144446040-0c012b0e-3472-4f54-a384-1cb86d798f83.jpg)
