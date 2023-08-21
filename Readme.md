# ExtendScript-Set

 A lightweight Set class extension for Adobe ExtendScript.

This project was originally intended for learning purposes, but in the end turned into a full Map implementation. As ExtendScript is a version of ES3 implemented by Adobe, it is not fully compatible with ES3. This version can be used with Adobe programs such as Illustrator, InDesign/InCopy, or Photoshop.

This Set class is an implementation of the JavaScript built-in Set object.
It has all the standard Set methods as well as some additional ones are in some stage of tc39 proposal phase.

## Properties
* `size` - The number of elemets in the set

## Standard methods for the Set object

* `add(value)` - Adds a value to the set.
* `clear()` - Clears all element in the set and sets the size to 0.
* `delete(value)` - Deletes the given value from the set.
* `entries()` - Returns a new set iterator object that contains the value/value pairs for each element in the set.
* `forEach()` - Iterates through each element of the set and applies a callback function.
* `has(value)` - Checks if the given value exists in the set object or not.
* `keys()` - The keys() method is an alias for the values() method.
* `values()` - Returns a new set iterator object that contains the values for each element in the set.

## Additional non-standard methods
*(They are mostly Array-like methods in some stage of tc39 proposal phase)*

* `every()` - Checks if all elements in the set satisfy the provided callback function
* `filter()` - Filters the elements of a Set object based on a provided callback function
* `find()` - Finds the first element in the set that satisfies the provided testing function
* `from()` - Adds new Set element to the set.
* `isEmpty()` - Determines whether the given parameter is an empty Set.
* `isSet()` - Checks if an object is a Set.
* `map()` - Applies a callback function to each element in the set and returns a new set with the results.
* `reduce()` - Reduce the set to a single value by applying a callback function
* `some()` - Checks if any element in the set satisfies the provided callback function
* `toArray()` - Returns an array representation of the set.
* `toString()` - Returns a string representation of the set.

## Set operations

* `union()` - Returns a new Set with the union of the two sets
* `difference()` - Calculates the difference between the current set and another set.
* `symmetricDifference()` - Calculates the symmetric difference between this set and another set.
* `intersection()` - Calculates the intersection of two sets.
* `isSubset()` - Checks if the current set is a subset of another set
* `isSuperset()` - Checks if the current set is a superset of another set
* `isDisjoint()` - Checks if the current set is a disjoint of another set
* `isEqual()` - Checks if the current set is equal to another set

## Externals

* `Array.isArray()` - Checks if an argument is an array.
* `Array.isEmpty()` - Checks if an array is empty.
* `Array.prototype.toString()` - Returns a string representation of the array.
* `Object.isEmpty()` - Checks if an object is empty.
* `sameValueZero()` - Determines if two values are equal using the SameValueZero algorithm.
* `isPrimitive()` - Check if the given value is a primitive data type or null/undefined.