# How 'configuration' repository works :
  Download and place directly the folder into .minecraft | Warning, this do not work with the mods folder.
  Everytime the launcher is opened, it check this repository hash and compare to it's local hash, if it is different, the launcher will update mods. It should re-download everything !


## mods folder :
  Client and Server mod categorized.
  Note that the launcher should only look up for clients' folders such as 'Client' and 'lient Libs and APIs' Mods from both folders should be download at .minecraft/mods. Overwrite is needed when update.

## config folder :
  Based config for every mod, for example Immersive Portal is optimised.
  The launcher should download 'config' folder and overwrite existing 'config' folder located at .minecraft/config
  Overwrite is needed when update.

## resource folder :
  Resources for fancymenu, such as animations, logos, musics.
  The launcher should download 'config' folder and overwrite existing 'config' folder located at ..minecraft/resources
  Overwrite is needed to update.
