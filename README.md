# dieter
A Dieter Rams inspired Home Assistant Theme

<a href="https://buymeacoffee.com/strhwste" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=Strhwste&repository=https%3A%2F%2Fgithub.com%2Fstrhwste%2Fdieter&category=Theme)

## Screenshots

### Homescreen

#### Light Theme
![Theme - HomeScreen](https://github.com/strhwste/dieter/blob/main/docs/Dashboard-Light.png?raw=true)

#### Dark Theme
![Theme - HomeScreen](https://github.com/strhwste/dieter/blob/main/docs/Dashboard-dark.png?raw=true)


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