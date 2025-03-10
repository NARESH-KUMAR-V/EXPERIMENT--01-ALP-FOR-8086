# EXPERIMENT--01-ALP-FOR-8086
Name : Naresh Kumar V

Roll no : 212223040126

Date of experiment : 07.03.2025

## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
![image](https://github.com/user-attachments/assets/630dd538-599f-42c6-9f18-e946263e9f17)
8.	Click on emulate to start emulation
![image](https://github.com/user-attachments/assets/e82c0fd0-8cce-4264-8f9b-62ed27590c59)
9.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below.
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```assembly
MOV AL,88H
MOV BL,65H
ADD AL,BL
HLT
```
## Output  
![image](https://github.com/user-attachments/assets/ed7e5940-cf91-4215-ba73-dc052e3592fc)

## Subtraction   of 8 bit numbers  ALP 
 ```assembly
MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT
``` 
## Output
![image](https://github.com/user-attachments/assets/f922aa00-9af3-4817-b67c-e9cde7b3d93d)

## Multiplication alp 
```assembly
MOV AL,75H
MOV BL,32H
MUL BL
HLT
```
 ## Output  
![image](https://github.com/user-attachments/assets/bbca5942-b35c-4154-9253-54e28586897a)


## Division alp 
```assembly
MOV BL,18H
DIV BL
HLT
```
## Output  
![image](https://github.com/user-attachments/assets/efc9fdfe-934a-45d7-99de-6aa1066e7806)

## And of 8 bit numbers ALP
```assembly
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/80068281-673e-426b-b1cc-45baa39dd78c)

## OR of 8 bit numbers ALP
```assembly
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/569b4360-d73d-4983-a0f7-cacbcb944e2a)

## NOT of 8 bit number ALP
```assembly
MOV AL,65H
NOT AL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/3bb09950-8aba-4496-b787-55faf9526a77)

## XOR of 8 bit number ALP
```assembly
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```

## Output
![image](https://github.com/user-attachments/assets/21ead682-ddf0-4b8a-a4c2-8e31d1984592)

## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.







