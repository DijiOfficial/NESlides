# NES Project

## Requirement to play

- Mesen or any other emulator for NES
- Controller

### Requirement to compile

- Make
- CC65 compiler

## Running the Game

To run the game simply download the latest release [here](https://github.com/DijiOfficial/NESlides/releases/tag/v1.0) and run the `NESlides\out\NESlides.nes` with [Mesen](https://www.mesen.ca).

To play the game load the `.nes` file with an Emulator like Mesen. You will need a controller to play.

#### Controls

| Control           | Action                       |  
|-------------------|------------------------------|  
| **D-PAD**         | Move / Change Selection      |  
| **SELECT**        | Confirm Selection            |  
| **X & A**         | Change Audio                 |  
| **START**         | Cahnge Color Palett          |  
| **Y & B**         | Shoot                        |  

**AUDIO WARNING** The audio starts on max volume so be careful when playing it with headphones!
* `X & A` are west and south buttons, if you are using a different controller.
* `Y & B` are north and east buttons, if you are using a different controller

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
