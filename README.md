# NES Project

## Requirement

- Mesen or any other emulator for NES

### Requirement to compile

- Make
- CC65 compiler

## Running the Game

To run the game simply download the latest release [here]() and run the `out\NESlides.nes` with [Mesen](https://www.mesen.ca).

## Compiling the Project from source

Before compiling you will need a `cc65 compiler` which you can find [here](https://github.com/cc65/cc65/releases/tag/V2.19). 
Download the latest source code version. Unzip it and rename it to "cc65" then move it to the `C:\` folder.

Then download this project's code from the top right corner and Unzip when downloaded.

Open the Command Prompt using `Win + R` and typing `cmd` or by searching for command prompt.
Then navigate to the folder you just downloaded.

```cmd
cd C:\ProjectDirectory

in my case

cd C:\Users\me\Downloads\NESlides-main
```

You can make this step easier by copying the path from the explorer.

Finally type 

```cmd
make clean && make all
```

you can now find in `ProjectDirectory\out` a file called `NESlides.nes` which you can load in Mesen.
