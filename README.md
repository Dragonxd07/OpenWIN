**Advanced bootloader with Lua REPL, protected access and cool interface (OpenComputers)**

## Installation

For **OpenOS**, just run this command(You are need an internet card to run this):

```
wget -fq https://raw.githubusercontent.com/BrightYC/Cyan/master/installer.lua && installer.lua
```

For **MineOS**, you need to find app with name `Cyan BIOS`. That's it!
## Lua 5.3
This function is the basic Lua 5.3 interpreter with the following functions:

* os.sleep([timeout: number]) -- Basic delay (You can interrupt this via CTRL+ALT+C).
* proxy(componentName: string): component proxy or nil -- Like component.eeprom in OpenOS/MineOS.
* read(lastInput: string or nil): string or nil -- Very basic read, like io.read()
* print(...) -- Very basic print.

## Internet boot
This function downloads the specified file by URL and executes it.

## Rename/Format
This functions renames/formats the selected file system.

## Whitelist access
That's feature can protect your BIOS from other people and can ask trusted user for boot.

## Images/Videos

[![](https://img.youtube.com/vi/89K8mWFEJKw/0.jpg)](https://www.youtube.com/watch?v=89K8mWFEJKw)
![](https://i.imgur.com/WWiX2tQ.png)
![](https://i.imgur.com/pnFC0cO.png)
![](https://i.imgur.com/6QXw6LX.png)
![](https://i.imgur.com/Yi7v2n2.png)
