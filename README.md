# Color Schemes for [Windows Terminal](https://github.com/microsoft/terminal) 
## A Port of [Material Theme](https://github.com/material-theme/vsc-material-theme) , [One Dark Pro](https://github.com/Binaryify/OneDark-Pro) and [Shades of Purple](https://github.com/ahmadawais/shades-of-purple-vscode) for [Windows Terminal](https://github.com/microsoft/terminal) 

Schemes from left to right:

* Material Palenight
* One Dark Pro
* Shades of Purple

![Screenshot](https://raw.githubusercontent.com/TimilsinaBimal/WindowsTerminal-ColorScheme/master/screenshot.png)


## Install

In the `settings.json` file for Windows Terminal, find the `schemes` section and add the colors of the desired variant to the list:

```json
{
    "name": "Shades of Purple",
    "background": "#1E1E3F",
    "foreground": "#FFFFFF",
    "black": "#000000",
    "red": "#EC3A37",
    "green": "#3AD900",
    "yellow": "#FAD000",
    "blue": "#6943FF",
    "purple": "#FF2C70",
    "cyan": "#80FCFF",
    "white": "#FFFFFF",
    "brightBlack": "#5C5C61",
    "brightRed": "#EC3A37",
    "brightGreen": "#3AD900",
    "brightYellow": "#FAD000",
    "brightBlue": "#6943FF",
    "brightPurple": "#FB94FF",
    "brightCyan": "#80FCFF",
    "brightWhite": "#FFFFFF"
}
```

Example:

```json
    "schemes" :
    [
        {
          "name": "Shades of Purple",
          "background": "#1E1E3F",
          "foreground": "#FFFFFF",
          "black": "#000000",
          "red": "#EC3A37",
          "green": "#3AD900",
          "yellow": "#FAD000",
          "blue": "#6943FF",
          "purple": "#FF2C70",
          "cyan": "#80FCFF",
          "white": "#FFFFFF",
          "brightBlack": "#5C5C61",
          "brightRed": "#EC3A37",
          "brightGreen": "#3AD900",
          "brightYellow": "#FAD000",
          "brightBlue": "#6943FF",
          "brightPurple": "#FB94FF",
          "brightCyan": "#80FCFF",
          "brightWhite": "#FFFFFF"
        },
        {
            ...
        }
    ]
```

## Result Configuration File With Enabled Profile

```json
        {
            ...
        }
    "profiles" :
    [
        {
            "guid": "{574e775e-4f2a-5b96-ac1e-a2962a402336}",
            "startingDirectory": ".",
            "hidden": false,
            "colorScheme": "Shades of Purple",
            "name": "PowerShell 7",
            "source": "Windows.Terminal.PowershellCore",
            "fontFace": "fira code retina",
            "fontSize": 14
        },
    ],
    "schemes" :
    [
        {
            "name": "Shades of Purple",
            "background": "#1E1E3F",
            "foreground": "#FFFFFF",
            "black": "#000000",
            "red": "#EC3A37",
            "green": "#3AD900",
            "yellow": "#FAD000",
            "blue": "#6943FF",
            "purple": "#FF2C70",
            "cyan": "#80FCFF",
            "white": "#FFFFFF",
            "brightBlack": "#5C5C61",
            "brightRed": "#EC3A37",
            "brightGreen": "#3AD900",
            "brightYellow": "#FAD000",
            "brightBlue": "#6943FF",
            "brightPurple": "#FB94FF",
            "brightCyan": "#80FCFF",
            "brightWhite": "#FFFFFF"
        },
        {
            ...
        }
```
## License

[MIT License](./LICENSE)
