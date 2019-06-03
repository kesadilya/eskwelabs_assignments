# Algorithm output
Analyzes all outstanding purchase requisitions and decides whether:

1. The goods that are to be purchased still exist in the inventory;
2. The goods can be bundled with other goods;
3. The goods can be combined with other services. 

# Factors to look at:
1. Historical suppliers - given an item, who were previously engaged with;
2. Material Code/ Material Groups - the groupings of each item;
3. Inventory Level - check if good to be ordered are still available in the inventory, and there is enough stock
4. Month and year of Purchase order - to see if there are seasonalities in items that are being bought
5. Services and Goods tag - to see what items can be bundled
6. Historical prices - to check what goods are cheaper when bought from supplier to another supplier.
