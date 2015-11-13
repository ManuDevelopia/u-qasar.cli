# U-Qasar CLI tool

U-Qasar CLI is a command line tool that provides U-Qasar Information right to the console using a few keystrokes.

Why use this old-fashined command line tool?
--------------------------------------------

Anwser is simple, you spent a lot of time in terminal compiling, mvn, git, ... And as soon as you realize that using command line is faster that login and selecting items, you will fall in love with this tool. 

Usage & Commands
----------------
As you type uclisar in terminal, you will see something like the following:

>Usage: uclisar [OPTIONS] COMMAND [ARGS]...
>
>  U-Qasar CLI X.X.X version.
>
>  This is a proof of concept about how can be implented a CLI tool to
>  retrieve from U-Qasar information from Projects and QModels.
>
>Options:
>  --help  Show this message and exit.
>
>Commands:
>  historic      Retrieve all existing Historic Values in...
>  measurements  Retrieve all measurements gathered from an...
>  project       Retrieve an existing Project in platform by...
>  projects      Retrieve all existing Projects in platform.
>  qmodel        Retrieve an existing Project in platform by...
>  qmodels       Retrieve all existing QModels in platform.

To Do
-----
- Write the functions, for now they seems more like an interface than a real tool
- Read config from an external file, placed at ~/.config/uqasar.cli or simiar
- Wrtie test
- Write documentation
- Define visual outputs, colors, Themes?
