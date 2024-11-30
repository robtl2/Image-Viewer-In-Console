# Image-Viewer-In-Console
A Toy for viewing images in terminal.
Use character "▄" preview image in a pixel style.
Maybe you can use it to view some images in your ssh mission.

## Usage

It is strongly recommended to use WARP as the terminal tool, as other tools may have poor color display effects.
- [Warp](https://www.warp.dev/)

#

To use it, go to the directory of the images and run:

```bash
img
```

Use the arrow keys to navigate the image.  
Press 'esc' to exit.

it's should be like this:

![img](./images/preview.jpg)

or just run:

```bash
img <image_path>
``` 

it's will print the image directly in the terminal like this:

<img src="./images/preview2.jpg" alt="img" width="400px" height="auto">

## Installation

first, clone the repo to your local:

```bash
git clone https://github.com/robtl2/Image-Viewer-In-Console.git
```

#### Linux
--------------------------------

```bash
cd linux
```

```bash
chmod +x img
```

```bash
sudo cp img /usr/local/bin/img
```

```bash
python3 -m pip install -r requirements.txt
```

#### macOS
--------------------------------

```bash
cd macOS
```

```bash
chmod +x img
```

```bash
sudo cp img /usr/local/bin/img
```

```bash
/usr/local/bin/python3 -m pip install -r requirements.txt
```

#### Windows
sorry, I don't have this idea for now


## Terminal color
If you image's color is not good, you can try to set the terminal's color to true color.(Warp's default is true color, but in ssh it may be 256 color.)

when you open a ssh session, run this command first:

```bash
export TERM=xterm-truecolor
```

in a linux ssh session:
![img](./images/truecolor.jpg)

if it's not work, change the terminal to warp :-)










