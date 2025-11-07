# dieter
A Dieter Rams inspired Home Assistant Theme

<a href="https://buymeacoffee.com/strhwste" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

## Screenshots

### Homescreen

#### Light Theme
![Theme - HomeScreen](https://raw.githubusercontent.com/strhwste/dieter/docs/Dashboard-Light.png)

#### Dark Theme
![Theme - HomeScreen](https://raw.githubusercontent.com/strhwste/dieter/docs/Dashboard-dark.png)


## Installation

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. Go to the Community Store.
3. Search for `Dieter`.
4. Navigate to `Dieter` theme.
5. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.