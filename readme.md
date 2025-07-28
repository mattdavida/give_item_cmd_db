# Give Item Cmd - Item Database

This repository contains the complete mapped item database for the **Give Item Cmd** mod for Wuchang: Fallen Feathers.

## 🔗 Main Mod
**Download the mod here:** [Give Item Cmd on Nexus Mods](https://www.nexusmods.com/wuchangfallenfeathers/mods/86)

## 📋 About This Repository

This is a comprehensive collection of all useful items I could extract and map from Wuchang: Fallen Feathers' game data tables. The items have been:

- **Mapped for easier searching** - Clean, readable names instead of cryptic IDs
- **Separated by categories** - Weapons, armor, accessories, etc. organized in separate files
- **Tested and verified** - Only items confirmed to work with the give_item command

## 📁 File Structure

- `mapped_weapons.json`
- `mapped_armor.json`
- `mapped_ring.json`
- `mapped_spell.json`
- `mapped_cui.json`
- `mapped_item.json`

## 🎮 How to Use

1. Install the [Give Item Cmd mod](https://www.nexusmods.com/wuchangfallenfeathers/mods/86) first
2. Browse the JSON files to find items you want
3. Use the console command: `give_item <item_id> <quantity>`

**Example:**
```
give_item 10000 1    # Cloudfrost's Edge
give_item 19013 1    # Twin Lion Pendant
```

## 🔍 Finding Items

### Quick Search Tips:
- Use Ctrl+F in your browser to search item names
- Check the item ID ranges:
  - Weapons: 10000-15000+
  - Armor: 18000+
  - Accessories: 19000+

### Popular Items:
- **Cloudfrost's Edge**: ID 10000
- **Flamebringer +10**: ID 10030  
- **Dhutanga's Mask**: ID 18021
- **Twin Lion Pendant**: ID 19013

## ⚠️ Important Notes

- **For exploration & fun** - Not all 10,000+ items extensively tested
- **Weapon upgrades** - "+10" weapons spawn as base versions (game limitation)
- **Backup your saves** - Some items may behave unexpectedly
- **UE4SS required** - Console must be enabled in UE4SS settings

## 🤝 Contributing

Found missing items or errors? Feel free to:
- Open an issue with item details
- Submit a pull request with corrections
- Share newly discovered working item IDs

## 🏷️ Credits

Data extracted from Wuchang: Fallen Feathers using FModel and extensive testing.

---
**Remember:** Always backup your saves before experimenting with new items!
