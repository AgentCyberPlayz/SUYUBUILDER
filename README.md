# SUYUBUILDER
In order for this to work you need to download some stuff if you don't have them already.

1. download visual studios here: https://visualstudio.microsoft.com/downloads/

2.download CMake here: https://cmake.org/download/ 

3. download git-scm here: https://git-scm.com/download

4. download Python from Microsoft store
----------------------------------------------------------------------------------------------
When downloading visual studios make sure to check Desktop Development withC++
----------------------------------------------------------------------------------------------

open commandprompt and paste these in one by one 
1. winget install git.git 
2. winget install cmake
3. winget install vulkansdk
-----------------------------------How-to-use-builder------------------------------------------

inside the SUYUBUILDER type cmd after that opens paste the command "python SUYU.py" and it 
will start downloading the files after it finishes it will open CMake-gui.exe.  

Click browse source code and find the suyu folder inside of SUYUBUILDER folder and hit config
the only thing you change optional platform for generation click the drop down and select 64x.
Hit finish It might take a while depending on your speed after it finishes hit generate it 
will take some time once its done it will say open project click it will open visual studios once
opened go to the top where it says Debug switch it to Release after you do that go in the solution
 explorer right click on solution "suyu" 45 of 45 projects you should see a option
called build solution click it after it finishes go into the build folder bin and the folder
called Released and congrats you just build your own build of Suyu.
