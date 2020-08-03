# Google Dark Theme

A Home Assistant theme inspired on Google app dark mode.
<br />
<br />

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)


[![Subscribe to YouTube channel][youtube-sub-shield]][youtubesubscribe]

[![Become a Patron][become-a-patron-shield]][becomeapatron]

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]
<br />
<br />

### Screenshots

![Google Dark Mode 1](https://raw.githubusercontent.com/JuanMTech/google_dark_theme/master/images/Google%20Dark%20Mode%201.jpg)<br />
<br />
![Google Dark Mode 2](https://raw.githubusercontent.com/JuanMTech/google_dark_theme/master/images/Google%20Dark%20Mode%202.jpg)<br />
<br />
![Google Dark Mode 3](https://raw.githubusercontent.com/JuanMTech/google_dark_theme/master/images/Google%20Dark%20Mode%203.jpg)<br />
<br />

### Preparation
1. Make sure that under the **configuration.yaml** file you have the following:

```
frontend:
  themes: !include_dir_merge_named themes
```

2. Under the Home Assistant **Config** folder, create a new folder named **themes**
3. **Restart** Home assistant to apply the changes. 

### HACS installation
1. Go into the Community Store (HACS)
2. Search for Google Dark Theme
3. Open the theme
4. Press Install
5. Restart Home Assistant

### Manual installation
1. In the Home assistant **themes** folder, create a file named `google_dark_theme.yaml`
2. In this GitHub repo, go into the **themes** folder, open the `google_dark_theme.yaml` file and copy the content
3. Paste the content in the `google_dark_theme.yaml` file created under your Home Assistant themes folder

### Enable theme
1. Open your Home Assistant **Profile**
2. Under, **Themes**, select the new Google Dark Theme


### Custom Header settings
When using the [Custom Header](https://github.com/maykar/custom-header) plugin, add the following to make sure that the header matches the theme.

```
custom_header:
  compact_mode: true
  background: var(--app-header-background-color)
  elements_color: var(--app-header-text-color)
  active_tab_color: var(--state-icon-active-color)
  tab_indicator_color: var(--state-icon-active-color)
```



[buymeacoffee-shield]: https://i.imgur.com/Hzn2rM8.png
[buymeacoffee]: https://www.buymeacoffee.com/JuanMTech
[become-a-patron-shield]: https://i.imgur.com/U9BjCfc.png
[becomeapatron]: https://www.patreon.com/JuanMTech
[youtube-sub-shield]: https://i.imgur.com/6TAqHgi.png
[youtubesubscribe]: https://www.youtube.com/c/JuanMTech?sub_confirmation=1
