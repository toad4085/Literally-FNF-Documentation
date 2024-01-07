**Main** / [**Visuals**](.. "shitballs") / **Entities**

# Entities
Entities are the character models for Opponents, Players and Speakers.

There are two types of Entities:

* **Chars** <sup>(eg. Boyman and Dad)</sup>
* **Speakers** <sup>(eg. Gal-Pal)</sup>

---

## Attributes

* **FacingLeft**<sup>`Boolean`</sup><br><div style="padding-left: 15px;">
A descriptor used to identify whether the character is facing left or not. For example, it is set to true for Boyman, and set to false for Dad.
</div>

* **HealthIcon**<sup>`ImageID`</sup><br><div style="padding-left: 15px;">
The ImageID that the entity is using for its health icon.
</div>

* **IconRectPos**<sup>`Vector2` `(optional)`</sup><br><div style="padding-left: 15px;">
The coordinates of the entity's health icon in the health icon spritesheet. The spritesheet uses the Image set in the `HealthIcon` attribute.</div>