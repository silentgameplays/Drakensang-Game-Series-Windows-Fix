# Drakensang-Game-Series-Windows-Fix
Drakensang, Drakensang The River Of Time, Drakensang 2: PhIlleassons Secret Series Windows 10/11 Fix With Higher 2k/4k resolution support

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support and just in case install DirectX 9.0c:

https://www.microsoft.com/en-us/download/details.aspx?id=8109

1. Install Drakensang/Drakensang:The river Of Time/Drakensang 2: PhIlleassons Secret 

2. Go To Steam> Properties> General for each game 

3. Add ``-windowed``

4. Launch every game once and set resolution to 1920x1080 then exit

5. Download and extract files from this repo 

6. Put ``d3d9.dll`` ``dxwrapper.dll`` ``dxwrapper.ini`` into ``C:\Program Files (x86)\Steam\steamapps\common\Drakensang`` and ``C:\Program Files (x86)\Steam\steamapps\common\Drakensang The River of Time``

7. Go into your ``C:\Users\User\Documents\Drakensang\profiles\default`` for Drakensang ``C:\Users\User\Documents\Drakensang_TRoT\profiles\default`` for TROT and Drakensang 2: PhIlleassons Secret

8. Edit ``profile.xml`` file and replace the ``Profile Width="1920" Height="1080"`` with your desired resolution like ``Profile Width="2560" Height="1440"`` for 2k or  ``Profile Width="3840" Height="2160"`` for 4k

9. Launch the games again

# If it results in Nebula errors piling up then switch the launch settings back to -autoconfig -windowed -noborder and use the Borderless Gaming App

# NB2!: In some cases some files for all three games fail to download properly,to fix this issue

1. Go to Steam Properties> Local Files> Verify integrity of game files for each game and click on the "Verify integrity of game files"

# On Windows 11 additional steps are required for Drakensang The River Of Time and PhIlleassons Secret:
1. Go into the game folder C:\Program Files (x86)\Steam\steamapps\common\Drakensang The River of Time\redist
2. And install all the exe's you see there,repair if you have vcredist_x86 2008 and install DirectX 9
3. Try launching the game,if it fails for both games,go to the  Steam Properties> General> Installed Files
4. Verify the files
5. Launch each game again,until they are all running at your desired resolutions.
6. Enjoy the game

# NB3! If all else fails ,especially for Drakensang Steam Version(GoG version works without any tinkering) then use the Borderless Gaming from this repo:

1. Install Drakensang

2. Go To Steam> Properties> General

3. Set parameters to ``-autoconfig -windowed -noborder``

4. Install and launch Borderless Gaming

5. Add Drakensang to Borderless Gaming App:
   
* ![Drakensang Borderless Gaming](https://github.com/user-attachments/assets/d91af7eb-13b0-47d4-968e-0bf9d9207bb8)

7. Enjoy the game.

# NB Every time all the games are uninstalled it's recommended to delete the User Profile Folders located in ``C:\Users\User\Documents\Drakensang\`` for Drakensang ``C:\Users\User\Documents\Drakensang_TRoT\`` for River Of Time

# Drakensang-Game-Series-Linux-Fix

1. Install all three games Drakensang, Drakensang The River Of Time, Drakensang 2:PhIlleassons Secret

2. For all three games Drakensang, Drakensang The River Of Time, Drakensang 2:PhIlleassons Secret

3. Right click in Steam Properties> General> Compatibility>Force the use of a Specific Steam Play Compatibility Tool

4. Currently all three games work with 9.0-4 Proton version even the cut scenes are playable

5. Right click in ``Steam Properties> General> Launch Options``

6. To restore default movement speed to characters in all games, mostly Drakensang limit the FPS to 60

``MANGOHUD_CONFIG="fps_limit=60,no_display" mangohud %command%``

Run all of the the games once and set resolution to 1080p

7. Change to 2k/4 resolutions by going into these folders on Linux:

**Drakensang**

`` /home/user/.steam/steam/steamapps/compatdata/12640/pfx/drive_c/users/steamuser/My Documents/Drakensang/profiles/default``

**Drakensang The river Of Time**

``/home/user/.steam/steam/steamapps/compatdata/33770/pfx/drive_c/users/steamuser/My Documents/Drakensang_TRoT/profiles/default``

**Drakensang 2 -Phileasson's Secret**

``/home/user/.steam/steam/steamapps/compatdata/33780/pfx/drive_c/users/steamuser/My Documents/Drakensang_TRoT/profiles/default``

8. Edit **profile.xml** file and replace
* ``Profile Width="1920" Height="1080"``

**With your desired resolution like**

*  ``Profile Width="2560" Height="1440" ``for 2k
*  ``Profile Width="3840" Height="2160"`` for 4k for each game on Linux


**NB! Drakensang can be launched with intro video now after it has been launched once with
-novideo parameter in the Steam Properties> General> Launch Options and no additional arguments on latest Proton 9.0-4 version.**

# Ok,everything should be good, happy gaming.
# silentgameplays



