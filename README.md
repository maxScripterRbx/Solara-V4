# Solara-V4
# PASS:1234
# ADD ZIP TO YOUR DESKTOP

SOLARA [BETA] EXECUTOR!

Changelog:

5/29: Fixed appendfile Added lz4compress, lz4decompress Added debug.getinfo Added debug.getmetatable / getrawmetatable (watered down version) Added isnetworkowner Added isscriptable Added setsimulationradius Added isexecutorclosure Added getcallingscript Added a more functional cloneref Fixed compareinstances Reverted fireclickdetector (should work now) Loadstring now returns compiler errors semi correctly, and no longer errors in console Loadstring now takes a chunkName Added islclosure

5/27: Removed some on load tampering checks which prevented the exe opening for some people Fixed in game attaching again hopefully (also, it will detect once you've left the game and auto attach on the homescreen, however if you teleported you will need to attach again), this also fixes not being able to leave the game after attaching in game Added a check to automatically create a SolaraMain folder on desktop with workspace, autoexec, and scripts if you ran the exe straight from the temp folder without ever running the bootstrapper

5/23#2: Added a semi functional require, if the ModuleScript's source is visible it will require it. Also, require(assetid) will work now

5/23: Updated for latest ROBLOX version Teleport Handler more stable Added a check in the bootstrapper to kill node.exe and the main solara exe High CPU Usage should be fixed Implemented measures to lower memory usage Fixed writefile, appendfile getscriptbytecode now works CORRECTLY and now works with localscripts, make sure to test by passing the bytecode into decompilers like Konstant or Unluau


