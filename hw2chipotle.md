1. The columns means as follow: (head chipotle.tsv)
    Order_id = It is the number of the POS order and can have multiple items in each order. 
    quantity = the amount 
    item_name = description of the item 
    choice_description = what's the detail composition of the food such as burritos
    price = $
    Each row is an item within a order. so there can be multiple items 
2. There are 1834 orders in the file (tail chipotle.tsv)

3. The total lines are 4623 (wc-l chipotle.tsv)

4. **Chicken** (553) is more popular than Steak (368).  Using piping function grep -i 'steak burrito' chipotle.tsv | wc -l

5. one additional piping 
    **Black beans** are more popular
    grep -i 'chicken burrito' chipotle.tsv | grep -i 'black beans' | wc -l

6. i utilzied "find . -name *.?sv" retrieve all the tsv and csv files. see attachment.  Homework2.png
7. ** 84** under DAT2 grep -ir 'dictionary'. |wc -l




    
