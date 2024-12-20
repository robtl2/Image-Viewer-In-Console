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

<img src="./images/preview.jpg" alt="img" width="650" height="auto">

or just run:

```bash
img <image_path>
``` 

it will print the image directly in the terminal like this:

<img src="./images/preview2.jpg" alt="img" width="500" height="auto">

## Installation

first, clone the repo to your local:

```bash
git clone https://github.com/robtl2/Image-Viewer-In-Console.git
```

```bash
cd Image-Viewer-In-Console
```

#### Linux
--------------------------------

```bash
python3 -m pip install -r requirements.txt
```

```bash
cd linux
```

```bash
chmod +x img
```

```bash
sudo cp img /usr/local/bin/img
```

#### macOS
--------------------------------

```bash
/usr/local/bin/python3 -m pip install -r requirements.txt
```

```bash
cd macOS
```

```bash
chmod +x img
```

```bash
sudo cp img /usr/local/bin/img
```

#### Windows
sorry, I don't have this idea for now


## Terminal color
If your image's color display is not good, you can try to set the terminal's color to true color.(Warp's default is true color, but in ssh it may be 256 color.)

when you open a ssh session, run this command first:

```bash
export TERM=xterm-truecolor
```

in a linux ssh session:
![img](./images/truecolor.jpg)

if it's not work, change the terminal to warp :-)

## Other

in warp, default line height is 1.5, recommend set it to 1.1

<img src="./images/warp.jpg" alt="img" width="650" height="auto">









