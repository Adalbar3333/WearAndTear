**Wear and Tear**
This alias allows you to add items to your equipment bag, damage them, and roll checks to repair them. If you want more information on the rules, please run `!wat help` which will both show the following information, and explain the rules, and how to use it in game.

__***Arguments***:__

`add <item>` This adds an item to your `Equipment Bag`. If you use the `!bag` alias, it will show up there. `<item>` should be an item from the players handbook, or in your server's Homebrew. 
- `-name` adds a custom name to the item. 
- `-mb` adds a magical bonus to the item.
- `-metal` defines what metal the item will be. 


`repair` Adds 1d4 on a successful check to repair an item. 
Requires `-skill <skill> | -tool <tool> -a <attribute>`. The roll also accepts `adv|dis` and `guidance` as arguments. 


`damage` Removes 1 HP from the item. You can add `-d #` do do more than one damage.


`list|display` will show your `Equipment` bag.
