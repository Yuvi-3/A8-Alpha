

[![Badge License]][License]   [![Button Discord]][Discord Server]

<br>

The A8-Alpha is a 16-bit computer design. It has a (almost) working **[Logisim Evolution]** circuit, along with an emulator on Windows, Mac, and Linux, for running code at full speed. There is an assembly language, along with a higher level language called Armstrong, plus more which are actively being built by the community.

## Demos
There are some demos for the Astro-8, such as the pong game and a typing program. You can locate those in the folder `/example_armstrong_programs/`.

[Go here for the documentation and more previews for some other demos](https://sam-astro.github.io/A8-Alpha-Computer/docs/Demos.html)

<p float="left">
<img src="https://github.com/sam-astro/Astro8-Computer/blob/main/images/pong.gif" width=30% />
<img class="portfolio" src="https://raw.githubusercontent.com/sam-astro/Astro8-Computer/main/images/perspectiveCube.gif"  width=30%/>
<img src="https://raw.githubusercontent.com/sam-astro/Astro8-Computer/main/images/raytracer.gif"  width=30% />
</p>

## Programming
The two most supported ways to program for the computer is using the [assembly language](https://sam-astro.github.io/A8-Alpha-Computer/docs/Architecture/Instruction%20Set.html) or [Armstrong](https://sam-astro.github.io/A8-Alpha-Computer/docs/Programming/README.html).

## Documentation
[![Button Documentation]][Documentation] 

## Installation
### Windows
1. Navigate to [the most recent release](https://github.com/sam-astro/A8-Alpha-Computer/releases), and download the **Windows** version
2. Unzip the downloaded file
### Linux
1. Make sure you have [SDL2 installed](https://wiki.libsdl.org/Installation#supported_platforms) on your system

    For debian based operating systems, you can do this with:
```
sudo apt-get install -y libsdl2-2.0-0 libsdl2-mixer-2.0-0
```
2. Navigate to [the most recent release](https://github.com/sam-astro/A8-Alpha-Computer/releases), and download the **Linux** version
3. Unzip the downloaded file
### From Source
1. Clone this repository in a command line using `git clone https://github.com/sam-astro/A8-Alpha-Computer.git` OR by downloading the repository as a .ZIP file and unzipping it to your location of choice
2. Make sure you have [SDL2 installed](https://wiki.libsdl.org/Installation#supported_platforms) on your system
3. Enter the directory `A8-Alpha-Computer/A8-Alpha-Emulator/linux-build`
4. Run CMake using `cmake ..` to generate Unix Makefile
5. Run `make -j5` to generate executable
6. The executable is `A8-Alpha-Computer/A8-Alpha-Emulator/linux-build/A8-Alpha-Emulator`

<br>
<br>

[License]: LICENSE



