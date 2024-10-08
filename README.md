# Julia Set Animation Generator with ARM Assembly

This project is a Julia Set animation generator implemented using ARM Assembly language. The Julia Set is a fractal that is generated by iterating a complex function. The goal of this project is to create an animated visualization of the Julia Set using ARM Assembly instructions.

## Table of Contents

- [Introduction](#introduction)
- [Development Environment](#development-environment)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The Julia Set is a mathematical set of complex numbers that exhibits chaotic behavior. It is generated by iterating a function on a complex plane. This project aims to create an animated visualization of the Julia Set using ARM Assembly language.

## Development Environment

Using QEMU to simulate ARM environment

## Installation

To run this project, you will need an ARM-based device or emulator. Follow these steps to install and run the Julia Set animation generator:

1. Clone this repository: `git clone https://github.com/Xiao-E5B08F/Julia-Set-animation-generator-with-ARM-assembly.git`
2. Navigate to the project directory: `cd julia-set-animation`
3. Build the project: `gcc main.c id.s name.s drawJuliaSet.s -o julia_set_animation.out`
4. Run the animation generator: `./julia_set_animation.out`

Note: Make sure you have an ARM-based device or emulator to run this project.

## Usage

To use the Julia Set animation generator, follow these steps:

1. Enter 3 random id and enter 'p' to show the authors and the sum of those id.

Example:

```
Enter id 1: 123
Enter id 2: 456
Enter id 3: 789
p
```

Output:

```
123 Liu Yan Cheng
456 Bai Hong Dek
789 Chen Kong Sang
ID Summation = 1368
```

2. Enter 'p' again to generate the Julia Set.

Example:

```
p
```

Output: 

![JuliaSet animation.gif](https://github.com/Xiao-E5B08F/Julia-Set-animation-generator-with-ARM-assembly/blob/main/JuliaSet%20animation.gif)
