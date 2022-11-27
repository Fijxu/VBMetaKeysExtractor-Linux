### vbmeta.img keys extrator for Unisoc

Based on [this](https://forum.hovatek.com/thread-32664.html) and [this](https://forum.hovatek.com/thread-32667.html) topics on Hovatek forum.

#### How to use:
1) Download the bin from [Releases](https://github.com/ProKn1fe/VBMetaKeysExtractor/releases).
2) Get vbmeta-sign.img (Or vbmeta.img if you are using samsung) from firmware files.
3) Open the terminal and execute the program `VBMetaKeysExtractor` pointing to the `vbmeta.img` path. 

Ex:

`./VBMetaKeysExtractor /home/user/vbmeta.img`

4) Files will be extracted to same folder that contains the `vbmeta.img` file.

#### System requirements:

1) None, ready to use in any distro (If you are going to compile it yourself, install .NET SDK 6.0 or 7.0)

#### How to compile it?

1) Make sure you have installed .NET SDK 6.0 or 7.0
2) Clone the repo with `git clone https://github.com/Fijxu/VBMetaKeysExtractor-Linux`
3) Go into the folder VBMetaKeysExtractor-Linux
4) Compile it with `dotnet publish -r linux-x64 VBMetaKeysExtractor.sln --framework net6.0 --configuration Release` or `dotnet publish -r linux-x64 VBMetaKeysExtractor.sln --framework net7.0 --configuration Release`
