## Dwains-Dashboardv3-Blueprints-Homekit-Style-Cards
## Replace Card for Dwains Dashboard v3
##### Created by Bourner
---


### HACS components

- Install [Button-Card](https://github.com/custom-cards/button-card) from [HACS](https://hacs.xyz).

### Configuration

To use the button card templates install the content from homekit_style_templates_blueprint.yaml as a blueprint in Dwains Dashboard.
<br>Copy loader.svg and vanilla-titl.js to your config/www/ folder.
<br>Add "/local/vanilla-tilt.js" as a ressource in HA if you want a tilt effect.
<br>Make sure to restart Home Assistant after you copied all files.

After you did all that you can add templates in your custom button card.
For tmeplates look in the folders above. Screenshots and examples will be there.

### Installation: 
  
1.  Go into Edit Mode
2.  Go to an alarm control panel entity you want to change or to the alarm control panel domain in the device tab
3.  Click on three dots and choose Entity Card
4.  Use Dwains Dashboard Blueprint
5.  Add YAML Code from file to HA
6.  Click install Blueprint
7.  Click Use this Blueprint


### Templates

Tested templates:

- base
- tilt
- extra_styles
- circle
- loader
- climate_hvac
- climate
- light
- person
- media
- conditional_media
- lock
- icon_plex
- icon_apple_tv
- icon_spotify
- icon_nest_mini
- icon_play_pause
- icon_hue
- icon-shade
- icon_tv
- icon_ps5
- icon_spot
- icon_imac
- icon_monitors
- icon_lamp
- icon_climate
- icon_bathroom
- icon_fan2
- icon_closet
- icon_awy
- icon_home

untesetd templates:
- base_media
- laundry
- icon_name
- icon_only


### Links:
* https://github.com/dwainscheeren/dwains-dashboard-blueprints
* https://www.home-assistant.io/

---


### Changelog
#### 1.0.0
- First release
