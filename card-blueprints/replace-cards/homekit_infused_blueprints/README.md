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

After you did all that you can add templates in your custom button card in Dwains Dashboard.
<br> You can also use the replace cards. Screenshots and Code Examples are shown below.


### Installation: 
  
1.  Go into Edit Mode
2.  Click Add Card
3.  Use Dwains Dashboard Blueprint
4.  Add YAML Code from file to HA
5.  Click install Blueprint

### Examples

## Homekit Light Hue

![image](https://user-images.githubusercontent.com/64064679/169295749-fa14e0be-6150-4f83-b274-8415285f57fa.png)
![image](https://user-images.githubusercontent.com/64064679/169296212-dec38c21-d0c4-4672-a2ca-45f500f3bebe.png)

````
entity: light.light
template:
  - light
  - icon_hue
type: custom:button-card
````
## Homekit Conditional Media

![image](https://user-images.githubusercontent.com/64064679/169297548-93ab71c2-8e69-4ae9-9d0e-c07456a30450.png)
![image](https://user-images.githubusercontent.com/64064679/169297971-2da85817-a035-4e1d-af44-8eb528737e25.png)

````
entity: media_player.media
template:
  - conditional_media
  - icon_monitors
type: custom:button-card
````

<details>
<summary> Click here to show more Examples </summary>


## Homekit Light Lamp

![image](https://user-images.githubusercontent.com/64064679/169295904-fdf45aa6-cd7d-4b2c-ac21-d38451025448.png)
![image](https://user-images.githubusercontent.com/64064679/169296120-3e38de47-6cbc-423b-911c-f6e97b1566c2.png)

````
entity: light.light
template:
  - light
  - icon_lamp
type: custom:button-card
````

## Homekit Light Spot

![image](https://user-images.githubusercontent.com/64064679/169295851-7ce62c8d-bdd5-487f-be82-bfb058202579.png)
![image](https://user-images.githubusercontent.com/64064679/169296065-36427428-45e4-43dc-be55-5650b83d8d28.png)

````
entity: light.light
template:
  - light
  - icon_spot
type: custom:button-card
````

## Homekit Light Shade

![image](https://user-images.githubusercontent.com/64064679/169295802-ad1364df-c8a1-4000-928a-4700c875a7e7.png)
![image](https://user-images.githubusercontent.com/64064679/169296027-8e893f79-4719-464d-a0bd-94a278d01c5e.png)

````
entity: light.light
template:
  - light
  - icon_shade
type: custom:button-card
````


## Homekit Media Spotify

![image](https://user-images.githubusercontent.com/64064679/169297588-548106ee-9db2-4196-a6b6-213c04ae0f7b.png)
![image](https://user-images.githubusercontent.com/64064679/169298018-8153da68-80ba-48ec-8bc6-582c5a513e5f.png)

````
entity: media_player.media
template:
  - media
  - icon_spotify
type: custom:button-card
````

## Homekit Media Monitors

![image](https://user-images.githubusercontent.com/64064679/169297643-ac5a803f-5b15-480d-830d-97090baf867b.png)
![image](https://user-images.githubusercontent.com/64064679/169298066-8e78da8f-65a1-42c0-b41e-5c278b4509a0.png)


````
entity: media_player.media
template:
  - media
  - icon_monitors
type: custom:button-card
````

## Homekit Climate

![image](https://user-images.githubusercontent.com/64064679/169300586-41834cb6-9e03-44c1-8703-c1fae44269ad.png)
![image](https://user-images.githubusercontent.com/64064679/169300698-6bd0f20c-dd65-4603-a8b2-cff44905e309.png)


````
entity: climate.climate
template:
  - climate
type: custom:button-card
````

## Homekit Climate HVAC

![image](https://user-images.githubusercontent.com/64064679/169300865-ef04a9f6-2fec-4f1f-adf5-d5236d8c4e5e.png)
![image](https://user-images.githubusercontent.com/64064679/169300923-f5af75bd-18f8-4ce4-9cb6-e8d7864af2cc.png)


````
entity: climate.climate
template:
  - climate_hvac
type: custom:button-card
````

## Homekit Person

![image](https://user-images.githubusercontent.com/64064679/169302785-7bc27ab8-db2c-4f32-b6f4-09bddbe127ba.png)
![image](https://user-images.githubusercontent.com/64064679/169303222-84ff3e7d-a6cc-44cd-87e6-5dd3951c3c5e.png)

````
entity: person.person
template:
  - person
type: custom:button-card
````
## Homekit Plex Icon

![image](https://user-images.githubusercontent.com/64064679/169303632-c0ad6ac8-2f04-4e52-ab38-28a16cd052d5.png)
![image](https://user-images.githubusercontent.com/64064679/169303717-74071e93-d5a7-4fd1-95c8-258db32cbc38.png)

````
entity: entity.entity
template:
  - base
  - icon_plex
type: custom:button-card
````
## Homekit Apple TV Icon

![image](https://user-images.githubusercontent.com/64064679/169305069-08d07872-6c21-4f40-a9b3-c8e4eebab4c9.png)
![image](https://user-images.githubusercontent.com/64064679/169305707-83c6269e-191e-4951-a482-87ab1488d47a.png)

````
entity: entity.entity
template:
  - base
  - icon_apple_tv
type: custom:button-card
````

## Homekit TV Icon

![image](https://user-images.githubusercontent.com/64064679/169305120-b1d106ac-c501-4108-b348-c4f1e66c6649.png)
![image](https://user-images.githubusercontent.com/64064679/169305750-a35283f6-51dd-4e83-ba5f-cb02915b1a60.png)

````
entity: entity.entity
template:
  - base
  - icon_tv
type: custom:button-card
````

## Homekit Nest Mini Icon

![image](https://user-images.githubusercontent.com/64064679/169305153-49d9026b-68d6-436f-b223-8ee255cde034.png)
![image](https://user-images.githubusercontent.com/64064679/169305785-7f187436-6f77-4973-bde6-112f8e9d4d2d.png)

````
entity: entity.entity
template:
  - base
  - icon_nest_mini
type: custom:button-card
````

## Homekit Playstation Icon

![image](https://user-images.githubusercontent.com/64064679/169305203-df2aabbb-ed78-44a1-a0c8-835f05ef969e.png)
![image](https://user-images.githubusercontent.com/64064679/169305814-24baebc6-90a7-4371-949c-f64746d28e22.png)

````
entity: entity.entity
template:
  - base
  - icon_ps5
type: custom:button-card
````
## Homekit Mac Icon

![image](https://user-images.githubusercontent.com/64064679/169305263-34e86c9e-386d-4312-9696-0645e98d2803.png)
![image](https://user-images.githubusercontent.com/64064679/169305849-ef9da26c-5c69-4d8f-9954-1d8bfabbd833.png)

````
entity: entity.entity
template:
  - base
  - icon_imac
type: custom:button-card
````

## Homekit Climate Icon

![image](https://user-images.githubusercontent.com/64064679/169305319-f3a8922b-0323-4cea-83f5-0dc0506deef0.png)
![image](https://user-images.githubusercontent.com/64064679/169305900-77306f06-d3d9-45ff-aa93-fc617c45f54d.png)

````
entity: entity.entity
template:
  - base
  - icon_climate
type: custom:button-card
````
## Homekit Fan Icon

![image](https://user-images.githubusercontent.com/64064679/169305364-5a4ab8fc-fee7-476f-bc5f-b698ffaaba1d.png)
![image](https://user-images.githubusercontent.com/64064679/169305938-5c8a9160-2239-4888-b88b-c43877b84a57.png)

````
entity: entity.entity
template:
  - base
  - icon_fan
type: custom:button-card
````

## Homekit Bathroom Icon

![image](https://user-images.githubusercontent.com/64064679/169305419-fdf93706-693b-44eb-b56b-7df8019bdaaa.png)
![image](https://user-images.githubusercontent.com/64064679/169305990-e9751159-6573-491e-93da-48d7ffb47a32.png)

````
entity: entity.entity
template:
  - base
  - icon_bathroom
type: custom:button-card
````
## Homekit Closet Icon

![image](https://user-images.githubusercontent.com/64064679/169305472-2af2e856-ed6f-4e20-8ee8-e9a35eca9583.png)
![image](https://user-images.githubusercontent.com/64064679/169306032-8c8628e1-5abd-40d5-aae2-7627d22256dc.png)

````
entity: entity.entity
template:
  - base
  - icon_closet
type: custom:button-card
````

## Homekit Away Icon

![image](https://user-images.githubusercontent.com/64064679/169307655-f0286012-fb70-4ef7-8e75-46f591490ee1.png)
![image](https://user-images.githubusercontent.com/64064679/169307545-0a64cca9-3e9c-4144-9226-f794cc174056.png)

````
entity: entity.entity
template:
  - base
  - icon_away
type: custom:button-card
````

## Homekit Home Icon

![image](https://user-images.githubusercontent.com/64064679/169307693-5a19dd25-0b61-4784-a005-8ae624e4075b.png)
![image](https://user-images.githubusercontent.com/64064679/169307582-ea6a84a3-18e4-42a9-85cd-341197cce1bf.png)

````
entity: entity.entity
template:
  - base
  - icon_home
type: custom:button-card
````

</details>



### Links:
* https://github.com/dwainscheeren/dwains-dashboard-blueprints
* https://www.home-assistant.io/

---


### Changelog
#### 1.0.0
- First release
