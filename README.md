# NIKKE Physics Fixer
A simple tool useful to mod [NIKKE](https://nikke-en.com/) bundles. Thanks to Bingle and Danieru for the help.


## Source code:

The .exe file is a SFX file created with WinRAR that contains all of the Python scripts and JSON files needed, it can be extracted with WinRAR/7Zip.


## Before to use this tool:

  - Download and install [.NET SDK 8](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-8.0.404-windows-x64-installer).
  - Download and install [Python](https://www.python.org/downloads/), along with all of the addons included (pip, etc).
  - Download and install [Microsoft C++ Build Tools](https://aka.ms/vs/17/release/vs_BuildTools.exe), and after that install the necessary libraries following [this video](https://files.catbox.moe/vqsuix.mp4).

  - Open a Windows PowerShell window as Admin, type:
    ```
    pip install UnityPy
    ```
    And hit enter to install UnityPy for Python.
  - On the same PowerShell window type:
    ```
    pip install requests
    ``` 
    Hit enter to install.



### Update:

I added a new feature where you can use a list from a text file to automate the process of the fixes, now the fixer gives this option besides the old one where you need to input every fix you want manually.



## Usage with a premade list:

1. Create a text file and rename it "physicsfixes", and write the list of all the fixes you want like this:

<img src="https://files.catbox.moe/3u4oav.jpg" width="800"/>

On the example above the structure is like this:

'character name to fix' 'skin number' - 'character name to use for the fix' 'skin number'.

Basically it follows the same pattern than the option 2 but automating the process with the usage of this text file containing the fixes you want listed.

2. Move the text file to your Desktop or to your Downloads folder, the tool will search for the text file in any of those two locations, if you don't put the text file there the tool will ask you to input the path to the text file manually.
3. Double-click the exe file "DOROPhysicsFixer.exe".
4. Wait until the fixer finishes to process stuff.
5. You will see the next message:

<img src="https://files.catbox.moe/20dhc0.jpg" width="600"/>


6. Select option 1 and just wait, the fixer will create the new physics file with the fixes you set in the text file previously.
7. If everything worked you will see the file with physics fixed saved on your `C:` drive in a new folder named "PHYSICS_FIXED".
8. Move that file from that folder "PHYSICS_FIXED" to your "mods" folder located in your NMM folder.



## Usage manually:

1. Double-click the exe file "DOROPhysicsFixer.exe".
2. Wait until the fixer finishes to process stuff.
3. You will see the message "Input character name to fix", write the character that you're fixing. For my example I'm fixing Naga physics using 2B free skin physics so I write Naga. Hit Enter.
4. You will see another message "Input character skin number to fix", write the corresponding number (default is 00, skins are 01 to 04 depending on the skin). For my example I'm fixing default Naga physics so I write 00. Hit Enter.
5. You will see the message "Input character name to use for the fix", write the character for the fix. For my example I'm fixing Naga physics using 2B free skin physics so I write 2B. Hit Enter.
6. You will see the message "Input character skin number to fix" again, write the corresponding number (default is 00, skins are 01 to 04 depending on the skin). For my example I'm fixing Naga physics (00) using 2B free skin physics (01) so I write 01. Hit Enter.
7. You will see a new message "Do you wish to fix another character? (Yes/No):". Type one of the options and hit Enter.
 - If you type "No", the fixer will start to fix the required physics data specified in the previous steps.
 - If you type "Yes", the fixer will ask you for more characters to add to the fixer list. With this option you can keep adding as much physics fixes as you want for all of your swapped characters if you made various swaps already.
8. If you typed "No" then just wait until the fixer finishes to fix the required physics, the Terminal window will close automatically after to finish.
9. If everything worked you will see the file with physics fixed saved on your `C:` drive in a new folder named "PHYSICS_FIXED".
10. Move that file from that folder "PHYSICS_FIXED" to your "mods" folder located in your NMM folder.


Apply the mods with NMM and that's it, happy modding! ^‿^
