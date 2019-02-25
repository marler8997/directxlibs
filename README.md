# DirectX Libraries

Contains precompiled `.lib` files to link against the directx dlls.  These are just used for compile-time linking.  In order to run a program that links against these libraries, the dll will need to exist somewhere on the system as well.  This repo stores both COFF and OMF formats of the `.lib` files.  COFF is mainly used by the Microsoft MSVC linker and OMF is mainly used by the MARS linker `optlink`.  `optlink` is mainly used by the D Programming Language reference compiler `dmd` and the Digital Mars `c++` compiler `dmc`.

I don't remember where I got the `d2d1.coff.lib` file, but I used it to generate the `d2d1.omf.lib` file using `coffimplib` at http://ftp.digitalmars.com/coffimplib.zip
