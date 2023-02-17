# RecordCollection
musical album collection

You are given an object literal representing a part of your musical album collection. Each album has a unique id number as its key and several other properties. Not all albums have complete information.

You start with an updateRecords function that takes an object literal, records, containing the musical album collection, an id, a prop (like artist or tracks), and a value. Complete the function using the rules below to modify the object passed to the function.

    Your function must always return the entire record collection object.
    If prop isn't tracks and value isn't an empty string, update or set that album's prop to value.
    If prop is tracks but the album doesn't have a tracks property, create an empty array and add value to it.
    If prop is tracks and value isn't an empty string, add value to the end of the album's existing tracks array.
    If value is an empty string, delete the given prop property from the album.

Note: A copy of the recordCollection object is used for the tests.

Hint 1 - Use an if...else if chain to check the different values of prop and value.
Hint 2 - To access the value of a key in this object, you will use bracket notation: records[id][prop].
Hint 3 - You can’t push to an array that doesn’t exist. If the "tracks" array does not exist yet, you need to create the "tracks" array before pushing value onto it.

https://forum.freecodecamp.org/t/challenge-guide-record-collection-deep-explanation/416606/2
