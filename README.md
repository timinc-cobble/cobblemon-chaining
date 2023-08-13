# Unchained

Add some spice to your Cobblemon world by adding hidden abilities, shiny boosts, guaranteed perfect IVs, and synchronized natures to wild spawning Pokémon, based on the points nearby users have accumulated with KOs, KO streaks, captures, and capture streaks for that Pokémon’s species.

## Features

### Hidden Booster

The Hidden Booster module gives spawning Pokémon the opportunity to spawn with their hidden ability. Each threshold grants a chance of `first` out of `second` that the spawning Pokémon will unlock their hidden ability slot. The default values for `hiddenBoost.json5` make it so that a player who most recently KO’d a given species, or someone who has KO’d at least 100 of a given species will give that species a 1 in 5 (20%) chance to spawn with its hidden ability 64 blocks around that player.

### Shiny Booster

The Shiny Booster module enhances the likelihood of encountering shiny Pokémon spawns. With each threshold reached, the chances of encountering a shiny Pokémon during spawn increase. When employing the default settings of `shinyBoost.json5` in conjunction with Cobblemon's default configuration values, the following shiny spawn rates are obtained: 2/8196 for a KO streak of 101+, 3/8196 for 301+, 4/8196 for 501+, and for all other cases 1/8196.

### IV Booster

The IV Booster module gives spawning Pokémon guaranteed perfect IVs based on the highest of a nearby player’s points. With the default `ivBoost.json5`, a capture streak of 6+ gives 1, 11+ gives 2, 21+ gives 3, and 30+ gives 4.

### Synchronized Natures

The Synchronized Natures module is a little different; it requires that a nearby player have a Pokémon with the Synchronize ability - optionally in the first slot of their party - in order to influence a nearby spawning Pokémon’s nature. This follows the rules of the out-of-battle effect of Synchronize in the main game. Points are only considered when multiple eligible players are nearby. When choosing a player from the list of eligible players, each player has one chance for every point they have.

### Points

Each main feature comes with its own config. The first few properties allow you to specify a multiplier for each different type of recorded count, including KOs, KO Streaks, captures, and capture streaks. For example, the default config for the IV Booster gives a multiplier of 0 for all but capture streaks, and 1 for capture streaks. This means that for each point in your current capture streak for a specific Pokémon, you have 1 point towards your total score.

## Dependencies

Cobblemon [Modrinth](https://modrinth.com/mod/cobblemon) / [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cobblemon)

Cobblemon Counter [Modrinth](https://modrinth.com/mod/cobblemon-counter) / [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cobblemon-counter)

Fabric Language Kotlin [Modrinth](https://modrinth.com/mod/fabric-language-kotlin) / [CurseForge](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin)

Cloth Config [Modrinth](https://modrinth.com/mod/cloth-config) / [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cloth-config)