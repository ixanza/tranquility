# Modifications to Serenity

## This isn't supported by me and I am not responsible for you breaking your list

If you plan to make modifications to Serenity be it adding or removing mods, you will want to get familiar with the tool SSEEdit.

SSEEdit is included in the installation of Serenity and can be accessed via the dropdown menu in Mod Organizer.

## Adding mods

If you quickly want to make sure a mod is compatible with Serenity, install it and activate it. If it is just a simple texture/mesh replacer or an SKSE Plugin, it should be compatibel out of the box. If it has an ESP you will want to check further On the right pane, move the ESP above RealisticWaterTwo.esp. Then open up SSEEdit Show Conflicts and wait until everything loads up. Once everything loads up you will be seeing a lot of red things on the left side.

![SSEEditShowConflicts](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/SSEEdit%20Show%20Conflicts.png)

Scroll down to the mod you added and expand the categories. Landscape/Worldspace edits can usually be ignored unless you're adding a mod that is meant to make sweeping changes to landscapes/worldspace.

If you see conflicts with leveled lists and containers like the one below, what you want to do is make an override like so

![CopyingAsOverride](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/Copying%20as%20Override.png)

In the window that pops up, scroll all the way down and pick New file (ESL) as below

![ChoosingAFileType](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/Choosing%20a%20Filetype.png)

Then give it a name

![NamingTheFile](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/Naming%20the%20file.png)

Now you want to scroll down to where the conflict is

![FindingTheConflict](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/Finding%20the%20Conflict.png)

And drag it over to the new file you made

![CopyingTheConflictOver](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/Copying%20the%20Conflict%20Over.png)

Once you've done making modifications, hit X on the top right and save the plugin

![SavingThePlugin](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/Saving%20the%20Plugin.png)

The new plugin will now be in Overwrite. Create a mod with it or leave it there. Just don't delete it.

If the mod you added has these records : Armor, Weapon, Container, Door, Leveled List, Leveled Item and/or NPC, you will have to re-run the Reqtificator. Normally this will be an easy task but due to Serenity being over the 255 plugin limit you will have to perform a workaround.

Download this custom plugins.txt file

- Serenity : [Plugins2.txt](https://drive.google.com/file/d/1kXnpNCc7zw_M0zOxXuhMLVXPvL17yeZD/view?usp=sharing)
- Serenity Plus : [Plugins.txt](https://drive.google.com/file/d/1Hw5rOgABxCUfv-1DLerkQXyraON8yCGw/view?usp=sharing)

Add in the ESP of the mod you added in relation to the load order on the right pane of ModOrganizer2

![EditingPlugins](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/Editing%20Plugins.png)

Then in Mod Organizer 2, Run the Reqtificator from the dropdown and click run. When it asks you for the plugins.txt, point it to this text file you downloaded and edited. It should now run fine. If any of the mods you added modify NPCs, you will have to re-run Synthesis. Synthesis is a tool created by Noggog to perform what we normally do with zEdit but faster.

Select Synthesis from the dropdown menu and click Run. If the window that opens is blank, you will want to add External Patcher Programs by clicking this button.

![AddingPatchesSynthesisPart1](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/AddingPatchesSynthesisPart1.png)

Then you want to browse and head to `Serenity\tools\Synthesis\Patchers` and select one exe file (eg. Face Fixer). Repeat this for all the EXE files in that folder. Once you've added everything, click on the small Play-like looking button at the bottom left to run the Patcher. This should take about 30 seconds. Once its done you can click X and you're done with Synthesis.

**Note** as of writing this guide there is a bug with Synthesis where it doesn't save the resulting plugin with the correct header. As such the game will not start. To remedy this, run CreationKit from the dropdown,

Once its loaded up click on Open, Find Synthesis.esp

![OpeningAFileInCreationKit1](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/Opening%20a%20File%20in%20Creation%20Kit%201.png)

Click on it and click Set as Active File. Then Press Ok
![OpeningAFileInCreationKit2](https://raw.githubusercontent.com/ixanza/serenity/master/tutorial%20images/Opening%20a%20File%20in%20Creation%20Kit%202.png)

Once it loads up. Just hit the Save Icon and then close CreationKit.

And that is pretty much how to add mods to Serenity.

### Removing Mods

Johanlh over on Noir has an incredible tutorial on how to remove mods if you so desire. Please check it out on the [Noir Readme](https://github.com/giraldiego/NOIR/blob/master/SETUP.md#remove-tso-music-or-any-other-mod).
