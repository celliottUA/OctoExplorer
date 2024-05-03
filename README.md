# OctoExplorer
Repository for OctoExplorer toolkit
This is the Unity project for the game.  Once downloaded, it can be opened in Unity, ideally in Unity 2022.3.19f. 

# How to use:
Once open, the user can navigate around the folders and see what's in each level.  All assets used to create the game are available here.  Nearly everything can be customized without any code changes.  Each object can be changed in the UI.  For example, the player's movement can be customized by going to a level, choosing camera and player prefab, player, and then adjusting the PlayerMovement2 script speed.  The scripts are also included, so the user can also change those if necessary.

# Packages:
This project uses the unity 2d template.  It also uses Cinemachine.  All other packages used can be seen in the External Asset Folders list (see line 24).

# Folders 
## Animations
Has the animations for the player character.
## Scenes:
Each scene is labeled according to what it is.  There are the levels, the menus, and the recaps for each level.
## Scripts:
This has the scripts for the game.  The scripts are separated into different folders depending on what zone of the game they control.  Each script has a description of what it does within the file.
## Prefabs: 
This has the prefabs for repeated objects within the game.  It is separated into different folders depending on what category the prefab is in.
## Sprites:  
This has the basic sprites for the game.


 # External Asset Folders
 ## Music Tracks:
 Music tracks from here: https://assetstore.unity.com/packages/audio/music/free-music-tracks-for-games-156413
 ## Retro Game SFX:
 Retro game bundle from here: https://assetstore.unity.com/publishers/20696
 ## Thaleah Pixel Font:
 Font used in game from here: https://assetstore.unity.com/packages/2d/fonts/free-pixel-font-thaleah-140059
 ## TextMeshPro:
 Textmesh pro asset for setup of UI

# Levels
 ## In scene setup
 Each level's components are separated into different things in the heirachy.  They are:
 
 ### Housekeeping
 This is where the basics of the game are set.  This includes the spawn point, event, main background, and level blocks that keep the player within bounds.
 ### Gauges
 This is where the temperature gauges are.  Each one has the guage object itself, and then a canvas with a text object that corrosponds to the gauge.  
 ### UI Panels
 This contains the beginning of level information as well as the sign objects.
 ### Camera and player prefabs
 This has the player itself, as well as the camera and the virtual cinemachine camera.
 ### Audio sources
 The audio sources for the various sounds in the level.
 ### Obstacles
 This is the obstacles that the player has to navigate around.
 ### Backgrounds
 The backgrounds for each level.
 ### Enemies
 The enemies

 # Menus
 ### Main camera
 What displays the scene
 ### Main Canvas 1
 What controls what's visible on the screen.  Text can be changed here, as well as what the buttons do.
 ### Event system
 The event system for the game
 ### Audio Source Menu Click
 The click sounds
 ### Menu Music
 Music for the menu

 
