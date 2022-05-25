# Setup

Create A folder named "lib" in disk D

Download SFML_2.5.1 and extract to ``` D:\lib ```

In Solution Explorer

Solution Platforms: x86

Solution Configurations: Debug

C/C++ -> General -> Additional Include Directories: ``` D:\Lib\SFML-2.5.1\include ```

C/C++ -> Preprocessor -> Preprocessor Definitions -> Edit -> Add:

```bash
SFML_STATIC
```

Linker -> General -> Additional Library Directories: ``` D:\Lib\SFML-2.5.1\lib ```

Linker -> Input -> Additional Dependencies -> Edit

```bash
sfml-graphics-s-d.lib
sfml-window-s-d.lib
sfml-system-s-d.lib
sfml-main-d.lib
opengl32.lib
freetype.lib
winmm.lib
gdi32.lib
```

