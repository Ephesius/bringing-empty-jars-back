Mod: Bringing Empty Jars Back v1.0.0

Description: Re-enables the previously deprecated re-use of jars. Now drinking from a jar lets the player keep the empty jar. Also, cooking recipes that require boiled water or beer from a jar lets the player keep the jar. The ability to craft empty jars at a forge has been re-implemented. Empty jars, along with a snowball, can once again be used at a campfire to make boiled water.

How it is implemented: For food recipes that use boiled water or beer as an ingredient, instead of simply crafting the food item, a "bundle" is crafted. This bundle contains the food as well as the empty jar. The bundle name is the same as the food to be crafted and the icon for this "bundle" is the same as the food icon, however there is the small "bundle icon" in the upper left corner of the food icon. The bundle is stackable to the same stack size as the crafted food. The bundle needs to be opened to receive the food and empty jar. For drinks, now when drinking a drink from a jar, the player keeps the empty jar. As soon as the drink action takes place, the empty jar will appear in the player's inventory.

List of food items that return an empty jar:
- Corn Bread
- Boiled Meat
- Vegetable Stew
- Meat Stew
- Hobo Stew
- Blueberry Pie
- Pumpkin Pie
- Pumpkin Cheesecake
- Pumpkin Bread
- Boiled Egg

List of drink items that return an empty jar:
- Murky Water
- Boiled Water
- Yucca Juice
- Pure Mineral Water
- Goldenrod Tea
- Red Tea
- Beer
- Coffee
- Grandpa's Moonshine
- Grandpa's Awesome Sauce
- Grandpa's Learning Elixir
- Grandpa's Forgetting Elixir

Empty jars can:
- Be filled with murky water from a water source like river or pond
- Be scrapped into broken glass
- Be stacked into stacks of 10
- Be crafted at a forge
- Be used, along with a snowball, at a campfire to make boiled water

Notes:
- The original icon from the game, although is still in the game files, appears to be broken and shows a blank icon in game. In order to keep this a server-side-only mod, the icon for the white barrel with a mild blue tint is used as the empty jar icon. Hopefully its appearance is similar enough to an empty jar.

- Compatible with 7 Days To Die v1.0