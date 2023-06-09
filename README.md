## The_Benatar_space_game
Adventure of a boy with the benatar.

## Screenshots

[[Back to top]](https://github.com/Devesh-code/The-Benatar-space-game#The_Benatar_space_game)

| ![Screen 1](https://i.imgur.com/puDP3f8.jpg) | ![Screen 2](https://i.imgur.com/Xk0gO5i.jpg) |
|---------------------------------------------|---------------------------------------------|
| ![Screen 3](https://i.imgur.com/ik0DDxT.jpg) | ![Screen 4](https://i.imgur.com/8w5ydNf.jpg) |
|---------------------------------------------|---------------------------------------------|
| ![Screen 5](https://i.imgur.com/1vfMMXJ.jpg) | ![Screen 6](https://i.imgur.com/Sa7eDsF.jpg) |

## Demo

[[Back to top]](https://github.com/Devesh-code/The-Benatar-space-game#The_Benatar_space_game)

Follow the below video link to see how I fared on ``The benatar space game``

[![Space Shooter Demo - link](https://i.imgur.com/puDP3f8.jpg)]

(https://vimeo.com/818505391)

## Controls

[[Back to top]](https://github.com/Devesh-code/The-Benatar-space-game#The_Benatar_space_game)

|              | Button              |
|--------------|---------------------|
| Move Left    | <kbd>a</kbd>     |
| Move right   | <kbd>d</kbd>    |
| Move top     | <kbd>w</kbd>    |
| Move down    | <kbd>s</kbd>    |
| Fire bullets | <kbd>spacebar</kbd> |
| Quit game    | <kbd>q</kbd>      |

## Game Features

[[Back to top]](https://github.com/Devesh-code/The-Benatar-space-game#The_Benatar_space_game)

- Health bar for the space ship
- Score board to show how you are faring so far
- Multiple type alien 
- 5 lives per game
- Fun to play :)

## Installation

[[Back to top]](https://github.com/Devesh-code/The-Benatar-space-game#The_Benatar_space_game)

### For `Windows`

- [Download the prebuilt zip file and unzip it.](https://github.com/Devesh-code/The-Benatar-space-game/archive/refs/heads/main.zip)
- Run the executable named `benatar` inside the extracted file.

### `Linux/Debian` based systems

#### Option 1: Download the zipped executable file

- [Download the latest zip file for linux](https://github.com/Devesh-code/The-Benatar-space-game/archive/refs/heads/main.zip)
- Unzip the file

If your download was saved on the `~/Downloads` folder

Press <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd> to open the shell if you are on `GNU/Linux` based systems and type

```bash
$ unzip ~/Downloads/benatar-0.0.3.Linux.zip -d ~/Desktop
$ cd ~/Desktop
$ ## navigate to the unzipped file and change the file permissions for the executable
~/Desktop $ chmod +x benatar
~/Desktop $ ./benatar
```

This will unzip the file on your `Desktop`, you can replace it with the directory of your choice

**NOTE** : If it gives you an error, you probably don't have `unzip` installed in your system.

```bash
$ sudo apt-get install unzip
```
That should fix the error.

- Run the executable named `benatar`

A Similar process would be followed for `OS X`

#### Option 2: Build from source

You need to have `pygame` installed for this option. 

##### Clone the repo
```sh
$ git clone https://github.com/Devesh-code/The-Benatar-space-game.git
$ cd The-Benatar-space-game/
$ chmod +x benatar.py
$ python benatar.py
```


### For `Ubuntu/Debian`

```bash
$ sudo apt-get install python-pygame
```

##### Clone the repo

```bash
$ git clone https://github.com/Devesh-code/The-Benatar-space-game.git
$ cd The-Benatar-space-game/ 
$ python benatar.py
```
