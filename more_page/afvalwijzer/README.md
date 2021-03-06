# Afvalwijzer Add-on (more_page)
##### Created by Jeroen Klompen


### Installation
- Install [Afvalbeheer](https://github.com/pippyn/Home-Assistant-Sensor-Afvalbeheer) from [HACS](https://hacs.xyz).
- Copy the file `page.yaml`  to your `<config dir>/dwains-theme/addons/more_page/afvalbeheer` directory.
- Configure your `more_page.yaml` file in `<config dir>/dwains-theme/configs` with config below.
- Download the [images ZIP file](https://github.com/Klumpke/dwains-theme-addons/blob/master/more_page/afvalwijzer/.github/afvalwijzer-images.zip) and extract it into your `<config dir>/www/images`  directory.
- Restart Home Assistant.


### Usage
To use this add-on in your Dwains Theme, add the following to your `more_page.yaml` file:

```yaml
# Example more_page.yaml entry
more_page:
    addons:
      - name: Afvalwijzer
        icon: fas:recycle
        path: 'dwains-theme/addons/more_page/afvalwijzer/page.yaml'
```

### Screenshots
**Light theme:**<br>
![light](https://github.com/Klumpke/dwains-theme-addons/blob/master/more_page/afvalwijzer/.github/screenshots/light.png "Light")

**Dark theme:**<br>
![dark](https://github.com/Klumpke/dwains-theme-addons/blob/master/more_page/afvalwijzer/.github/screenshots/dark.png "Dark")


### Changelog
#### 1.0.1
- Added unknown image state
#### 1.0.0
- First release

---

If you like my work please feel free to buy me a coffee

<a href="https://www.buymeacoffee.com/klumpke" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/white_img.png" alt="Buy Me A Coffee"></a>

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=T6QQWUABDP65G&source=url"><img src="https://www.paypalobjects.com/en_US/NL/i/btn/btn_donateCC_LG.gif" alt="Donate with PayPal"></a>