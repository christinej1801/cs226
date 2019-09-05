# Homework 1

**Unique**
1. My algorithm works by first creating an empty integer array nums. Then it iterates through the list of command line arguments, and first tries to read each argument as an integer. If this is not possible, then we will jump to the catch block and throw an IllegalArgumentException. If the number can be read in, we check to see if the number is already in the integer array. If it is not, then we create a copy of the array with one extra space and the rest of the elements copied and we assign it to nums. The new unique integer is put into the extra spot and then printed to output. If the integer read is already in the array, the loop continues.

2. I originally started with an array that was the size of the array of commandline arguments, since I thought the worst case scenario would be one where every argument was unique. Then I realized that all the elements of that kind of array would be initialized to 0, which was a problem because my algorithm would not count 0 as a unique argument. 

3. I think having Java collection classes would have made the process easier. Having ArrayList would have made looking for an element and also changing the size of the array faster, since I would not have to make a new copy of the array every time another unique integer was read in.

4. I had some trouble with git, but my environment seems to be running and compiling fine.

**Counter Varieties**
1. An interface extends another interface in the same way that a class would inherit from another class. In this case ResetableCounter inherits the "methods" of the parent Counter interface, value(), up(), and down().

2. Any ResetableCounter is also a Counter. However, any Counter is not always a ResetableCounter.

3. This way, since all the counters we're testing are ResetableCounters, we can test their methods all at once and minimize writing redundant code. 

4. An up operation increases the counter's value by some positive increment, and a down operation decreases the counter's value by some increment.
