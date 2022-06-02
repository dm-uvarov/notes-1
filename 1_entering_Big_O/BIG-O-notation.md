

when descibing which algorythm better, usualy mening 3 points:

1. Faster => meaning the lesser quantity of operation algorytm makes. regardless of how calculatiuons was made in counts only power of quantity of operations. ex: 5n+7 operations could be 2n but realy meaniing ~ of n operations and use O(n). big o- notations is way to simplify and formilize counting. and as it was in limits in math we count only highest power of operations 4n^5 + n +100000 => O(n^5)

cite start
 Big O Definition
We say that an algorithm is O(f(n)) if the number of simple operations the computer has to do is eventually less than a constant times f(n), as n increases

some shorthands

Arithmetic operations are constant
Variable assignment is constant
Accessing elements in an array (by index) or object (by key) is constant
In a loop, the the complexity is the length of the loop times the complexity of whatever happens inside of the loop
cite end


2. space consuming => space complexity
====
Sometimes you'll hear the term auxiliary space complexity to refer to space required by the algorithm, not including space taken up by the inputs.
====
Rules of Thumb
Most primitives (booleans, numbers, undefined, null) are constant space
Strings require O(n) space (where n is the string length)
Reference types are generally O( n) time, where n is the length (for arrays) or the number of keys (for objects)

An Example

=====
logarifmic complexity is great
Certain searching algorithms have logarithmic time complexity.
Efficient sorting algorithms involve logarithms.
Recursion sometimes involves logarithmic space complexity.