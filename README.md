## Requirements
    Linux or MacOS

## Released GSIs
Download links: https://mirrors.lolinet.com/firmware/gsi/  
XDA thread: https://forum.xda-developers.com/project-treble/trebleenabled-device-development/pie-erfan-gsi-ports-t3906486   

## How to use

### Download tools
```
git clone --recurse-submodules https://github.com/JuCesarBR90/JuCesarGSIs.git
cd JuCesarGSIs
```

### For setting up requirements
    bash setup.sh

### Generating GSI from stock firmware URL
Example: for making GSI of other device, you can use this command
```
./make.sh /home/user/system Generic AB

It has to be the extracted system.img directory. If you didn't extract system.img you should extract it first before all this.
```
