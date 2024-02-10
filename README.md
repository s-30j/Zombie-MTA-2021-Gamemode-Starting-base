# Zombie mta server 2021
This is an old [Dayz] game mode for Starting Base
It has many bugs, but it's better than any gamemode.

# Installation
1. Place all the files in resource folder
2. Add this to ACL
```
<object name="resource.dayzepoch"></object>
<object name="resource.e_login"></object>
```
3. Add this to mtaserver.conf
```
<resource src="dayzepoch" startup="1" protected="0" />
<resource src="e_login" startup="1" protected="0" />
<resource src="dayzmap" startup="1" protected="0" />
<resource src="admin" startup="1" protected="0" />
<resource src="e_admin" startup="1" protected="0" />
<resource src="e_scoreboard" startup="1" protected="0" />
<resource src="e_downloader" startup="1" protected="0" />
<resource src="e_shop" startup="1" protected="0" />
<resource src="e_gps" startup="1" protected="0" />
<resource src="e_textures" startup="1" protected="0" />
<resource src="e_map" startup="1" protected="0" />
<resource src="e_radar" startup="1" protected="0" />
<resource src="e_dynamicsky" startup="1" protected="0" />
<resource src="particles" startup="1" protected="0" />
<resource src="noglitch" startup="1" protected="0" />
```
4. and you're done!

