![Java-runtime-beta Screenshot 2022 06 23 - 19 31 35 65](https://user-images.githubusercontent.com/83653555/176735339-61d07497-8f9f-406f-9993-db764d1f525f.png)
![Java-runtime-beta Screenshot 2022 07 03 - 19 25 24 48](https://user-images.githubusercontent.com/83653555/177048584-210fc4b7-a637-42b7-b846-94989fccadc4.png)

# Quick Harvest [plugin for minecraft 1.13+]
Plugin that let you harvest the plants by right-clicking and automatic replant it again!
- Quick harvest by dispenser! (You can disable this feature in plugin config)
- Quick harvest by right click! (You can disable this feature in plugin config)
- Expand the list of supported plants at your discretion! Currently supported:
  - `minecraft:wheat`
  - `minecraft:beetroots`
  - `minecraft:potatoes`
  - `minecraft:carrots`
  - `minecraft:nether_wart`
  - `minecraft:cocoa`

### Settings in `config.yml`
```yml
sound: minecraft:block.composter.ready  # played sound when quick harvest

feature:
  player: true  # quick harvest by right-click
  dispenser: true  # quick harvest by dispenser

reason:
  minecraft:wheat_seeds:  # item in hand
    target: minecraft:wheat  # harvest block (works when harvest age equals max age)

  minecraft:beetroot_seeds:
    target: minecraft:beetroots

  minecraft:potato:
    target: minecraft:potatoes

  minecraft:carrot:
    target: minecraft:carrots

  minecraft:nether_wart:
    target: minecraft:nether_wart

  minecraft:cocoa_beans:
    target: minecraft:cocoa
```

[[Download latest version]](https://github.com/TeaCondemns/quick-harvest-plugin/releases/tag/normal-functionality)
