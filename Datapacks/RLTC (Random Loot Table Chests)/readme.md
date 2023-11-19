# Random Loot Datapack

## Description

This Minecraft datapack generates random loot in custom chests based on predefined loot tables.

## Installation

1. Download the latest version of the datapack here (link)
2. Move the file to the `datapacks` folder in your Minecraft world directory.

## Usage

1. Load or reload your Minecraft world.
2. Use the `/reload` command to reload datapacks.
3. Use `/datapack enable "file/rltc.zip"` to enable the datapack.
4. Run the command `/setblock ~ ~ ~ minecraft:chest{LootTable:"rltc:blocks/loot_table"} replace`, this will place a block where you are standing with the loot table.

## Customization

- **Loot Tables:** Customize the loot by modifying the `loot_tables` folder.

## Notes

- Avoid frequent use of `/reload` for optimal performance.
- Test in your specific environment to observe performance.
- Contact Hamziee for any issues or improvements. (You can also create a pull request!)

## Credits

This datapack was created by Hamziee.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License - see the [LICENSE.md](https://github.com/HEO-Systems/Link101/blob/main/LICENSE) file for details.
