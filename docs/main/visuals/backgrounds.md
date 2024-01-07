**Main** / [**Visuals**](.. "shitballs") / **Backgrounds**

# Backgrounds 
Backgrounds are everything that's displayed in the background during gameplay.

Every background is composed of multiple assets:

* [**Spawns**](./spawns) <sup>(Determines where [Entities](../entities) are placed in the background.)</sup>

* [**Background Sprites**](./background_sprites) <sup>(Consists of Images or Spritesheets with [Animation](https://file.garden/ZAE-7lkUN2HXG_xm/chinese%20propaganda%20poster%20with%20chairman%20mao%20and%20the%20defiant%20chinese.mp4) objects.)</sup>

---

## Attributes

* **BGSize**<sup>`Vector2`</sup><br>
Adjusts the background's scaling.

## Formatting

All Background folders follow a specific way of formatting.

A background's folder name includes a shortened version of a Mod's name and the background's name seperated with an underscore:  

``ModTag_BackgroundName``

For Example, a mod with the name "Arcade Showdown" has the tag "AS". The name of one of the stages is "Sanctuary".
If we were to make a Background folder using that information, it would be formatted as follows:  

`AS_Sanctuary`