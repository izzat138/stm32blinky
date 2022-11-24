# stm32blinky
This repository documents the details of Blinky project on an STM32F103C8T6 MCU using STM32CubeIDE, an open-source C/C++ development platform for STM32 microcontrollers and microprocessors.



## Group Members
1. Ashraf Aminin bin Arman Alim
2. Izzat bin Idris


## Project Procedures
1. Start a new STM32 project and input part number according to the MCU being used.

![Semantic description of image](/image/pic1.jpg)

*My caption*




2. Input valid project name and click finish.

![Semantic description of image](/image/pic2.png)

*My caption*




3. Assign any output pins as the GPIO output pin by clicking the pin in the pinout view. Configuration for SYS under system core pull-down menu is set to **serial wire** for debugging mode and **SysTrick** as timebase source. Save the project to generate C code for given project configurations.

![Semantic description of image](/image/pic3.png)

*My caption*




4. Only a section of the generated code is modified. In this project, the executing loop is added with built-in functions to blink the LED on the MCU with 0.5 seconds interval. 

![Semantic description of image](/image/pic4.png)

*My caption*




5. Under project properties(Right click project, select properties), select to convert builds to binary and hex files under MCU Post build outputs. Apply the changes.

![Semantic description of image](/image/pic6.png)

*My caption*




6. Start building the debug for the current project.

![Semantic description of image](/image/pic5.png)

*My caption*




7. STM32 ST-LINK Utility is utilized to program the SM32F103C8T6 MCU through an ST-LINK V2. The generated binary/hex files are opened through this application.

![Semantic description of image](/image/pic7.png)

*My caption*




8. Connect the STM32 MCU through the USB port with the ST-LINK V2. Then, connect with the MCU and start to program it.

![Semantic description of image](/image/pic8.png)

*My caption*
