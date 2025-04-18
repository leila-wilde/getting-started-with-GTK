# Getting Started With GTK

A repository of some beginner GTK projects I have followed to learn how to use GTK to create GUIs in my C projects.  

## Installation process:

#### Debian Linux:

``` bash
sudo apt install libgtk-4-dev
```

|Distribution |Binary package |Development package |Additional packages |
|-------------|---------------|--------------------|--------------------|
|Arch         |gtk4           |-                   |-                   |
|Debian/Ubuntu|libgtk-4-1     |libgtk-4-dev        |gtk-4-examples      |
|Fedora       |gtk4           |gtk4-devel          |-                   |


#### Windows:

[Installation guide for Windows](https://www.gtk.org/docs/installations/windows/)

## Getting started

[GTK website](https://www.gtk.org/docs/getting-started/)

To build a program, run:

``` bash
gcc $(pkg-config --cflags gtk4) program.c -o program $(pkg-config --libs gtk4)
```

