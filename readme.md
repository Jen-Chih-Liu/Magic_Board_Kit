# Nuvoton Magic Board - Enjoy Creation in One MCU 
[Introduction for the board](https://www.nuvoton.com.cn/board/magicboard/?index=0)

### Magic Board Open Source Project 
This repository contains various files and folders organized into four main categories:

- **Document:** Intro and features highlight.
- **Schematic:** schematic diagrams, gerber file, placement, and layout.
- **SourceCode:** Contains source code and KEIL project divided into *APROM* and *LDROM(bootloader)* regions. 
  - **FW_build:** The FW_build folder allows for easy programming with using the Nuvoton ICP tool. Just open the `MagicBoard_20240408.icp`  , connect the nu-link to start programming.
  - **FW** Contains the APROM and LDROM application for the whole system.
  	- **APROM:** Magic board APROM source code.
  	- **LDROM:** Bootloader source code.
  - **ISP_Tool:**  FW update tool source code.
- **Tool:** Includes 3 tools for different purposes.
  - **Update Tool:** Provides an executable named `NUVOTON_Magic_Board_Util.exe` for updating text, graphics, and programs on the Magic Board via USB Type-C connection.
  - **LCDView:** Includes project files for LCDView tool.
  - **Touch View:** Contains the calibration program for the touch interface.

