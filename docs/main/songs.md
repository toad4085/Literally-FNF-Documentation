**Main** / **Songs**

# Songs

The Songs folder (`game.ServerStorage.Game.Stores`) stores all the FNF mod song configuration instances.

Songs themselves are stored in seperate folders, named after the mod they come from.

Song Folder's themselves don't have any attributes, however, song configuration instances do.

---

## Song Folder Structure

* **Song Instance** <sup>[`StringValue`](https://create.roblox.com/docs/reference/engine/classes/StringValue)</sup>

    * **Name** <sup>(This is the Song's name.)</sup>

    * **Value** <sup>`string` (This is the Song's [chart](https://file.garden/ZAE-7lkUN2HXG_xm/chinese%20propaganda%20poster%20with%20chairman%20mao%20and%20the%20defiant%20chinese.mp4).)</sup>

    * [**Fats_**](./fats) <sup>(This Folder allows charts to be bigger than the [StringValue.Value](https://create.roblox.com/docs/reference/engine/classes/StringValue/#Value) limit.)</sup>

    * [**MIDIs**](./midis) <sup>(This folder contains values that are used by the MIDI system.)</sup>

    * [**Song Attributes**](./song_attributes) <sup>(Song configuration values.)</sup>
