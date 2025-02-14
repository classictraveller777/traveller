This is a copy of my Foundry VTT V12 build 331 world folder for the classic traveller adventure shadows for use with the twodsix package  

The contents of this world folder is the scene maps, actors ( players and animals) tokens, artwork, JavaScript macros to simulate open doors closing as a result of seismic tremors, lights randomly toggled on / off, etc which represents aboout 3/4 setting up the adventure in Foundry VTT.
The remaining 1/4 can be customised by you to suit your style of play or should you wish to make modifications add on additional modules / packages add on player handouts etc.  

Because twodsix can be configured to be used with a number of traveller rulesets it is left up to the referee running this adventure to choose
the ruleset and configure both the twodsix package and also aspects of the adventure such as player and animal stats etc.

The referee will need to source a copy of the traveller shadows adventure to run the adventure as the copy contains the location descriptions the scene maps were based on. 

Refer the /readme/FoundryVTT_how_to_run_shadows_referee_notes for instructions including a list of the required Foundry modules, and notes how to teleport tokens through the levels, run macros etc.

installation notes 
1. Download from github the traveller-master.zip file ( click the code button and select download ZIP option ) 
2. In Foundry VTT setup UI using the install game system button search for and install twodsix
3. In Foundry VTT setup UI using the add on module install 

levels ( this will also install wall height  )  
monks active tile triggers  
monks token bar - this optional but I used this to lock / unlock tokens before / after teleport from scene to scene. 
tile sort https://foundryvtt.com/packages/tile-sort - this is optional only and only useful if you plan to add / edit any of the tiles as tile sort makes it easier to find tiles that are stacked on top of each other 

4. Extract the traveller-master.zip into a temporary directory. Rename the directory to traveller. 
5. Copy the traveller directory to the world folder of your Foundry VTT installation. Launch Foundry VTT and verify the traveller world can be launched from the game worlds tab of Foundry VTT setup.

OR optionally

5. Use Foundry VTT setup UI game worlds tab to create a new world folder using the twodsix ruleset.
6. Copy all files and folders EXCEPT for the world.json file from the traveller-master directory into the new world folder. 
7. Using a code editor open both the traveller-master/world.json and the new world /world.json and NOTE any differences and manually copy / edit the new world /world.json for any missing but desired properties. For example I noticed that when setting up a new world the packs property is missing despite the /pack folder copied over from traveller-master to the new world. NOTE if you don't plan on using cepheus light or any custom compendium pack then this step is not necessary 
 

