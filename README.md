# MerryweatherState
A mod that replaces the main police force of GTA V with Merryweather but in a more takeover style

Installation:
Just drop "mwr_state" into your "lml" folder
Inside of mwr_state folder, you may also notice an "combat_tweaks.ini" file.

This mod requires Cpast's combat tweaks to function properly, and this is just an pre-configured file
Get Cpast's Combat Tweaks here: https://github.com/cpast/GTA_Combat_Tweaks

OpenIV version might come in the future if i know how to do dlc.rpf structure

Example mods.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<ModsManager>
  <Mods>
    <Mod folder="mwr_state">
      <Name>MWRState</Name>
      <Enabled>true</Enabled>
      <Overwrite>false</Overwrite>
      <DisabledGroups />
    </Mod>
  </Mods>
  <LoadOrder>
    <Mod>mwr_state</Mod>
  </LoadOrder>
</ModsManager>
```
