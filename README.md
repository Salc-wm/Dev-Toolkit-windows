<p align="center">
    <h1 align="center">Dev $${\color{lightgreen}Toolkit}$$ windows</h1>
    <p align="center">Programs, Tools and Modifications, Plugins for a better Windows for devs.</p>
</p>


# [![My Skills](https://skillicons.dev/icons?i=windows&theme=dark)](https://skillicons.dev) Windows 11
Essential programs to improve the _appearance_ and usability of Windows

That make it easier to modify the default appearance of\
*Windows 11/10* and can improve quality or performance

- → Notepads app
	- _A clean and up-to-date notepad for windows_

> [!IMPORTANT]  
> If you are using any different Windows/Modified assignment, be careful when using Rectify11 and AtlasOS, which can break the system, so make restore points before installing them.
> preferably for the original version of Windows to avoid problems if you want to use them...

- → [`AtlasOS`](https://atlasos.net/)
	- _"A modification of Windows, designed for enthusiasts" It's time for a new Windows experience. Designed for enthusiasts and gamers, Atlas improves privacy, usability, and performance_
- → [`Rectify11`](https://rectify11.net/home)
	- _"ultimate Windows 11 customization tool" A good way to clean Windows, and leave it clean and truly usable_

- → [`Start11`](https://www.stardock.com/products/start11/)
	- _An amazing menu replacement platform_

- → [**`Windhawk`**](https://windhawk.net/)
	- _An essential windows customizer for many occasions_
 	- Mods:
  	    - Better file sizes in Explorer details
	    - Taskbar Clock Customization
	    - Windows 11 Start Menu Styler
	    - Windows 11 Taskbar Styler

- → [**`Komorebi`**](https://github.com/LGUG2Z/komorebi)
	- _A sensational tiling window manager for Windows_
	- Settings →: [**JSON FULL FILES**](https://github.com/Salc-wm/--komorebi.Config)

*komorebi*
```json
  "theme": {
    "palette": "Catppuccin",
    "name": "Mocha",
    "unfocused_border": "Crust",
    "bar_accent": "Blue"
  },
```

*komorebi.bar*
```json
  "monitor": {
    "index": 0,
    "work_area_offset": {
      "left": -15,
      "top": 8,
      "right": -30,
      "bottom": -5
    }
  },
  "theme": {
    "palette": "Catppuccin",
    "name": "Mocha",
    "accent": "Crust"
  },
  "viewport": {
    "inner_size": {
      // You size monitor
      "x": 1920, 

      // 20 is the default value for the height; if you want to increase the height you can try
      // doubling the y value as a starting point and then iterating from there
      "y": 23,
    }
  },
```


## OS - Windows 10/11
For those who know what they are doing, and know how to navigate the web, or just buy and use legal products\
Windows systems that bring high performance and low latency, varying in what each one performs best.

> [!WARNING]  
> Be careful when using these systems, if you don't know what you are doing or have no knowledge, avoid it, so as not to have problems or big losses.

- [**FoxOS**](https://discord.com/invite/4Gg8n6WhPN)
	- _A very lightweight system, with a strong focus on low latency, without losing out in terms of performance to other modifications_

- [**SapphireOS**](https://x.com/sapphire0s)
	- _With a very low number of processes, with the best latency time between modifications but it remains average to high in terms of gaming performance_

- **FSOS**
	-  _One of the best for general use, doing everything very well, low latency, high fps, not the best but very good, in addition to other incredible features_

- [**Windows X Lite**](https://windowsxlite.com/)
	- _For those who want something that doesn't change the standard version of Windows too much, and if you are concerned about security, this is a good option_

- [**xOS 11**](https://discord.com/invite/XTYEjZNPgX)
	- _They say this is one of the best modifications for games, it performs very well in all aspects, bringing good fps and low latency_


# [![My Skills](https://skillicons.dev/icons?i=devto&theme=dark)](https://skillicons.dev) Terminal

- → [`Git`](https://git-scm.com/downloads)

Use your favorite management software to install the below software like\
_[Chocolatey](https://community.chocolatey.org/packages), [Scoop](https://scoop.sh/), etc_

→ [**Uv**](https://docs.astral.sh/uv/getting-started/installation/)
> ```Bash
> powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

→ [**fzf**](https://github.com/fuzzy-finder/fzf)
> ```bash
> winget install fzf

→ [**Curl**](https://curl.se/download.html)
> ```bash
> winget install cURL.cURL

→ [**Zoxide**](https://github.com/ajeetdsouza/zoxide)
> ```bash
> winget install ajeetdsouza.zoxide

→ [**Oh My Posh**](https://ohmyposh.dev/)
	- Theme: emodipt-extend
> ```bash
> winget install JanDeDobbeleer.OhMyPosh -s winget

→ [**Posting CLI**](https://posting.sh/guide/)
> ```bash
> # install Posting (will also quickly install Python 3.12 if needed)
> uv tool install --python 3.12 posting
> 
> # install Posting (will also quickly install Python 3.13 if needed)
> uv tool install --python 3.13 posting --prerelease=allow

- → [**Powershell Core**](https://github.com/PowerShell/PowerShell)
	- : [_Setup File_ **| - :** _Config File_](https://github.com/Salc-wm/Powershell-WindowsProfile)

- → [**Kanata**](https://github.com/jtroo/kanata?tab=readme-ov-file)
	- _Cross-platform software keyboard remapper for Linux, macOS and Windows_
 	- - **Main** configurates here -> [**MODS KEYSWORDS**](https://github.com/dreamsofcode-io/home-row-mods)
    - _To facilitate faster coding, as well as maintaining hand health_

→ [**Yazi**](https://yazi-rs.github.io/)
	- _Fast terminal file manager written in Rust_

- ### Windows
Yazi relies on file(1) to detect the mime-type of the file, and the easiest and most reliable way to get it on Windows is to install Git for Windows and use the file.exe that comes with it.
```txt
    Install Git for Windows by running the official installer, or through your package manager of choice.
    To allow Yazi to use file(1), add <Git_Installed_Directory>\usr\bin\file.exe to your YAZI_FILE_ONE environment variable, which differs depending on how you installed Git:
        If you installed Git with the installer, it would be C:\Program Files\Git\usr\bin\file.exe.
        If you installed Git with Scoop, it would be C:\Users\<Username>\scoop\apps\git\current\usr\bin\file.exe.
    Restart your terminal.
```


<p align="center"><h1 align="center">Editors</h1></p>

## [![My Skills](https://skillicons.dev/icons?i=neovim&theme=light)](https://skillicons.dev) **Vim | Nvim**
- [Lazy](https://lazy.folke.io/)
	Distro Vim\
	 → [**mini.nvim**](https://github.com/echasnovski/mini.nvim)\
  	 → [**Nightfox**](https://github.com/EdenEast/nightfox.nvim) -< `Theme=Carbonfox`

## [**Wez's**](https://wezterm.org/)
"WezTerm is a powerful cross-platform terminal emulator and multiplexer"\
A very useful and automatically modifiable terminal, along with its ease and capability of configuration thanks to its Lua API

> [!IMPORTANT]  
> The _wezterm_ folder needs to go in the *.config* folder.
→ Config [**file Code**](https://github.com/Salc-wm/Dev-Toolkit-windows/blob/main/wezterm/wezterm.lua)

- Rename the wezterm file to __.wezterm__ or add it to your own
- located at _($HOME/.wezterm.lua)_ or _(Users\ \<USER NAME>)_

## [![My Skills](https://skillicons.dev/icons?i=vscode&theme=light)](https://skillicons.dev) [**VS-Code**](https://code.visualstudio.com/download)
| …                         | Extensões            |
| ------------------------- | -------------------- |
| ESLint                    | Stylelint            |
| Better Comments           | Even Better TOML     |
| Markdown All in One       | Material Theme Icons |
| Prettier - Code formatter | Code Runner          |
| Subtle Match Brackets     | TODO Highlight       |
| Custom CSS and JS Loader  | Custom UI Style      |

- → *Custom CSS and JS Loader:*
	- CSS → File Code
	- JS  → File Code

## [**Rio**](https://rioterm.com/)
Rio is a Brazilian terminal, simple and fast, in addition to an easy configuration,\
made in rust, it brings great performance to accompany Vim/Nvim

### Configs
- Theme -> [_Code Theme_](https://github.com/Salc-wm/Dev-Toolkit-windows/blob/main/rio/themes/darkMeRio-Slim.toml)
	- **[DarkMeRio](https://github.com/Salc-wm/rio-DarkMe-Terminal/blob/main/README.md)**
- Config -> [_Toml Code_](https://github.com/Salc-wm/Dev-Toolkit-windows/blob/main/rio/config.toml)
  	```toml
  confirm-before-quit = false
  hide-cursor-when-typing = true
  # ignore-selection-foreground-color = false

  theme = "darkMeRio-Slim"

  # Padding-x
  padding-x = 20
  padding-y = [0, 10]

  # Line height
  line-height = 1.4

  # Startup directory
  working-dir = "/Users/<USER>/<YOU HOME>"

  [cursor]
      shape = 'Beam'
      blinking = false
      blinking-interval = 800

  [editor]
      program = "nvim"
  # args = []

  [window]
      blur = false
      opacity = 1.0
      mode = "Fullscreen"
      decorations = "Disabled"

  [renderer]
      level = 1
      target-fps = 165
      backend = "Vulkan"
      performance = "high"
      disable-unfocused-render = false
  # filters = []

  [fonts]
      size = 18

  [scroll]
      multiplier = 3.0
      divider = 1.0

  [navigation]
      mode = "BottomTab"
      clickable = false
      hide-if-single = true
      use-current-path = false
  # color-automation = []

  [platform]
  windows.shell.program = "pwsh"
  windows.shell.args = ["-l", "-NoLogo"]

<p align="center"> <h1 align="center">Discord</h1> </p>

### **[Vencord](https://vencord.dev/)**

| …… Plugins       | ……           |
| ---------------- | ------------ |
| MessageTags      | OnePingPerDM |
| FixSpotifyEmbeds | SpotifyCrack |
| SpotifyControls  | Experiments  |
| ValidUser        | FakeNitro    |
| MessageLogger    | PinDMs       |
| ImageZoom        | Translate    |

### Themes
- → [Discord Mica](https://betterdiscord.app/theme/Discord%20Mica)
- → [System24](https://betterdiscord.app/theme/system24)
- → [SurCord](https://betterdiscord.app/theme/surCord)
- → [AMOLED-Cord](https://betterdiscord.app/theme/AMOLED-Cord)
- → [SettingsModal](https://betterdiscord.app/theme/SettingsModal)


<p align="center"><h1 align="center">Steam</h1></p>

### **[Millennium](https://steambrew.app/themes)**

- **USE**:→
	- Theme → [Minimal Dark](https://steambrew.app/theme?id=F4XgbtTW4x5CJmi5DUK3)
	- Plugin  → [SteamDB](https://steambrew.app/plugin?id=c36d5f67c99f)

[![My Skills](https://skillicons.dev/icons?i=steam&theme=light)](https://skillicons.dev)

<p align="center"><h1 align="center">Apps Notes</h1></p>

## [![My Skills](https://skillicons.dev/icons?i=notion&theme=light)](https://skillicons.dev) Notion
All-in-one productivity tool that combines note-taking, task management, wikis, databases, and collaboration features into a single workspace.

## [![My Skills](https://skillicons.dev/icons?i=obsidian&theme=light)](https://skillicons.dev) Obsidian
Markdown-based note-taking app that stands out for its "second brain" approach and ability to connect information.

| **Plugins**     |                 |
| --------------- | --------------- |
| Iconize         | Excalidraw      |
| Style Settings  | Text Format     |
| Advanced Slides | Smart Typograph |

## [![My Skills](https://skillicons.dev/icons?i=linear&theme=light)](https://skillicons.dev) Linear
Modern project management and issue tracking tool designed specifically for software and product development teams.

<p align="center"><h1 align="center">Youtube</h1></p>

## **Plugins**
- → Stands
- → Tweaks for YouTube
- → Screenshot YouTube

### *Tweaks for YouTube*
Choose or use as a base to create your own theme to customize the YouTube theme and make it as pleasant and modern as possible.

1. __Original Themes__: By
    - [LawOff](https://github.com/LawOff/YouTubeFluent)
    - [RikisuT](https://github.com/RikisuT/Youtube-Fluent-Theme)
    - [jean0t](https://github.com/jean0t/customize-youtube)
