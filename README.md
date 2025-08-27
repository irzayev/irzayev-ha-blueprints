[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Firzayev%2Firzayev-ha-blueprints%2Frefs%2Fheads%2Fmain%2Fha-blueprint-linked-entities.yaml)

**Linked Entities v1.5** 🔛

This blueprint allows you to easily create/maintain an automation that links the state of multiple entities:
  - turn ANY linked entity ON, it will turn ON ALL linked entities.
  - turn ANY linked entity OFF, it will turn OFF ALL linked entities.
  - set the brightness of any light entity, it will set the same brightness of ALL linked light entities.
  - set the color temp of any light entity, it will set the same color temperature of ALL linked light entities.
  - set the color of any light entity, it will set the same color of ALL linked light entities.
  - set the speed (percentage) of any fan entity, it will set the speed of ALL linked fan entities.

**NOTE**: You can select any entity with an ON/OFF state (switches, lights, etc.), lights with brightness or color temperature attributes, and Fans with speed (percentage) attributes.

My main use-case was for multiple light switches in the house controlling the same light, but I also use it for other things:
  - at dawn, when I turn on the external lights (a shelly switch), I also link the pool light mqtt switch.
  - when I want to open the external gate, I can use several linked switches in multiple rooms of the house
  - when I want to manually turn on/off the irrigation system, I use two switches (internal and external) to activate my RainMachine cycle

I'm sure you'll find many more use-cases. :slight_smile:
