# sfml-test

Test VS2019 project to see if sfml works

[SFML DOWNLOAD](https://www.sfml-dev.org/download.php)

[HO1 Assets](https://drive.google.com/open?id=1xct6DWbrsohSMAduz9xP3QnTVfCJh6KF)

## Project properties Setup:
1. Put the `SFML-2.5.1` directory in C:\ or any other folder as long as you change the path in the following path accordingly
2. In *`C/C++`->`General`->`Additional Include Directories`* paste this: `C:\SFML-2.5.1\include;%(AdditionalIncludeDirectories)`
3. In *`C/C++`->`Preprocessor`->`Preprocesor Definitions`* paste this: `SFML_STATIC;_DEBUG;_CONSOLE;%(PreprocessorDefinitions)`
4. In *`Linker`->`General`->`Additional Library Directories` paste this: `C:\SFML-2.5.1\lib;%(AdditionalLibraryirectories)`
5. In *`Linker`->`Input`->`Additional Dependencies` paste this: `winmm.lib;opengl32.lib;freetype.lib;sfml-graphics-s-d.lib;sfml-window-s-d.lib;sfml-system-s-d.lib;%(AdditionalDependencies)`
