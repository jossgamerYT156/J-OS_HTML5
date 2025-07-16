# J-OS_HTML5_
> A HTML5 UI Inspired on Windows NT4 for [LDS](lillydevstudios.neocities.org/J-OS/)' website!

## Features:
- Basic CLI
- Simple Commands
- Basic Window Management (By Using iframe elements)
- Quick setup process at first load, just to trigger the nostalgia


## What Can It Do?
> It can:
> -  load simple windows, give you a [File Manager](html/File%20Manager/index.html) for you to edit/create/delete new files and directories on the virtual filesystem, give you a terminal to run some commands and cause you to miss old Windows versions.
>    All while just running on your web browser

## How To Use
Load the [main html](html/index.html) in your browser, go through the setup waitime for the first time and then run `EXEC:HLP`, this will give you a fast list of commands to check at, and once you're ready, you can run your first CLI `EXEC:` command!

> Shipped Help Message
```
"EXEC:" for builtin commands:
EXEC:OPEN URI:[URL] - Opens a window.
EXEC:FM.Open - Opens The J-File Manager
EXEC:Terminal.JELF - Executes The JELF Terminal
EXEC:RST_SETUP - Reinitializes J setup
EXEC:HLP - Shows this help menu
Try: EXEC:HLP OPEN:URI
```

# What Each Command Does?

- `EXEC:` - EXEC is your predefined EXECUTION layer(No wonder the name, smartass), this prefix, tells the LiRA to EXECUTE a command that it recognizes, if it can't find it? it'll just error out.
    
    - `OPEN URI:[URL]` - This opens a specified URL on a floating window(YAY!! Graphics!), this works by creating an iframe element and giving you the control to resize/move and close it, have fun loading protected websites tho, most websites don't like embedded loading.
      
    - `FM.Open` - This opens the shipped [File Manager](html/File%20Manager/index.html) at the root of the virtual filesystem, inside here, you can Create, edit, and delete files and directories at will!
        > it comes with a shipped in Text Editor, and yes, the metadata of files IS saved for download!

    - `Terminal.JELF` - This is just your Good 'ol terminal window, you can run commands here, but don't expect very complex stuff, it is very limited as an iframe window, and i am yet finding out how to properly embed it.
    
    -  `RST_SETUP` - Wanna see the setup process again? well, have fun, because this command will run it again for your comodity(you can also reload the window after running this command if you want to.)
    
    -  `HLP` - Shows the generalized help message, and by adding a command name like `OPEN` or `FM.Open`, you can get quick-help for each command!
    -  ```
       > EXEC:HLP [COM]
       // Example:
       > EXEC:HLP OPEN
        EXEC: Built-in Command — OPEN REQ.ARG: URI:
        Usage: EXEC:OPEN URI:[URL]
        Opens a GUI window pointing to the specified URL.

# Wanna see a demo?
Lucky for you, there's a basic Demo available at YT of LiRA PC Simulator V0.0.1!
And you can watch it [here](https://youtu.be/MAg0RBLfHro?si=kt3oEkbGSvAyQkbL)!
