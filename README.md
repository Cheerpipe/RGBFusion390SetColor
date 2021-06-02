Updated from CheerPipes RGBFusion project.

Source: https://github.com/Cheerpipe/RGBFusionCli

Piped a .EXE from the projects source code since the project didn't include the necessary files for ordinary users to copy/paste the items needed to process the RGB LEDs without downloading visual studio C# and compiling the code from the source.


Instructions:


To install first have RGBFusion B19.0919.1 installed on machine (uninstall any other version) .ZIP included in fork.

Now, copy the RGBFusionCLI.EXE and RGBFusionCLI.exe.config to the C:\Program Files (x86)\GIGABYTE\RGBFusion folder

Then copy all the .CS files to the C:\Program Files\Aurora\Scripts\Devices folder (if Scripts doesnt exist, make the folder, and make a child folder "devices")


Now try using Aurora and the RGB should light up for your motherboard/gigabyte peripherals.


Update 4-1-21:

Having trouble with auto opening the RGBFusionCLI program automatically, will work on a fix and update this fork.


Update 4-14-21:

Added Start-RGBFusionCli.bat which starts the RGBFusionCLI.exe program on startup. 

All you need to do is, place the .BAT file in the following directory: (copy/paste if needed)  C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp

The above folder will start the RGBFusionCLI.exe file on PC startup along with project aurora, and ensure the gigabyte RGBFusion system syncs with aurora

.Bat file located under RGBFusionCli/Startup-Folder of my fork of the project


Update 6-2-21:

Added RGB_Fusion_B21.0113.1.zip to fork to ensure any issues with the program are resolved with a working version of RGBFusion. 

As newer versions of RGBFusion do not work at all with the CLI program, they don't detect any RGB lights, even after a reboot of the workstation.