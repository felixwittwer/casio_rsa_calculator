[![Generic badge](https://img.shields.io/badge/newest_version-1.0.0-<COLOR>.svg)](https://github.com/felixwittwer/casio_rsa_calculator/releases)

# casio_rsa_calculator
allows you to calculate the rsa public and private keys


## LICENSE
This work is licensed under GLP-3.0.


## CONTACT
Felix Wittwer (felix.wittwer.mail@gmail.com)

<div id=compatibility>
  
## Compatibility
Supported calculators:

Casio fx-9860 GII

Casio fx-9860 GII SD

Casio fx-9860 GIII

</div>


## Versions | Changelog
#### naming convention 
year . main version (for major changes) . sub version (for small changes of bug fixes)

### 1.0.0
- Initial version

## Installation
### via USB
#### fx-9860 GII
1. [Download](https://edu.casio.com/dl/) and install the Casio FA-124 Programm

Due to the complexety of the program I won't explain every detail in this README. For further information use the [official manual (German)](https://support.casio.com/storage/de/manual/pdf/DE/004/FA-124_DE.pdf).

#### fx-9860 GIII and fx-CG50
1. Connect Casio fx-9860 GIII of fx-CG50 to your Computer with the help of the USB cable.

**On the Calculator:** <br>

2. Press [F1]. (USB-Massensp)

**On your machine:** <br>

3. Open the file manager of your operating system and copy all [.g1m](#program_files) (for fx-9860 GIII) files into the shown device (usually D:) under D:/@MainMem/PROGRAM.

4. Eject device (usually D:). More info on calculator display.

**On the Calculator:** <br>

5. Press [EXE] as shown on the screen. <br>
6. Press [EXIT] as shown on the screen. <br>
7. Press [MENU] as shown on the screen. <br>

**Note**
Installation is also possible via the 3-Pin cable betweeen calculators.

| transmiting calculator | reciving calculator |
| ----------------- | ----------------- |
|fx-9860 GIII | fx-9860 GIII | 
| fx-9860 GII | fx-9860 GII |
| fx-9860 GII | fx-9860 GIII |
| fx-9860 GIII | fx-9860 GII |

### via 3-Pin
1. go into the LINK menu on both calculators [ALPHA] [E]
2. make sure that "Kabeltyp" is **3pin**
   
   If not [F4] (CABL) + [F2] (3PIN)
   
| transmiting calculator | reciving calculator |
| ----------------- | ----------------- |
| [F1] (TRAN)| |
|| [F2] (RECV) |
| [F1] (MAIN)| |
| [F1] (SEL)| |
| Go down to "< PROGRAM >" and press [EXE]. | |
| Select all files you want to transmit with arrows and [F1] (SEL) or press [F2] (ALL) to select all. | |
| If you finished press [F6] (TRAN) to transmit the selected files. | |
| If you get asked for confirmation press [F1] (Ja) | |
| Press [EXIT] as shown on the screen.| |
| | Press [EXE] as shown on the screen.|
| | Press [EXIT] as shown on the screen.|
| | [MENU] |

## How to use
To use the Progam you have to execute the RSA-KEY.g1m file by:

**On the Calculator:** <br>
1. go into the Program menu [B]
2. execute the RSA-KEY file [EXE]

<div id=program_files> 
  
## Progam Files

| Filename   | Filesize on Calculator | Lines of code |
| ---------- | ---------------------- | ------------- |
| RSA-KEY    | 2172 Bytes             | 103  Lines    |
| **Total**  | **2172 Bytes**         | **103 Lines** |

</div>

## Diclaimer
The links contained in this file allow you to leave this file and jump to other websites. I, Felix Wittwer, am not responsible for the content, links, changes or updates of these external websites. Use at your own risk!
