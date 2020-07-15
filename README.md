# Factors

## A Unix based command line command

**"factors"** is command line command that can be installed on any UNIX based operating systems and it's built on linux

## How to install factors

1. Download a copy of this factors file 1
Click immediately on the link provided above the file downloading or go to the terminal and type `$ git clone https://github.com/sam0132nodier/factors-of-a-number` to not include **$**.

1. Create a `~/bin` repository 2
* Go to the terminal and type `$ cd ~` if you are not in `$HOME`.
* Type `$ mkdir -p ~/bin` to create a bin directory in home directory.

#### 1. Copy the script to `~/bin` 3
Got to the directory where you cloned this repository and type `$ cp factors ~/bin`.

#### 1. Mark the file executable 4
Go back to your `~/bin` by typing `$ cd ~/bin` and type `$ chmod +x factors`.

#### 1. Add the `~/bin` directory to your PATH
* Open your `~/.profile` or `~/.bash_profile` in your home directory.
* Add the `~/bin` directory to the PATH by typing `$ export PATH=$PATH":$HOME/bin"` to the end of the file. You can add a comment to make sure that you don't mix things up when you want to revert the changes.
* Type `$ source ~/.profile` or `$ source ~/.bash_profile` to commit the changes

#### 1. Now **GREAT** you can run your factors command.
Go to the terminal and type `$ factors -h` to see a little usage of the program. Pass few numbers with argument like `-a` for all factors or `-p` for prime factors, try a combination of both to see both results.