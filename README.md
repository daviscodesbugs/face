# Face

A linux CLI for emojis

Take a look at the [reference page](reference.md)

## Installation

Clone the repository

	cd /opt
    git clone https://github.com/daviscodesbugs/face.git

Make `face` executable

    cd face/
	chmod +x ./face

Create symlink

    sudo ln -sf /opt/face/face /usr/local/bin/face

Install dependencies

    sudo pip install pyperclip

## Usage

See available faces

    face help

Copy a face to the clipboard using it's name  
If no name is specified, the default 😊 will be copied

	face wink tongue

Paste where ever you need it! `(Ctrl+v)`

    I love Face! 😜
