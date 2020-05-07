Here we going to learn about 'How to handle missing values from data set'

1. Deleting those recordes
2. Create new model to generate the missing values
 Example:
if feature is A,B,C and output is OP 
     A B C   OP
0 -> - 2 2   4
1 -> 2 2 2   8
2 -> 3 2 2   12

So now have to create model with, inputs of OP, B, C and A as output,
by providing non-missing values to the model we can predict the missed values from the dataset
<b>Note: </b> This will not suitable for biger dataset, due to the requirment of more time and computational power

3. Some statistical method like Mean, Meadinan, Mode

 Example:
By finding mean or meadian or mode of column which consist missed values,
<b>Note: </b> before finding values we need to sort the column inc\ case of finding MODE 