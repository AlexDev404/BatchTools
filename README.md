# BatchTools
The classic BatchTools that includes all the hard to find tools like graphic.exe, ctext.exe, colous.exe, etc.

- These are the batchtools I dug up from the internet a while back and have lost them on my harddrive but just found them until recently, so I decided to post it here for easier access and to share it with you all too.

- You won't be able to find these applications anywhere else (unless you are a digger like me).

- All these applications listed here are either extinct or nonexistent anymore.

- These applications provide you to create a multitude of games and software.

- If you are a person who like retro (like me), these are the right tools for you. With these you are able to create batch-style games, etc.

This package contains:

- `colous.exe`
- `ctext.exe`
- `Graphic.exe`
- `Kbd.exe`
- `Mouse.exe`

Most of these programs are undocumented or have lost their documentation, so will take a while to learn. Programs like `ctext.exe` do include some breif documentation if evoked with the program's name while in the directory saved using the Windows Console/Command Prompt ( `cmd.exe` ).

Output from ctext/colous.exe:

`CTEXT.EXE : Version 2K.232 (C)opyright Dennis Bareis 2000`
<br>
`http://www.labyrinth.net.au/~dbareis/index.htm(dead link) (dbareis@labyrinth.net.au)`

If you are like me you are not happy that windows does not support ANSI color
codes on the command line.

This program allows you to display text in different colors in batch files etc.

Simply specify the text (surrounded by double quotes if required) and
imbed any control codes as follows (codes start with '{', end with '}'):

    {{      = Escape control character ('{')
    {\n}    = New Line
    {color} = 1. Hex code for color ("0c" = bright red on black)
              2. Color "bred on black", "green" etc
                 Valid colors names are:
                   "BLACK", "BLUE", "GREEN", "CYAN", "RED", "MAGENTA", "BROWN",
                   "WHITE", "GRAY", "BBLUE", "BGREEN", "BCYAN", "BRED",
                   "BMAGENTA", "YELLOW", "BWHITE"

Note that there need be no text as in the following fragment from a
batch file:

    ctext.exe "{bred on black}"
    This message is in bright red on black
    ctext.exe "{07}"
