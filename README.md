# The_Aeroplane_Game MIG-29

CSE-1211 Lab Project (Fall 2022)


## Outline
This is an academic project of the course CSE-1211 for 1st year 2nd semester in the Department of Computer Science and Engineering of the Univeristy of Dhaka. The game project is developed for only **Linux** as of now using **SDL2**

## In Details
**MIG-29** is a 2D Third-person Shooting game. 

The game has two levels till now **Easy** and **Hard** . Both levels are endless. 


The game will over when life becomes zero.

I will try to add new levels and challenges in the game in near future.

## Pre-requisites
**For Debian and Debian based distributions:**
* ```g++```
* ```libsdl2-image-dev``` 
* ```libsdl2-ttf-dev```
* ```libsdl2-mixer-dev```
* ```libsdl2-dev``` 
or equivalent packages for other distributions.

## Running the game

### using Terminal
After opening the terminal in the folder where the game folder issimply use the command `make all` or `./a.out` or 
write 
```g++ src/*.cpp -lSDL2 -lSDL2_image -lSDL2_ttf -lSDL2_mixer && ./a.out```
to run the game.

### using Unity Launcher
open the **MIG-29.desktop** using any text editor (gedit,nano,vim,vscode etc.).

In the file assign the full path of `a.out` in `Exec`. 
Like this:

```Exec=/home/user-name/MIG-29/a.out```

then assign the full path of this game folder in `Path`. 
Like this:

```Path=/home/user-name/MIG-29/```

finally assign full path of an icon image in `Icon`. 
Like this:

```Icon=/home/user-name/MIG-29/assets/obj & background/mainmenubg.png```

After that move or paste the **MIG-29.desktop** file in desktop and right clicking click on **Allow Launching**
and in **Properties** make sure you ticked **Allow executing as program** in the **Permissions** section.
Now, double clicking will launch the game. 


