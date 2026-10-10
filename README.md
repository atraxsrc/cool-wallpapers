# Cool Wallpapers

## About
This repository is a collection of high-quality wallpapers grouped by color palette and theme: TokyoNight, Catppuccin, Everforest, Harbor Dark, COSMIC and a set of Omarchy community themes, plus one astronaut and one reaper recoloured for each of the Pop!_OS COSMIC rices listed under Related.

## Installation and Usage
To use these wallpapers:
1. Clone the repository:
   ```sh
   git clone https://github.com/atraxsrc/cool-wallpapers.git
   ```
2. Choose your favorite wallpaper and set it as your background through your operating system's preference settings.

## Structure
- `tokyonight/` - wallpapers in the TokyoNight palette
- `catppuccin/` - wallpapers in the Catppuccin palette
- `cosmic/` - COSMIC desktop (and Pop!_OS) branded wallpapers. `cosmic-astronaut-<rice>-3840x2160.png` is the same astronaut recoloured for each of the COSMIC rices below; the untouched originals are `cosmic-astronaut-smooth` (dark) and `cosmic-astronaut-gray-standard` (light)
- `everforest/` - wallpapers in the Everforest palette, from [Apeiros-46B/everforest-walls](https://github.com/Apeiros-46B/everforest-walls) (archived)
- `harbor-dark/` - wallpapers in the Harbor Dark palette. `shuttle-launch`, `hyundai-n-vision-blueprint`, `reaper-skull` and `space-monolith` come from the [Harbor Dark Omarchy theme](https://github.com/HANCORE-linux/omarchy-harbordark-theme) (MIT)
- `omarchy/` - wallpapers from Omarchy community themes, one folder per theme, plus an index of all community theme repos
- `reaper/` - the Harbor Dark reaper (`harbor-dark/reaper-skull-digital-art`) recoloured for each COSMIC rice, `reaper-skull-<rice>-3440x1440.png`

Files are named `<subject>-<width>x<height>.<ext>`. Higher resolutions of the same subject are AI upscales of the smallest one. Recolours are named `<subject>-<rice>-<width>x<height>` and are made from the originals with ImageMagick: background and line art flattened to the rice's background and text colours, each coloured region remapped onto a palette colour with its shading kept.

## Features
- High-resolution images suitable for various screen sizes.
- A variety of themes capturing the TokyoNight, Catppuccin, Everforest, Harbor Dark and Omarchy palettes.

## Related
Pop!_OS COSMIC rices that use these wallpapers:
Every rice has its own astronaut and reaper: `cosmic/cosmic-astronaut-<rice>-3840x2160.png` and `reaper/reaper-skull-<rice>-3440x1440.png`.

| Rice | Palette | Also uses |
|------|---------|-----------|
| [cosmic-darkgold-theme](https://github.com/atraxsrc/cosmic-darkgold-theme) | charcoal and gold | `harbor-dark/` |
| [cosmic-whitegold-theme](https://github.com/atraxsrc/cosmic-whitegold-theme) | parchment and dark gold, light sibling of DarkGold | `omarchy/white-gold/` |
| [cosmic-tokyonight-theme](https://github.com/atraxsrc/cosmic-tokyonight-theme) | Tokyo Night | `tokyonight/` |
| [cosmic-monochrome-theme](https://github.com/atraxsrc/cosmic-monochrome-theme) | gray, no hue | |
| [cosmic-noir-theme](https://github.com/atraxsrc/cosmic-noir-theme) | charcoal, sage and orange | `omarchy/greek-noir/` |
| [cosmic-dossier-theme](https://github.com/atraxsrc/cosmic-dossier-theme) | stone grey, olive and rust, light half of Noir | `omarchy/the-greek/` |

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**. 


