### BDEnc.bat ###
- Renames the source files (i.e. "00000.m2ts" to "src.m2ts")
- Copies .avs files from a previous directory (default "Ep 01")
- Indexes the source
- Encodes audio
- Encodes video
- Muxes (with correct names/numbers fetched from the folders, for example: "Showname - NCED 01 480 AAC.mkv")

A specific folder structure is necessary. Use this [BD Template](https://db.tt/295TS1NH).

### BDEncEp.bat ###
Same as BDEnc, except it only works for a single folder. Copying .avs from previous folders not supported (yet?). Use the same BD Template as for BDEnc.bat.

### TVEnc.bat ###
Encodes, muxes, names and uploads TV encodes. 

Needs [wput](http://wput.sourceforge.net/) for uploading and [vfr.py](https://github.com/wiiaboo/vfr/releases) for trimming the audio.

Use the following folder structure: Showname/01/TVEnc.bat ([TV Template](https://db.tt/KL9PKl0t))
