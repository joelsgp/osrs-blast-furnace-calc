# osrs-blast-furnace-calc
Calculator for buying blast furnace materials, uses GE API to get item costs

Supports runescape quantity notation - e.g. 1m = 1000000, 1k = 1000    
I had to make the function to parse those anyway, the API uses them

If you want to use it for other calculations you need to put the API item IDs,the items and their ratios, and the free inventory space into the code, `inv_space`, `item_ratios`, `item_ids`, `time_ratio_seconds`, `base_item`
