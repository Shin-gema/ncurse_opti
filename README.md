# TDL — Terminal Direct Media Library

## Description

TDL is graphical library inside a terminal.

The purpose of this project is to permitted the majority of the functionality of standard graphic libraries like SDL or SFML inside a terminal. It is written and usable in C++.

# Install

## From AUR

To install from the AUR you can found the link [here](https://aur.archlinux.org/packages/tdl_terminal_directmedia_library).

## From this repository

To install and use TDL in your project please follow these steps    

1. Clone this repository.

2. Create and build folders and run the following command inside.
```
cmake .. -DCMAKE_INSTALL_PREFIX=/usr/ -DBUILD_SHARED_LIBS=ON
cmake --build . --target install (you may need to run this as sudo)
```
The file should be correctly installed, and you can compile your code with the library using:
``` make your_project -ltdl```

## State of Developpement

Development is focused in adding new feature and improve the C++ Library. You can check the list below for a better view of what is left to add for the official v1.0.

### RoadMap V1.0
- [x] Implement window class for terminal display
- [x] Implement texture and sprite management
- [x] Implement event handler
- [x] Implement keyboard input manager
- [x] Implement music and sound solution
- [x] Implement Text method.
- [x] Improve resolution and performance
- [ ] Implement new image loading solution. (actually only PNG is handle)

## External library used
- [libpng](https://github.com/pnggroup/libpng) under [png library licence](https://spdx.org/licenses/libpng-2.0.html)
- [openAl](https://www.openal.org/) under [GNU LGPL](https://www.gnu.org/licenses/lgpl-2.1.html)
- [freetype](https://www.freetype.org/) under [GNU LGPL](https://www.gnu.org/licenses/lgpl-2.1.html)
- [sndfile](http://www.mega-nerd.com/libsndfile/) under [GNU LGPL](https://www.gnu.org/licenses/lgpl-2.1.html)

## Contributing

 If you want to contribute to this project, you can simply follow this step :

- Fork this repository
- Implement your functionnality in your repo
- Create an pull request
- And your done !