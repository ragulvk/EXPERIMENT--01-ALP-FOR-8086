# EXPERIMENT--01-ALP-FOR-8086:
~~~
Name : Ragul Vk
Register Number : 212221240043
Date of experiment : 09/09/2022
~~~
## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required:
 8086  emulator 
## Theory: 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.
 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory.
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color.
3.	Write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations.
4.	Compile the program and check for the errors.
5.	Run (once there is no syntax error).
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)
9.	Click on emulate to start emulation 
![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)
10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 
![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

# Programs for arithmetic  operations:
## Addition  of 8 bit ALP :
## Program:
~~~
name "Addition"
org 100h
MOV AX,05H;
MOV BX,03H;
ADD AX,BX;
MOV CX,AX;
MOV AX,00H;
HLT;
~~~

## Output:
### Loading AX and BX register with the Numbers whose Addition has to be found :
  ![output](1.jpg)
  ![output](2.jpg)
  ![output](3.jpg)
### Performing 8-bit Addition using "ADD" instructions :
  ![output](4.jpg)
### Moving the data to CX register :
  ![output](5.jpg)
### Resetting the AX register :
  ![output](6.jpg)
### End of the execution :
  ![output](7.jpg)
### Status of flags:
  ![output](8.jpg)

## Subtraction of 8 bit numbers  ALP :
## Program:
~~~
name "Subtraction"
org 100h
MOV AX,07H;
MOV BX,03H;
SUB AX,BX;
MOV CX,AX;
MOV AH,00H;
HLT;
~~~

## Output:
### Loading AX and BX register with the Numbers whose Subtraction has to be found :
  ![output](9.jpg)
  ![output](10.jpg)
  ![output](11.jpg)
### Performing 8-bit Subtraction using "SUB" instructions :
  ![output](12.jpg)
### Moving the data to CX register :
  ![output](13.jpg)
### Resetting the AX register :
  ![output](14.jpg)
### End of the execution :
  ![output](15.jpg)
### Status of flags:
  ![output](16.jpg)

## Multiplication ALP: 
## Program:
~~~
name "Multiplication"
org 100h
MOV AL,04H;
MOV BL,03H;
MUL BL;
MOV CL,AL;
MOV AL,00H;
HLT;
~~~
## Output: 
### Loading AL and BL register with the Numbers whose Multiplication has to be found :
  ![output](17.jpg)
  ![output](18.jpg)
  ![output](19.jpg)
### Performing 8-bit Multiplication using "MUL" instructions :
  ![output](20.jpg)
### Moving the data to CL register :
  ![output](21.jpg)
### Resetting the AL register :
  ![output](22.jpg)
### End of the execution :
  ![output](23.jpg)
### Status of flags:
  ![output](24.jpg)

## Division ALP:
## Program:
~~~
name "Division"
org 100h
MOV AL,09H;
MOV BL,03H;
DIV BL;
MOV CL,AL;
MOV AL,00H;
HLT;
~~~
## Output:  
### Loading AL and BL register with the Numbers whose Division has to be found :
  ![output](25.jpg)
  ![output](26.jpg)
  ![output](27.jpg)
### Performing 8-bit Division using "DIV" instructions :
  ![output](28.jpg)
### Moving the data to CL register :
  ![output](29.jpg)
### Resetting the AL register :
  ![output](30.jpg)
### End of the execution :
  ![output](31.jpg)
### Status of flags:
  ![output](32.jpg)

## Result :

Thus, to write and execute ALP on fundamental arithmetic operations is successful.
