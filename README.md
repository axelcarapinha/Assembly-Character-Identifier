# Assembly-Character-Identifier
College project made with Assembly RISC-V to identify a character in a specific image, based on RGB and Hue.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#results">Usage</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About the project
Final project done in the _Computer Architecture I_ class, during the 1st year of the computer science degree.

With it I was able to improve my knowledge with:
* C programming language
* Linux terminal
* Assembly RISC-V
* Image properties (RGB, Hue, ...)

<!-- HOW TO START IT -->
## Getting started
### Prerequisites
1. Linux system (for the Makefile)
2. ImageMagick package
3. <a href="https://github.com/TheThirdOne/rars">RARS</a> assembler and runtime system for RISC-V, 

### Installation (ImageMagick)
```sh
# Choose the needed one:

sudo apt-get install imagemagick # ubuntu
sudo yum install ImageMagick     # centOS / REHL
sudo dnf install ImageMagick     # Fedora
sudo pacman -S imagemagick       # Arch Linux
```

## Usage
After pulling the code, you can execute in two ways:

### (1.1) RISC-V
1. Open the folder containing the RARS file and execute it with the command below:
```sh
java -Xmx8g -XX:+UseParallelGC -jar rars1_6.jar # for the 1_6 version!
```
2. Open _assembly.asm_ with RARS
3. Save, compile and run the code

### (1.2) C code 
In Linux, open the containing folder and enter "make" in the terminal

### (2.) Interface
It should appear:
  -  a question in the terminal asking for the character to select in the image
  -  a new image file with a small yellow cross made in the head of the chosen character

## Results
![Starting image](https://github.com/axelcarapinha/Assembly-Character-Identifier/edit/main/images/README.md)

![Character 1](https://github.com/axelcarapinha/Assembly-Character-Identifier/edit/main/images/char1.png)
![Character 2](https://github.com/axelcarapinha/Assembly-Character-Identifier/edit/main/images/char2.png)
![Character 3](https://github.com/axelcarapinha/Assembly-Character-Identifier/edit/main/images/char3.png)









