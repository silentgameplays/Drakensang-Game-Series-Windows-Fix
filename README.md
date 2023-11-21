# Drakensang-Game-Series-Windows-Fix
Drakensang, Drakensang The River Of Time, Drakensang 2: PhIlleassons Secret Series Windows 10/11 Fix

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support and just in case install DirectX 9.0c:

https://www.microsoft.com/en-us/download/details.aspx?id=8109

1. Install all three games Drakensang, Drakensang The River Of Time, Drakensang 2:PhIlleassons Secret

2. Install Borderless Gaming from this repository

3. Fix Drakensang first

4. Right click in Steam Properties> General> Launch Options 

5. Add this line -autoconfig -windowed -noborder

6. Launch Drakensang 

7. Launch Borderless Gaming

8. Configure Video Options in Drakensang 

9. In Borderless Gaming app add Drakensang from the section Applications to Favorites.

10. Exit Drakensang,leave borderless gaming running.

11. Fix Drakensang:The River Of Time

12. Right click in Steam Properties> General> Launch Options 

13. Add this line: -autoconfig -windowed -noborder

14. Launch Drakensang: The River Of Time, if all is good there should be no "Nebula error"

15. Configure Video Options in Drakensang The River Of Time

16. Exit Drakensang The River Of Time

17. Fix Drakensang 2: PhIlleassons Secret last

18. Right click in Steam Properties> General> Launch Options 

19. Add this line: -autoconfig -windowed -noborder

20. Launch Drakensang 2: PhIlleassons Secret if all is good there should be no "Nebula error"

21. Configure Video Options in Drakensang 2: PhIlleassons Secret

# For the most cases it should solve the issues on Win10/11

# NB!: In rare cases instead of 

* -autoconfig -windowed -noborder 

* # You can use 

*  -d3d9 -windowed -noborder

# But if it results in Nebula errors piling up then switch the launch settings back to -autoconfig -windowed -noborder

# NB2!: In some cases some files for all three games fail to download properly,to fix this issue

1. Go to Steam Properties> Local Files> Verify integrity of game files for each game and click on the "Verify integrity of game files"

2. Repeat all the previous steps with -autoconfig -windowed -noborder
# On Windows 11 additional steps are required for Drakensang The River Of Time and PhIlleassons Secret:
1. Go into the game folder C:\Program Files (x86)\Steam\steamapps\common\Drakensang The River of Time\redist
2. And install all the exe's you see there,repair if you have vcredist_x86 2008 and install DirectX 9
3. Try launching the game,if it fails for both games,go to the  Steam Properties> General> Installed Files
4. Verify the files
5. Launch each game again,until it is running,make sure that Drakensang is in the  Favorites in the Borderless Gaming application
6. Enjoy the game
   
# NB3!: You can exit Borderless Gaming after each of your gaming sessions in any game, they all use the same Drakensang engine and this needs to be added once.

# Ok,everything should be good, happy gaming.
# silentgamepls



