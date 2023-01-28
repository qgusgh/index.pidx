# What is this for?
In Eclipse embedded CDT, you can install MCU packages by refreshing in CMSIS Packs window

However, it stucks because of ADuCM320_DFP

You can simply fix by changing url from https://www.keil.com/pack/index.pidx to https://raw.githubusercontent.com/qgusgh/index.pidx/main/index.pidx in C://Users/(user name)/AppData/Roaming/CMSIS-Packs/.repos.xml

Error causing packages are deleted in this file
