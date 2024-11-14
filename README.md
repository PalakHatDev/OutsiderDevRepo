# Official Submechnophobia Development Repository
![Screenshot_12](https://github.com/user-attachments/assets/c18b3916-566f-4b13-830f-e86153f39743)

 Repository used for testing of Submechnophobia

# Project Setup Instructions

## Engine Setup

In order to use this project you must first modify your unreal engine by taking a 5.3.2 UE installation (duplicated for convinience) While most of these settings are configured already you must make sure to follow the intructions listed in DaveFace's RetroGraphics plugin: https://github.com/DaveFace/UnrealRetroShaders

Navigate into the "\UE_5.3\Engine\Shaders\Private" directory of your unreal engine and add the following text to the beginning "PostProcessTonemap.usf" file.

`#undef USE_GRAIN_QUANTIZATION`

## Project Setup

You need to download two private files from our internal database (Studio Google Drive)

- Resources.zip
- Plugins.zip

The Resources.zip file goes into the content folder and is simply extracted into it (Make sure it does not create a subfolder)
Plugins folder goes into the HOME directory of the repository (with the ".uproject" file)

`NOTE: This Plugins folder contains Wwise intergration required to hear the game. it can run without it but you should never compile or submit the game without the necessary files.`

## DO NOT RUN OPEN YOUR PROJECT FILE UNTIL ALL ADDITIONAL RESOURCES ARE ADDED!



Make sure to use all the required plugins listed in the "PhobiaAlpha.uproject" file 

Mandatory plugins: (Untested)

- ASyncLoadingScreen
- ScreenFade
- AchievementSystem

Modify this file and remove any unecessary plugins if necessary (The rest of the plugins are used for developer convience)

You are done! Just open the folder and verify that the project is working correctly.


## TO-DO:

- Make Sun ~15% bigger (Josh)
- Learn and see if NiagaraSimCache can be input into the sequencer (Josh)
- Litmus (Litmus)