# Dark Material Theme for Sublime Text 3
This theme brings flat material similar visual language to your Sublime Text 3. If you have problems report them with an [issue](https://github.com/artifactdev/Theme-Dark-Material/issues).

## Screenshots

![image](http://equinusocio.github.io/material-theme/assets/materialtheme.png)

![image](http://equinusocio.github.io/material-theme/assets/materialtheme2.png)

![image](http://equinusocio.github.io/material-theme/assets/materialtheme3.png)

## Easy installation
You can install this awesome theme through the [Package Control](https://packagecontrol.io/installation). Search for *"Theme-DarkMaterial"*, install, **restart Sublime Text** and enjoy!

--

**Manual installation**

1. Download the [latest release](https://github.com/artifactdev/Theme-Dark-Material/releases/latest), extract and rename the folder to "Material Theme".

2. Move the folder inside your sublime Packages directory. (Preferences > Browse packages...)

3. Activate the theme with the following preferences:

```json
"theme": "Dark-Material.sublime-theme",
"color_scheme": "Packages/Theme-Dark-Material/schemes/Dark-Material.tmTheme",
```

***Note*** : Remember to restart Sublime Text after activating the theme.

## Recommended UI and font settings
I suggest you to use this custom settings for a better experience with the theme:

```json
"overlay_scroll_bars": "enabled",
"line_padding_top": 3,
"line_padding_bottom": 3,
"font_options": [ "gray_antialias" ], // On retina Mac
"always_show_minimap_viewport": true,
"bold_folder_labels": true
```

The font used for the code is "[Fira Code](https://github.com/tonsky/FiraCode)" with code ligatures (not supported in Sublime Text).

You can also use the official Material Design monospace font, "[Roboto Mono](https://www.google.com/fonts/specimen/Roboto+Mono)"
