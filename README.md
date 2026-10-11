# Cool Wallpapers

## About
This repository is a collection of high-quality wallpapers grouped by color palette and theme: TokyoNight, Catppuccin, Everforest, Harbor Dark, COSMIC and a set of Omarchy community themes, plus one folder per Pop!_OS COSMIC rice with wallpapers recoloured to that rice's palette.

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
- `cosmic/` - the gray COSMIC astronaut, plus one folder per COSMIC rice (`cosmic/<rice>/`) holding that rice's recolours, named `<rice>-<subject>-<width>x<height>`. Where a small JPEG sits next to a PNG, the JPEG is the render the PNG was upscaled from
- `everforest/` - wallpapers in the Everforest palette, from [Apeiros-46B/everforest-walls](https://github.com/Apeiros-46B/everforest-walls) (archived)
- `harbor-dark/` - wallpapers in the Harbor Dark palette. `shuttle-launch`, `hyundai-n-vision-blueprint`, `reaper-skull` and `space-monolith` come from the [Harbor Dark Omarchy theme](https://github.com/HANCORE-linux/omarchy-harbordark-theme) (MIT)
- `omarchy/` - wallpapers from Omarchy community themes, one folder per theme, plus an index of all community theme repos

Files are named `<subject>-<width>x<height>.<ext>`. Higher resolutions of the same subject are AI upscales of the smallest one. Recolours in `cosmic/<rice>/` are made two ways: with ImageMagick (background and line art flattened to the rice's colours, each coloured region remapped onto a palette colour with its shading kept), or with an image model given the palette as hex values, then upscaled with Upscayl and resized to 3840 wide. Subjects come from elsewhere in this repo: the COSMIC astronaut, the Harbor Dark reaper and Hyundai blueprint, the Tokyo Night samurai and sushi, the Omarchy The Greek ink drawings.

## Features
- High-resolution images suitable for various screen sizes.
- A variety of themes capturing the TokyoNight, Catppuccin, Everforest, Harbor Dark and Omarchy palettes.

## Related
Pop!_OS COSMIC rices that use these wallpapers:
Every rice has its own folder, `cosmic/<rice>/`.

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


