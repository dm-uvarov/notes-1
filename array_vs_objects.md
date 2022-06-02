ARRAYS VS OBJETCS intro


Unordered, key value pairs!

let instructor = {
    firstName: "Kelly",
    isInstructor: true,
    favoriteNumbers: [1,2,3,4]
}

When to use objects
* When you don't need order
* When you need fast access / insertion and removal

big - O of objects
Insertion -   O(1)
Removal -   O(1)
Searching -   O(N)
Access -   O(1)
When you don't need any ordering, objects are an excellent choice!
Big O of Object Methods
Object.keys -   O(N)
Object.values -   O(N)
Object.entries -   O(N)
hasOwnProperty -   O(1)


================================================================
ARRAYS
ordered lists: 


let names = ["Michael", "Melissa", "Andrea"];
let values = [true, {}, [], 2, "awesome"];

WHEN TO USE ARRAYS
* When you need order
* When you need fast access / insertion and removal (sort of....)

Big O of Arrays
Insertion -   It depends....
(Inserting at the beginning is not as easy as we might think! There are more efficient data structures for that!)
Removal -   It depends....
Searching -   O(N)
Access -   O(1)

push -   O(1)
pop -   O(1)
shift -   O(N)  
unshift -   O(N)
concat -   O(N)
slice -   O(N)
splice -   O(N)
sort -   O(N * log N)
forEach/map/filter/reduce/etc. -   O(N)

 b