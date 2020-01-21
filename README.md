# Material Color Scheme for [Windows Terminal](https://github.com/microsoft/terminal)
A port of the [Material Theme](https://github.com/material-theme/vsc-material-theme) for [Windows Terminal](https://github.com/microsoft/terminal).

Schemes from left to right:

* Material Darker
* Material Lighter
* Material
* Material Palenight
* Material Ocean

![Screenshot](https://raw.githubusercontent.com/julianlatest/material-windows-terminal/master/screenshot.png)


## Install

In the `profile.json` settings file for Windows Terminal, find the `schemes` section and add the colors of the desired variant to the list:

```json
{
    "name": "Material",
    "background": "#263238",
    "foreground": "#eeffff",
    "black": "#000000",
    "blue": "#82aaff",
    "brightBlack": "#546e7a",
    "brightBlue": "#82aaff",
    "brightCyan": "#89ddff",
    "brightGreen": "#c3e88d",
    "brightPurple": "#c792ea",
    "brightRed": "#ff5370",
    "brightWhite": "#ffffff",
    "brightYellow": "#ffcb6b",
    "cyan": "#89ddff",
    "green": "#c3e88d",
    "purple": "#c792ea",
    "red": "#ff5370",
    "white": "#ffffff",
    "yellow": "#ffcb6b"
}
```

Example:

```json
    "schemes" :
    [
        {
            "name": "Material",
            "background": "#263238",
            "foreground": "#eeffff",
            "black": "#000000",
            "blue": "#82aaff",
            "brightBlack": "#546e7a",
            "brightBlue": "#82aaff",
            "brightCyan": "#89ddff",
            "brightGreen": "#c3e88d",
            "brightPurple": "#c792ea",
            "brightRed": "#ff5370",
            "brightWhite": "#ffffff",
            "brightYellow": "#ffcb6b",
            "cyan": "#89ddff",
            "green": "#c3e88d",
            "purple": "#c792ea",
            "red": "#ff5370",
            "white": "#ffffff",
            "yellow": "#ffcb6b"
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
    {
        "defaults":
        {
            "fontFace": "CascadiaCode Nerd Font",
            "fontSize": 10,
        },
        "list":
        [
            {
                "guid": "{574e775e-4f2a-5b96-ac1e-a2962a402336}",
                "hidden": false,
                "name": "PowerShell Core",
                "source": "Windows.Terminal.PowershellCore",
                "startingDirectory": null,
                "colorScheme": "Material"
            }
        ]
    },
    "schemes" :
    [
        {
            "name": "Material",
            "background": "#263238",
            "foreground": "#eeffff",
            "black": "#000000",
            "blue": "#82aaff",
            "brightBlack": "#546e7a",
            "brightBlue": "#82aaff",
            "brightCyan": "#89ddff",
            "brightGreen": "#c3e88d",
            "brightPurple": "#c792ea",
            "brightRed": "#ff5370",
            "brightWhite": "#ffffff",
            "brightYellow": "#ffcb6b",
            "cyan": "#89ddff",
            "green": "#c3e88d",
            "purple": "#c792ea",
            "red": "#ff5370",
            "white": "#ffffff",
            "yellow": "#ffcb6b"
        },
        {
            ...
        }
```
## License

[MIT License](./LICENSE)
