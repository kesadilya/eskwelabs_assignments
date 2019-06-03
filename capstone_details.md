# Algorithm output
Analyzes all outstanding purchase requisitions and decides whether:

1. The goods that are to be purchased still exist in the inventory;
2. Good A may be bundled with all other Good As from purchase requests from different departments
3. Good A may be bundled with other goods, let us say Good B or C; and
3. Goods can be combined with other services (good to have).

# Factors to look at:
1. Historical suppliers - given an item, who were previously engaged with;
2. Material Code/ Material Groups - the groupings of each item;
3. Inventory Level - check if good to be ordered are still available in the inventory, and there is enough stock
4. Month and year of Purchase order - to see if there are seasonalities in items that are being bought
5. Services and Goods tag - to see what items can be bundled
6. Historical prices - to check what goods are cheaper when bought from supplier to another supplier.
7. Buyer- to rule out the bias of differences in prices due to buyer 
8. Unit Prices - same item that were bought from different suppliers have very different unit prices.

# Data Source
1. 6 years worth of procurement data
2. Inventory data
