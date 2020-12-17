# blinking
contains the source code to make RED LED (DIO6) of [TI LaunchPad kit with CC1352R MCU] blink

# HOW TO LAUNCH THE CODE:

# 1. You need to have                                                                                                                               https://eu.mouser.com/ProductDetail/Texas-Instruments/LAUNCHXL-CC1352R1?qs=%2Fha2pyFaduiQ7Z42YDZKD%252B%252BKR%252BDtUFlmucoyXB8qKwOHg2wBKpv0sFZe%2FQNwveyX device. Connect it to PC.

# 2. Install on your PC such apps (if they weren't downloaded earlier): 

    1)  CCS https://www.ti.com/tool/download/CCSTUDIO (from single file installer)
    2)  https://www.ti.com/tool/download/UNIFLASH

# 3. Clone the repository in a folder, open CCS and import the folder (project) in CCS.

# 4. Build it. Having built it, you have a binary, which is in: 
    empty_CC1352R1_LAUNCHXL_tirtos_ccs/Debug/syscfg/empty_CC1352R1_LAUNCHXL_tirtos_ccs.out directory.
  
# 5. Open UniFlash -> detect the device -> flash image (browse the directory where the binary is) -> load image.

That's it!
