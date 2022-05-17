# ABSTRACT
The wiper control system is used in a four wheeler vehicle to wipe the water droplets off the front glass of the vehicle. In this project i have designed a wiper control system with on board leds in stm32f407 discovery board. the led will circle around in a wiper moving fashion.
# INTRODUCTION
The stm32f407 on board led with different timings for switching on and off is what determines each speed of the wiper control system.the push button is used to trigger each speed of the wiper.
# SOFTWARE REQUIREMENTS
 STM32 CUBE IDE
# COMPONENTS
 STM32F4O7 discovery board
## DESCRIPTION
# STM32F407VG
The STM32F407  Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications. It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.
 # FEATURES OF STM32F407VG MICROCONTROLLER
  * In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
  * On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)
  * USB ST-LINK with three separate interfaces and re-enumeration capability.
  * Virtual Com port Debug port (with new order code only)
  * Large-scale storage (with new order code only)
  * Board power is supplied through USB or an external 5 V supply source.
  * 3 V and 5 V external application power supply
 # USES
  * This Microcontroller is utilised in printing and scanning machines ,heat ventilation, air conditioning, and security systems. 
  * This module can be found in a variety of household products.
 # WORKING PRINCIPLE
 The push button is pressed for switching on the red led(engine start),second press of push button switches on the wiper motion of led blue,green,orange(wiper starts at low speed),third press of push button switches on the wiper motion of led blue,green,orange(wiper starts at medium speed),fourth press of push button switches on the wiper motion of led blue,green,orange(wiper starts at fast speed),fifth press of push button switches off the red led(engine stop).
 ## 4 W'S
 # WHAT IS WIPER SYSTEM
  Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.
 # WHY WIPER SYSTEM
   To keep the windscreen clean enough to give adequate view at all times.
 # WHEN SHOULD USE WIPER SYSTEM 
  The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
 # WHO should use the wiper
  people who drive the fourwheeler vehicles.
#  ENGINE ON STATE
![on](https://user-images.githubusercontent.com/101464023/168469055-4ce4b21b-0b54-4bc7-b6b0-99f6318c55ac.png)
# WIPER SPEED IS LOW
![low](https://user-images.githubusercontent.com/101464023/168469076-d4234bd2-d0d3-4921-8866-73120e4c3d49.png)
# WIPER SPEED IS MEDIUM
![medium](https://user-images.githubusercontent.com/101464023/168469082-fb4f60a7-9ca7-4050-84e1-0fee32d05232.png)
# WIPER SPEED IS HIGH
![high](https://user-images.githubusercontent.com/101464023/168469071-bf0dab12-ee9a-4e94-bfe9-ce4ef54d5191.png)
# OFF STATE
![Schematiccapture](https://user-images.githubusercontent.com/101464023/168469057-29a24f26-622b-4b81-a376-8c308da01270.png)
