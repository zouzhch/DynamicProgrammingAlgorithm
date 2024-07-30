# DynamicProgrammingAlgorithm
A simple Java implement of Dynamic Programming Algorithm

Question:Assuming you are going to camping.You are having a bag of 6 pounds size,you need to decide which items below to take with.Every Item has its own value,the bigger the value is, the more important the item is.

Water(3 pounds, value 10);
Books(1 pound, value 3);
Food(2 pounds, value 9);
Jacket(2 pounds, value 5);
Camera(1 poundm value 6).

Please answer choose which items to take with will have a highest value?

Thinking:
  Dynamic Programming Algorithm
     Core Algorithm:
           To split the problem:
           ---first consider the situation only have one item and 1 size of the bag,
              calculate the optimum value.
           ---then 2 size of the bag...to 6 size of the bag,
               calculate the optimum value.
           ---then the two items and 1 size of the bag...to 6 size of the bag,
               calculate the optimum value.During this progress,the prior optimum value
               can be used as the optimum value at the remaining size of
               the bag which has bagged the present item.
           ---by parity of reasoning, go on then finally we can calculate the optimum
               value of five items and 6 size of the bag.
