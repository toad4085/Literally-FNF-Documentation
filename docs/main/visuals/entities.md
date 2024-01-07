**Main** / [**Visuals**](.. "shitballs") / **Entities**

# Entities
Entities are the character models for Opponents, Players and Speakers.

There are two types of Entities:

* **Chars** <sup>(eg. Boyman and Dad)</sup>
* **Speakers** <sup>(eg. Gal-Pal)</sup>

---

## Attributes

* **FacingLeft**<sup>`Boolean`</sup><br>
Determines whether the character is facing the left. This is necessary so that the character faces the correct direction ingame.

* **HealthIcon**<sup>`ImageID`</sup><br>
The ImageID that the entity is using for its health icon.

* **IconRectPos**<sup>`Vector2` `(optional)`</sup><br>
The coordinates of the entity's health icon in the health icon spritesheet. The spritesheet uses the Image set in the `HealthIcon` attribute.