# Cool Wallpapers

## About
This repository is a collection of high-quality wallpapers grouped by color palette and theme: TokyoNight, Catppuccin, Everforest, a set of Omarchy community themes, and the recolours for the light Pop!_OS COSMIC rices. The dark rices ship their own wallpapers in their theme repo instead.

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
- `cosmic/` - one folder per light COSMIC rice (`cosmic/dossier/`, `cosmic/whitegold/`) holding that rice's recolours, named `<rice>-<subject>-<width>x<height>`. Where a small JPEG sits next to a PNG, the JPEG is the render the PNG was upscaled from. The dark rices (DarkGold, TokyoNight, Monochrome, Noir) keep theirs in `backgrounds/` of their own repo, see Related
- `everforest/` - wallpapers in the Everforest palette, from [Apeiros-46B/everforest-walls](https://github.com/Apeiros-46B/everforest-walls) (archived)
- `omarchy/` - wallpapers from Omarchy community themes, one folder per theme, plus an index of all community theme repos

Files are named `<subject>-<width>x<height>.<ext>`. Higher resolutions of the same subject are AI upscales of the smallest one. Recolours in `cosmic/<rice>/` are made two ways: with ImageMagick (background and line art flattened to the rice's colours, each coloured region remapped onto a palette colour with its shading kept), or with an image model given the palette as hex values, then upscaled with Upscayl and resized to 3840 wide. Subjects come from the Tokyo Night samurai and sushi in `tokyonight/`, the Omarchy The Greek ink drawings in `omarchy/the-greek/`, and the Harbor Dark reaper and Hyundai blueprint, which now live in [cosmic-darkgold-theme](https://github.com/atraxsrc/cosmic-darkgold-theme/tree/main/backgrounds).

## Features
- High-resolution images suitable for various screen sizes.
- A variety of themes capturing the TokyoNight, Catppuccin, Everforest and Omarchy palettes.

## Related
Pop!_OS COSMIC rices. The two light rices keep their recolours here in
`cosmic/<rice>/`; the four dark rices ship theirs in `backgrounds/` of their own repo,
named `<rice>-<subject>.png`.

| Rice | Palette | Wallpapers |
|------|---------|------------|
| [cosmic-darkgold-theme](https://github.com/atraxsrc/cosmic-darkgold-theme) | charcoal and gold | its `backgrounds/`, with the Harbor Dark originals |
| [cosmic-whitegold-theme](https://github.com/atraxsrc/cosmic-whitegold-theme) | parchment and dark gold, light sibling of DarkGold | `cosmic/whitegold/`, `omarchy/white-gold/` |
| [cosmic-tokyonight-theme](https://github.com/atraxsrc/cosmic-tokyonight-theme) | Tokyo Night | its `backgrounds/`, plus `tokyonight/` here |
| [cosmic-monochrome-theme](https://github.com/atraxsrc/cosmic-monochrome-theme) | gray, no hue | its `backgrounds/` |
| [cosmic-noir-theme](https://github.com/atraxsrc/cosmic-noir-theme) | charcoal, sage and orange | its `backgrounds/`, plus `omarchy/greek-noir/` here |
| [cosmic-dossier-theme](https://github.com/atraxsrc/cosmic-dossier-theme) | stone grey, olive and rust, light half of Noir | `cosmic/dossier/`, `omarchy/the-greek/` |

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**. 


