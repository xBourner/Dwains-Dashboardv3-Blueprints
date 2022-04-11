[< Go back to Home](../index.md)

# How to create Dwains Dashboard blueprints?


Dwains Dashboard blueprints are pre-made pages or cards that you can easily add to your Home Assistant instance. Each blueprint can be added as many times as you want.

Quick links:

[Dwains Dashboard Blueprints](https://github.com/dwainscheeren/dwains-dashboard-blueprints)

## Creating Blueprints

You always gonna start with the header of a blueprint which looks like this.

````yaml
blueprint:
  custom_cards:
  - button-card
  description: description of blueprint
  input:
    entity_name:
      description: description shown
      name: entity name
  name: name of blueprint
  type: page
  version: '1.0.1'
card:  
````

Then you can follow with your YAML Code. 

## Configuration variables

All the options are available in the lovelace editor but you can use `yaml` if you want.

| Name                | Type    | Default              | Options | Description                                                                |
| :------------------ | :------ | :------------------- | :-------| :------------------------------------------------------------------------  |
| `custom_cards`      | string  | Optional             |         |  Used custom cards which were used. Will show in blueprint overview.       |
| `description`       | string  | Optional             |         |  adds a description to blueprint overview                                  |
| `input`             | string  | Optional             |         |  define input fields                                                       |
| `name`              | string  | Optional             |         |  Choose name of blueprint                                                  |
| `type`              | string  | Optional             |         |  defines type of blueprint page/card                                       |
| `version`           | string  | Optional             |         |  defines version of blueprints in blueprint overview                       |

