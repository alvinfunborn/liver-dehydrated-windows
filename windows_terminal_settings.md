# settings.json
```
// This file was initially generated by Windows Terminal 1.4.3243.0 // It should still be usable in newer versions, but newer versions might have additional // settings, help text, or changes that you will not see unless you clear this file // and let us generate a new one for you.

// To view the default settings, hold "alt" while clicking on the "Settings" button. // For documentation on these settings, see: https://aka.ms/terminal-documentation 
{ "$schema": "https://aka.ms/terminal-profiles-schema",

// system, dark, light
"theme": "dark",

// true, false, "mru", "inOrder", "disabled"
"tabSwitchMode": true,
"alwaysShowTabs": true,
// "equal", "titleLength", "compact"
"tabWidthMode": "equal",
"confirmCloseAllTabs": false,

"startOnUserLogin": false,
// "default", "maximized", "fullscreen", "focus", "maximizedFocus"
"launchMode": "default",
// Coordinates as a string in the following formats: ",", "#,#", "#,", ",#"
"initialPosition": ",",
// This is the number of character columns displayed in the window upon first load
"initialCols": 120,
// This is the number of rows displayed in the window upon first load
"initialRows": 30,

"alwaysOnTop": false,
"showTabsInTitlebar": true,
"showTerminalTitleInTitlebar": true,

"copyOnSelect": false,
"copyFormatting": false,
"wordDelimiters": " ./\\()\"'-:,.;<>~!@#$%^&*|+=[]{}~?│",
"largePasteWarning": true,
"multiLinePasteWarning": true,

// only available in preview
"disableAnimations": false,
"experimental.rendering.forceFullRepaint": false,
"experimental.rendering.software": false,

"snapToGridOnResize": true,


"defaultProfile": "{2c4de342-38b7-51cf-b940-2309a097f518}",

// You can add more global application settings here.
// To learn more about global settings, visit https://aka.ms/terminal-global-settings

// If enabled, selections are automatically copied to your clipboard.
"copyOnSelect": false,

// If enabled, formatted data is also copied to your clipboard
"copyFormatting": false,

// A profile specifies a command to execute paired with information about how it should look and feel.
// Each one of them will appear in the 'New Tab' dropdown,
//   and can be invoked from the commandline with `wt.exe -p xxx`
// To learn more about profiles, visit https://aka.ms/terminal-profile-settings
"profiles":
{
    "defaults":
    {
        // Put settings here that you want to apply to all profiles.
        "suppressApplicationTitle": false,
        "useAcrylic": true,
        // only available in preview
        "bellStyle": "none",
    },
    "list":
    [
        {
            "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
            "hidden": false,
            "name": "Ubuntu",
            // "source": "Windows.Terminal.Wsl",
            "commandLine": "wsl.exe",
            "acrylicOpacity": 0.7,
            "startingDirectory": "C:/workspace"
        },
        {
            // Make changes here to the powershell.exe profile.
            "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
            "name": "PowerShell",
            "commandline": "powershell.exe",
            "hidden": false,
            "colorScheme": "Tomorrow Night Blue",
            "acrylicOpacity": 0.6,
            "startingDirectory": "C:/workspace"
        },
        {
            // Make changes here to the cmd.exe profile.
            "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
            "name": "Cmd",
            "commandline": "cmd.exe",
            "hidden": false,
            "colorScheme": "Dark Pastel",
            "acrylicOpacity": 0.7,
            "startingDirectory": "C:/workspace"
        },
        {
            "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
            "hidden": false,
            "name": "Azure Cloud Shell",
            "source": "Windows.Terminal.Azure"
        },
    ]
},

// Add custom color schemes to this array.
// To learn more about color schemes, visit https://aka.ms/terminal-color-schemes
"schemes": [
    {
        "name": "Tomorrow Night",
        "black": "#000000",
        "red": "#cc6666",
        "green": "#b5bd68",
        "yellow": "#f0c674",
        "blue": "#81a2be",
        "purple": "#b294bb",
        "cyan": "#8abeb7",
        "white": "#ffffff",
        "brightBlack": "#000000",
        "brightRed": "#cc6666",
        "brightGreen": "#b5bd68",
        "brightYellow": "#f0c674",
        "brightBlue": "#81a2be",
        "brightPurple": "#b294bb",
        "brightCyan": "#8abeb7",
        "brightWhite": "#ffffff",
        "background": "#1d1f21",
        "foreground": "#c5c8c6"
    },
    {
        "name": "Tomorrow Night Blue",
        "black": "#000000",
        "red": "#ff9da4",
        "green": "#d1f1a9",
        "yellow": "#ffeead",
        "blue": "#bbdaff",
        "purple": "#ebbbff",
        "cyan": "#99ffff",
        "white": "#ffffff",
        "brightBlack": "#000000",
        "brightRed": "#ff9da4",
        "brightGreen": "#d1f1a9",
        "brightYellow": "#ffeead",
        "brightBlue": "#bbdaff",
        "brightPurple": "#ebbbff",
        "brightCyan": "#99ffff",
        "brightWhite": "#ffffff",
        "background": "#002451",
        "foreground": "#ffffff"
    },
    {
        "name": "Tomorrow Night Eighties",
        "black": "#000000",
        "red": "#f2777a",
        "green": "#99cc99",
        "yellow": "#ffcc66",
        "blue": "#6699cc",
        "purple": "#cc99cc",
        "cyan": "#66cccc",
        "white": "#ffffff",
        "brightBlack": "#000000",
        "brightRed": "#f2777a",
        "brightGreen": "#99cc99",
        "brightYellow": "#ffcc66",
        "brightBlue": "#6699cc",
        "brightPurple": "#cc99cc",
        "brightCyan": "#66cccc",
        "brightWhite": "#ffffff",
        "background": "#2d2d2d",
        "foreground": "#cccccc"
    },
    {
        "name": "Tomorrow",
        "black": "#000000",
        "red": "#c82829",
        "green": "#718c00",
        "yellow": "#eab700",
        "blue": "#4271ae",
        "purple": "#8959a8",
        "cyan": "#3e999f",
        "white": "#ffffff",
        "brightBlack": "#000000",
        "brightRed": "#c82829",
        "brightGreen": "#718c00",
        "brightYellow": "#eab700",
        "brightBlue": "#4271ae",
        "brightPurple": "#8959a8",
        "brightCyan": "#3e999f",
        "brightWhite": "#ffffff",
        "background": "#ffffff",
        "foreground": "#4d4d4c"
    },
    {
        "name": "Tomorrow Night Burns",
        "black": "#252525",
        "red": "#832e31",
        "green": "#a63c40",
        "yellow": "#d3494e",
        "blue": "#fc595f",
        "purple": "#df9395",
        "cyan": "#ba8586",
        "white": "#f5f5f5",
        "brightBlack": "#5d6f71",
        "brightRed": "#832e31",
        "brightGreen": "#a63c40",
        "brightYellow": "#d2494e",
        "brightBlue": "#fc595f",
        "brightPurple": "#df9395",
        "brightCyan": "#ba8586",
        "brightWhite": "#f5f5f5",
        "background": "#151515",
        "foreground": "#a1b0b8"
    },
    {
        "name": "Tomorrow Night Bright",
        "black": "#000000",
        "red": "#d54e53",
        "green": "#b9ca4a",
        "yellow": "#e7c547",
        "blue": "#7aa6da",
        "purple": "#c397d8",
        "cyan": "#70c0b1",
        "white": "#ffffff",
        "brightBlack": "#000000",
        "brightRed": "#d54e53",
        "brightGreen": "#b9ca4a",
        "brightYellow": "#e7c547",
        "brightBlue": "#7aa6da",
        "brightPurple": "#c397d8",
        "brightCyan": "#70c0b1",
        "brightWhite": "#ffffff",
        "background": "#000000",
        "foreground": "#eaeaea"
    },
    {
        "name": "Solarized Darcula",
        "black": "#25292a",
        "red": "#f24840",
        "green": "#629655",
        "yellow": "#b68800",
        "blue": "#2075c7",
        "purple": "#797fd4",
        "cyan": "#15968d",
        "white": "#d2d8d9",
        "brightBlack": "#25292a",
        "brightRed": "#f24840",
        "brightGreen": "#629655",
        "brightYellow": "#b68800",
        "brightBlue": "#2075c7",
        "brightPurple": "#797fd4",
        "brightCyan": "#15968d",
        "brightWhite": "#d2d8d9",
        "background": "#3d3f41",
        "foreground": "#d2d8d9"
    },
    {
        "name": "Solarized Dark - Patched",
        "black": "#002831",
        "red": "#d11c24",
        "green": "#738a05",
        "yellow": "#a57706",
        "blue": "#2176c7",
        "purple": "#c61c6f",
        "cyan": "#259286",
        "white": "#eae3cb",
        "brightBlack": "#475b62",
        "brightRed": "#bd3613",
        "brightGreen": "#475b62",
        "brightYellow": "#536870",
        "brightBlue": "#708284",
        "brightPurple": "#5956ba",
        "brightCyan": "#819090",
        "brightWhite": "#fcf4dc",
        "background": "#001e27",
        "foreground": "#708284"
    },
    {
        "name": "Solarized Dark Higher Contrast",
        "black": "#002831",
        "red": "#d11c24",
        "green": "#6cbe6c",
        "yellow": "#a57706",
        "blue": "#2176c7",
        "purple": "#c61c6f",
        "cyan": "#259286",
        "white": "#eae3cb",
        "brightBlack": "#006488",
        "brightRed": "#f5163b",
        "brightGreen": "#51ef84",
        "brightYellow": "#b27e28",
        "brightBlue": "#178ec8",
        "brightPurple": "#e24d8e",
        "brightCyan": "#00b39e",
        "brightWhite": "#fcf4dc",
        "background": "#001e27",
        "foreground": "#9cc2c3"
    },
    {
        "name": "Dark+",
        "black": "#000000",
        "red": "#cd3131",
        "green": "#0dbc79",
        "yellow": "#e5e510",
        "blue": "#2472c8",
        "purple": "#bc3fbc",
        "cyan": "#11a8cd",
        "white": "#e5e5e5",
        "brightBlack": "#666666",
        "brightRed": "#f14c4c",
        "brightGreen": "#23d18b",
        "brightYellow": "#f5f543",
        "brightBlue": "#3b8eea",
        "brightPurple": "#d670d6",
        "brightCyan": "#29b8db",
        "brightWhite": "#e5e5e5",
        "background": "#0e0e0e",
        "foreground": "#cccccc"
    },
    {
        "name": "Dark Pastel",
        "black": "#000000",
        "red": "#ff5555",
        "green": "#55ff55",
        "yellow": "#ffff55",
        "blue": "#5555ff",
        "purple": "#ff55ff",
        "cyan": "#55ffff",
        "white": "#bbbbbb",
        "brightBlack": "#555555",
        "brightRed": "#ff5555",
        "brightGreen": "#55ff55",
        "brightYellow": "#ffff55",
        "brightBlue": "#5555ff",
        "brightPurple": "#ff55ff",
        "brightCyan": "#55ffff",
        "brightWhite": "#ffffff",
        "background": "#000000",
        "foreground": "#ffffff"
    }
],

// Add custom actions and keybindings to this array.
// To unbind a key combination from your defaults.json, set the command to "unbound".
// To learn more about actions and keybindings, visit https://aka.ms/terminal-keybindings
"actions":
[
    { "command": "closeWindow", "keys": "alt+w" },
    // Press Ctrl+Shift+F to open the search box
    { "command": "find", "keys": "ctrl+f" },
    { "command": "openNewTabDropdown", "keys": "alt+d" },
    { "command": "openSettings", "keys": "ctrl+alt+s" },

    { "command": "toggleFullscreen", "keys": "f11" },
    { "command": "toggleFocusMode" , "keys": "f10"},
    { "command": "toggleAlwaysOnTop", "keys": "f9" },

    { "command": { "action": "sendInput", "input": "ephemeral" }, "keys": "alt+e" },

    { "command": "closeTab", "keys": "ctrl+w" },
    { "command": "closeOtherTabs", "keys": "ctrl+shift+w" },
    { "command": "closeTabsAfter", "keys": "" },
    { "command": "duplicateTab", "keys": "ctrl+shift+c" },
    { "command": "newTab", "keys": "ctrl+n" },
    { "command": { "action": "newTab", "index": 0 }, "keys": "alt+1" },
    { "command": { "action": "newTab", "index": 1 }, "keys": "alt+2" },
    { "command": { "action": "newTab", "index": 2 }, "keys": "alt+3" },
    { "command": { "action": "newTab", "index": 3 }, "keys": "alt+4" },
    { "command": { "action": "newTab", "index": 4 }, "keys": "alt+5" },
    { "command": { "action": "newTab", "index": 5 }, "keys": "alt+6" },
    { "command": { "action": "newTab", "index": 6 }, "keys": "alt+7" },
    { "command": { "action": "newTab", "index": 7 }, "keys": "alt+8" },
    { "command": { "action": "newTab", "index": 8 }, "keys": "alt+9" },
    { "command": "nextTab", "keys": "alt+]" },
    { "command": "prevTab", "keys": "alt+[" },
    { "command": "nextTab", "keys": "ctrl+tab" },
    { "command": "prevTab", "keys": "ctrl+shift+tab" },
    { "command": "tabSearch", "keys": "ctrl+`"},
    { "command": { "action": "switchToTab", "index": 0 }, "keys": "ctrl+1" },
    { "command": { "action": "switchToTab", "index": 1 }, "keys": "ctrl+2" },
    { "command": { "action": "switchToTab", "index": 2 }, "keys": "ctrl+3" },
    { "command": { "action": "switchToTab", "index": 3 }, "keys": "ctrl+4" },
    { "command": { "action": "switchToTab", "index": 4 }, "keys": "ctrl+5" },
    { "command": { "action": "switchToTab", "index": 5 }, "keys": "ctrl+6" },
    { "command": { "action": "switchToTab", "index": 6 }, "keys": "ctrl+7" },
    { "command": { "action": "switchToTab", "index": 7 }, "keys": "ctrl+8" },
    { "command": { "action": "switchToTab", "index": 8 }, "keys": "ctrl+9" },

    { "command": { "action": "renameTab", "title": "ephemeral" }, "keys": "" },
    // only available in preview
    { "command": "openTabRenamer", "keys": "f2" },
    // Change the tab's color to a bright magenta
    { "command": { "action": "setTabColor", "color": "#ff00ff" }, "keys": "" },
    // Reset the tab's color
    { "command": { "action": "setTabColor", "color": null }, "keys": "" },
    { "command": "openTabColorPicker", "keys": ""},

    { "command": "closePane", "keys": "alt+-" },
    { "command": { "action": "moveFocus", "direction": "down" }, "keys": "alt+down" },
    { "command": { "action": "moveFocus", "direction": "left" }, "keys": "alt+left" },
    { "command": { "action": "moveFocus", "direction": "right" }, "keys": "alt+right" },
    { "command": { "action": "moveFocus", "direction": "up" }, "keys": "alt+up" },
    // only available in preview
    { "command": "togglePaneZoom", "keys": "" },
    { "command": { "action": "resizePane", "direction": "down" }, "keys": "alt+shift+." },
    { "command": { "action": "resizePane", "direction": "left" }, "keys": "alt+shift+," },
    { "command": { "action": "resizePane", "direction": "right" }, "keys": "alt+shift+/" },
    { "command": { "action": "resizePane", "direction": "up" }, "keys": "alt+shift+;" },

    // Press Alt+Shift+D to open a new pane.
    // - "split": "auto" makes this pane open in the direction that provides the most surface area.
    // - "splitMode": "duplicate" makes the new pane use the focused pane's profile.
    // To learn more about panes, visit https://aka.ms/terminal-panes
    { "command": { "action": "splitPane", "split": "vertical", "splitMode": "duplicate" }, "keys": "ctrl+alt+c" },
    { "command": { "action": "splitPane", "split": "horizontal", "splitMode": "duplicate" }, "keys": "ctrl+alt+shift+c" },
    { "command": { "action": "splitPane", "split": "vertical", "splitMode": "duplicate" }, "keys": "ctrl+alt+plus" },
    { "command": { "action": "splitPane", "split": "horizontal", "splitMode": "duplicate" }, "keys": "ctrl+alt+shift+plus" },
    { "command": { "action": "splitPane", "split": "vertical" }, "keys": "alt+plus" },
    { "command": { "action": "splitPane", "split": "horizontal" }, "keys": "alt+shift+plus" },
    
    // Copy and paste are bound to Ctrl+Shift+C and Ctrl+Shift+V in your defaults.json.
    // These two lines additionally bind them to Ctrl+C and Ctrl+V.
    // To learn more about selection, visit https://aka.ms/terminal-selection
    { "command": {"action": "copy", "singleLine": false }, "keys": "ctrl+c" },
    { "command": {"action": "copy", "singleLine": false }, "keys": "ctrl+insert" },
    { "command": "paste", "keys": "ctrl+v" },
    { "command": "paste", "keys": "shift+insert" },

    // { "command": "scrollUp", "keys": "ctrl+shift+up" },
    { "command": "scrollUp", "keys": "ctrl+up" },
    // { "command": "scrollDown", "keys": "ctrl+shift+down" },
    { "command": "scrollDown", "keys": "ctrl+down" },
    // { "command": "scrollUpPage", "keys": "ctrl+shift+pgup" },
    { "command": "scrollUpPage", "keys": "pgup" },
    // { "command": "scrollDownPage", "keys": "ctrl+shift+pgdn" },
    { "command": "scrollDownPage", "keys": "pgdn" },

    { "command": { "action": "adjustFontSize", "delta": 1 }, "keys": "ctrl+=" },
    { "command": { "action": "adjustFontSize", "delta": -1 }, "keys": "ctrl+-" },
    { "command": "resetFontSize", "keys": "ctrl+0" },

    { "command": "toggleRetroEffect", "keys": ""},
    { "command": { "action": "setColorScheme", "colorScheme": "Campbell" }, "keys": "" },
    { "command": "commandPalette", "keys": "ctrl+shift+p" },
    { "command": "commandPalette", "keys": "f1" },
]
}
```