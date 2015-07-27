### QREencode Standalone (portable) Compilation on Linux

##### The 3 general steps needed to compile (simplified):
> ./configure

> make

> make install

<br>
##### Actual steps that I did:
1 - First, donwload and extract the QREncode source code.
> tar  -xzvf  qrencode3.4.4.tar.gz

2 - Enter the source code directory
> cd qrencode3.4.4

3 - Run the configuration script
> ./configure --prefix=/myDestination/FolderOf/Binary/  --enable-static  --disable-shared

4 - Run "make"
> make

Run "make install"
> make install

The resulting standalone (portable) binary will be on the */myDestination/FolderOf/Binary/***bin/** folder.

The executable file is "**qrencode**".
<br>
<br>
##### Downloading the QREncode Source Code:
Get the source code from the Kentaro Fukuchi website: http://fukuchi.org/works/qrencode/

<br>


