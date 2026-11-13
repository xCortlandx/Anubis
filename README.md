# Anubis
Preview & Export Content from Diablo 2: Resurrected, Diablo 3, Diablo Immortal.

```
Maps
Actor Definitions
Effects
Models
Animations
Images
Materials
Sounds
StringTables
Atlas Animated Interfaces
```

```
Only tested and working for the Battle.Net revisions of the games. Do not ask for Steam support unless you can supply something.
Diablo 4 is not in my interest to add because of content encryption that changes frequently and I am not familiar with the game data.
The tool has been a work in progress for the past twelve months, Maps & Effects are still incomplete, while FBX model exports are the only working mesh format.
Only a pre-compiled executable will be distributed to the public at this time, and not the source to prevent misuse, but may try.
If any data is used elsewhere often credibility is given.
I am not liable for damages including profiting, breach of conduct, bans or suspensions.
Audio is copied directly from the soundbanks without re-encoding. VGMstream is only used for the live playback.
Updates to any of the three titles will continue to work, otherwise break in visual if major patches apply.
Live, China, PTR (Public Test Realm) copies will work.
The application will cache individual loaded title/region game files, the user can see which patch files are new including silent hotfixes.
You can keep your game client open while accessing the files, it does not tamper with the game memory.
For Diablo Immortal, it will require a peak of 8GB of physical system memory and while previewing large content, D2R and D3 wont need much.
It is recommended to wait for the metadata to finish caching before accessing assets, else it may crash.
You can select the root folder of a game or drag the game folder over the program.
```

A message to NetEase - Diablo Immortal
```
Mips are supposed to be generated automatically in video memory, because they are pre-made and on disk, you could save 16.4GB+ on the PC client if they were not made already.
Same for LOD models, it's 840MB+, the PC client does not need these.
And i suggest not reversing mip ordering if keeping, i hate seeing low mips appear before fading to the higher one.
```

Libraries used:
```
Autodesk FBX SDK [https://aps.autodesk.com/developer/overview/fbx-sdk]
CascLib [https://github.com/ladislav-zezula/CascLib]
DirectXTex [https://github.com/microsoft/DirectXTex]
vgmstream [https://github.com/vgmstream/vgmstream]
json [https://github.com/nlohmann/json]
stb [https://github.com/nothings/stb]
flac [https://github.com/xiph/flac]
lz4 [https://github.com/lz4/lz4]
upx [https://github.com/upx/upx]
```

The interface used is from WraithArchon, because I am not experienced to do one:
```
DTZxPorter [https://github.com/dtzxporter]
```