# Google Dark Theme
A Home Assistant theme inspired on Google app dark mode.

<p align="center">
  <img src="https://i.imgur.com/eelK3dj.png">
</p>

### Preparation
1. Make sure that under the **configuration.yaml** file you have the following:

<pre>
frontend:
  themes: !include_dir_merge_named ../themes
</pre>

2. Under the Home Assistant **Config** folder, create a new folder named **themes**
3. **Restart** Home assistant to apply the changes. 

### Manual installation
1. In the Home assistant **themes** folder, create a file named `google_dark_theme.yaml`
2. In this GitHub repo, go into the **themes** folder, open the `google_dark_theme.yaml` file and copy the content
3. Paste the content in the `google_dark_theme.yaml` file created under your Home Assistant themes folder

### HACS installation
1. Go into the Community Store (HACS)
2. Search for Google Dark Theme
3. Open the theme
4. Press Install
5. Restart Home Assistant

### Enable theme
1. Open your Home Assistant Profile
2. Under, Themes, select the new Google Dark Theme


### Custom Header settings
When using the [Custom Header](https://github.com/maykar/custom-header) plugin, add the following to make sure that the header matches the theme.

<pre>
custom_header:
  compact_mode: true
  background: var(--app-header-background-color)
  elements_color: var(--app-header-text-color)
  active_tab_color: var(--state-icon-active-color)
  tab_indicator_color: var(--state-icon-active-color)
</pre>
