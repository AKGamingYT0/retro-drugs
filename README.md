# Archive
## New, good version will be released soon by Orchid Studios
This one has to many problems

# retro-drugs
FiveM resource that adds opportunity to deal drugs to NPCs with NPC Voice lines

First of all drag and drop this resource to your resource foldel.
Now if you using **ox_inventory** copy the items you need from items.lua file (in this resource) and simply paste them to the table into items.lua (in ox_ivnventory/data folder) and don't forget images for your items. Or you can simply define your own drungs!

For those who want to use another inventory, you can try doing ыimilarly with your inventory (paste copied items to where they are stored), but you might need to chage the way how they are defined (especially additional buttons I use in this case to call an export form the resource)

You can also implement another logic of selling (ox_target or another button) by simply calling 
```
exports['retro-drugs']:selltoNPC('name_of_your_drug')
```
wherever you might need.

I also left a line with event to call the cops, but the logic for it is not included in this resource, so you would have to add your own.


