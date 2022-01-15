# MKS-H43-firmware
The source code of MKS H43 project, can be forked to customize your own UI and functions. More information about MKS H43, please refer to https://github.com/makerbase-mks/MKS-H43

## How to build
If you want to customize your own UI on MKS H43, or modify some functions, you can using the "DGUS Tool" to make it, only support Windows OS so far:
1. Download the "DGUS_Tool_Vxxx.rar" from https://github.com/makerbase-mks/MKS-H43/tree/main/Tool, this is the tool use to edit the firmware of H43. Decompress it and run the "DGUS Tool Vxxx.exe". The default language is Simplified Chinese, you can config to English on the menu of "配置"(Setting)->Language.
2. Download the source code of MKS H43 from https://github.com/makerbase-mks/MKS-H43-firmware, open the project file "DWprj.hmi" file with the DGUS Tool above.
3. Now you can change the size of images/replace your own images or modify the execute functions and so on. 
4. After your modification, select the "DWIN ICL Generator" on DGUS TOOL's welcome page, it will generate the files for burned.
5. Copy the "DWIN SET" folder to the TF card(make sure it has been formated as FAT32 format with 4096 bytes aligned before, and insert it into MKS H43 board, reboot the board and it would update automatically.

More instruction about how to develop and buid the source code, please download the develop guide:[T5L_DGUSII Application Development Guide](https://github.com/makerbase-mks/MKS-H43/blob/main/Tool/T5L_DGUSII%20Application%20Development%20Guide20200902.pdf)

## Notice

Branch:

- main
- H43_for_Marlin

If you want to use Marlin_ Bugfix, Please select branch H43_for_Marlin.

## Updata

Updata version:V1.31

Note when updating to v1.31:

- The marlin version needs to be updated synchronously
- Need to enable "\#define USE_MKS_GREEN_UI " in "DGUSDisplayDef.h"

## Note
- Thank you for using MKS products. If you have any questions during use, please contact us in time and we will work with you to solve it.
- For more product dynamic information and tutorial materials, you can always follow MKS's Facebook/Twitter/Discord/Reddit/Youtube and Github. Thank you!
- MKS Github: https://github.com/makerbase-mks  
- MKS Facebook: https://www.facebook.com/Makerbase.mks/  
- MKS Twitter: https://twitter.com/home?lang=en  
- MKS Discord: https://discord.gg/4uar57NEyU
- MKS Reddit: https://www.reddit.com/user/MAKERBASE-TEAM/ 

![mks_link](https://user-images.githubusercontent.com/12979070/149612450-0e4f090e-215b-4f56-bb46-9f26fa4c4874.png)

