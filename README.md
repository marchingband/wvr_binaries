# WVR BINARIES

In each folder is all the released firmware versions for each WVR board.

The version code uses semantic versioning standards. A major version (1.x.x -> 2.x.x) update will trigger a full eMMC reset the first time it is booted.

Each firmware is compiled against the same version number of the WVR Arduino library, which is tagged using the version number. The .zip files for all these Arduino Libraries are available here https://github.com/marchingband/wvr/releases under **assets** WVR.zip
  
Starting with version 3.10.0, there are 2 versions of each firmware.  
`wvr_basic.ino.bin` - the `.ino.` indicates it is compiled using Arduino CLI.  
`wvr_basic.bin` - this was compiled using Platformio.  
If you attempt an update and it is rejected, just try the other version, it is possible your WVR was initially flashed using Platformio, and needs a Platformio binary to successfully update.