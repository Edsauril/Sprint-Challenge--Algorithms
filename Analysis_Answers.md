Add your answers to the questions below.

1. What is the runtime complexity of your `heapsort` function? (If you used any
   Python built-in functions, you can find their time complexities here:
   https://wiki.python.org/moin/TimeComplexity )

O(n)

Other hints, to save you some searching:

- Heap insert: `O(log n)`
- Heap delete: `O(log n)`
- Heap get max: `O(1)`

2. Could one make your algorithm run in better time? If so, how? If not, why
   not?

I dont see a way of making it run any faster than O(n). O(log n ) would be faster but we need to add the items in the list one at a time, thats one operation per item which is O(n).

3. What is the space complexity of your `heapsort` function? Recall that your
   implementation should return a new array with the sorted data. (Also remember
   that the size of the input array passed to the `heapsort()` function does
   _not_ contribute to the size complexity.)

   0(n) space complexity

   Most online sources say that the space complexity of heapsort is `O(1)`. What
   would we have to change in our code to get there?

   change the heapsort from a class to a regular function
