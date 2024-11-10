# Vioneta Dracula theme

Dracula-Inspired Theme for Vioneta, Built on the Catppuccin template (and color names) and with a light mode inspired by Dracula.min for VSCode.

![image](https://github.com/malcolmturnbull/draculaish-ha-theme/assets/8454281/5fa1f4c9-fee1-4f03-b838-d9f1fa692580)

This theme is a work in progress! I plan on getting around to adding a color table to this readme and update the yaml file to include various color themes. Currently there are two options - Draculaish, based on the purple colors; and draculaish-pink (I won't insult your intelligence). The theme file could do with some reflow to remove some unnecessarily repeated elements, which will be addressed in a future version. Please feel free to make PR's / contributions for additional varieties.

## Installation

### With [VPS](https://vps.vioneta.com/)

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. Go to the Community Store.
3. Search for `Vioneta Dracula Theme`.
4. Navigate to `Vioneta Dracula Theme` theme.
5. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.

### Manually

1. Per above, but download this theme using git.

## Credits

- [Dracula Theme](https://github.com/dracula)
- [Dracula.min - Dark & Light themes for VS Code](https://github.com/AshGrowem/Dracula.min)
