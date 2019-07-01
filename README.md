# The Truth of Amera

This is the GitHub repo for the developers of Next Gen Softwork's game The Truth of Amera. Below are some general guidelines for developers to follow:

## Naming Conventions
When creating a new asset in the engine, the following naming conventions should be used to keep everything consistent:
	- Character Blueprints should have "CH_" appended at the start (E.G. CH_PlayerCharacter)
	- Actor Blueprints should have "BP_" appended at the start (E.G. BP_ActorThing)
	- UI Blueprints should have "UI_" appended at the start (E.G. UI_HUD)
	- Any Static Meshes imported into the project should have "SM_" appended at the start (E.G. SM_Item)
	- Any Skeletal Meshes imported into the project should have "SK_" appended at the start (E.G. SK_Player)
	- Any Materials should have "M_" appended at the start (E.G. M_Grass) and any Material Instances should have "MI_" appended at the start (E.G. MI_Grass)
	- Any Textures imported into the project should have "T_" appended at the start (E.G. T_Picture)

## Colours
When commenting on code, the following conventions should be observed:
	- Commenting around an event should be blue (0, 0, 1, 1)
	- Commenting around input events should be red (1, 0, 0, 1)
	- Commenting around other parts of code should be green (0, 1, 0, 1)
