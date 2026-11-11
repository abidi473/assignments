Problems (codes showing them are in the 2_work.ipynb file)

1. The raw file contains an empty cell in the price column.
2. The raw file contains a duplicate.
3. There is a price with a comma in the raw file.
4. There is one item named "oil b" which is being counted as a different from other items of its group due to difference in capitalization.

Decisions

1. Enter the missing price because incomplete data should not be relied on and it will give a faulted average of any of the 5 items.
2. Remove the duplicate because the copy is not necessary and will lead to incorrect statistics.
3. Remove the comma, because Python cannot read the value.
4. Capitalize it the way other items of its group have been capitalized because this will allow correct categorization for Python to read.

