## Info:

- Auto loot items with customizable loot templates.

---

## Commands:

- **loot**
  - to toggle ON/OFF

- **loot overworld**
  - to toggle auto looting in overworld ON/OFF

- **loot instance**
  - to toggle auto looting in instances ON/OFF

- **loot templates**
  - to print a list of your custom templates in proxy chat
  - *(templates are defined in config.json)*

- **loot load**
  - to load new configuration from `config.json` file
  - *(for defining templates in runtime)*

- **loot save**
  - to save current configuration to your `config.json` file

- **loot set**
  - to set a template to be used by the auto loot module
  - Example: **loot set default** will set the auto loot module back to the default template

---

## Notes:

- The **default** template, blacklists looting only common items such as HP/MP/Keen motes *(can edit to your liking)*
- If a template contains item IDs in the whitelist, the blacklist will be completely ignored.
- If a template has no item IDs in the whitelist (empty), only the items in blacklist will **not** be looted.
- If a template has no item IDs in both the whitelist and blacklist, **all** item drops will be auto looted.

You can search for specific items and find their IDs here:
- https://teralore.com/us/items/
- http://teradatabase.net/us/items/

Alternatively, you can use this module to find item IDs in game:
- https://github.com/Tera-Shiraneko/item-id-finder

---

## Preinstalled Templates:

- **loot set ee**
  - Only **Elemental Essence** will be looted
- **loot set no-ee**
  - Loots everything except for **Elemental Essence**
 
- **loot set veil**
  - Only **Veilthroch** will be looted
- **loot set no-veil**
  - Loots everything except for **Veilthroch**
 
- **ee-veil**
  - Only **Elemental Essence** and **Veilthroch** will be looted
- **loot set no-ee-veil**
  - Loots everything except for **Elemental Essence** and **Veilthroch**
 
- **loot set amps**
  - Only **Amplifiers** will be looted
- **loot set no-amps**
  - Loots everything except for **Amplifiers**
 
- **loot set mallets**
  - Only **Sacred Mallets** will be looted
- **loot set no-mallets**
  - Loots everything except for **Sacred Mallets**
 
- **loot set amps-mallets**
  - Only **Amplifiers** and **Sacred Mallets** will be looted
- **loot set no-amps-mallets**
  - Loots everything except for **Amplifiers** and **Sacred Mallets**
 
- **loot set scrolls**
  - Only **Skill Advancement Scrolls** will be looted
- **loot set no-scrolls**
  - Loots everything except for **Skill Advancement Scrolls**
 
- **loot set claws**
  - Only **Devil's Claws** will be looted
- **loot set no-claws**
  - Loots everything except for **Devil's Claws**
 
- **loot set earring**
  - Only **Refined Lepidoptera Crystal Dust** will be looted
- **loot set no-earring**
  - Loots everything except for **Refined Lepidoptera Crystal Dust**
 
- **loot set ring**
  - Only **Refined Lepidoptera Crystal Powder** will be looted
- **loot set no-ring**
  - Loots everything except for **Refined Lepidoptera Crystal Powder**
 
- **loot set earring-ring**
  - Only **Refined Lepidoptera Crystal Dust & Powder** will be looted
- **loot set no-earring-ring**
  - Loots everything except for **Refined Lepidoptera Crystal Dust & Powder**

- **loot set necklace**
  - Only **Purified Ring Fragment** will be looted
- **loot set no-necklace**
  - Loots everything except for **Purified Ring Fragment**

- **loot set circlet**
  - Only **Purified Ornament Fragment** will be looted
- **loot set no-circlet**
  - Loots everything except for **Purified Ornament Fragment**

- **loot set circlet-necklace**
  - Only **Purified Ring & Ornament Fragment** will be looted
- **loot set no-circlet-necklace**
  - Loots everything except for **Purified Ring & Ornament Fragment**

- **loot set accessories**
  - Only the mats for all **Radiant Accessories** will be looted
- **loot set no-accessories**
  - Loots everything except for the mats for all **Radiant Accessories**
 
- **loot set marrow**
  - RIP Harrowhold.....many **Marrow Brooch** were looted :^)

---

Patch Version: **86.6**