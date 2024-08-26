# MouseAnchor
WoW Addon to Anchor tooltip to the mouse

# How-To
- Open Windows Explorer or an equivalent program.
- Browse to your AddOns directory. Its path is <Your WoW Install Directory>\Interface\AddOns (ex.: C:\Games\World of Warcraft\Interface\AddOns).
- Create a new folder. For the sake of recognizing it later, give it a name related to what the code should do (ex.: InnervateSay). This name needs to be unique within your WoW directory and may not contain spaces (at least I think so).
- Open Notepad or a similar editor that uses plain text. Do not use Microsoft Word!
- Copy the .TOC file contents from the bottom of this post into notepad. Replace YourFolderName with whatever your addon is called.
- Open the File menu and choose Save As... .
- Set the file format to "All Files (*.*)"
- Save the file as YourFolderName.toc - this needs to match the name you gave your folder above or the addon will not load.
- Create another new text document in notepad.
- Paste the code you want to run into this file
- Save the file as YourFolderName.lua - the name needs to match what you entered in your TOC file above. Don't forget to set file format to "All Files (*.*)"!
- Done! Restart WoW and your new addon should show in the AddOns list on your character select screen.

## TOC file for copy+paste:
Code:
```
## Interface: 60200
## Title: MyAddonTitle
YourFolderName.lua
```
## Get current version number
```
/dump select(4, GetBuildInfo())
```
