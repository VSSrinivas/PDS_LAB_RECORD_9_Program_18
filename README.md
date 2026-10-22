Program 18 - Arrays in Scala

Program18_ArraysInScala.scala

Demonstrates creating and working with arrays.

Creates an Array[Int] and prints its contents and length.
sumOfElements - returns the sum of all elements of an integer array using a for loop.
Creates an Array[String] of five fruit names.
concatenateWithCommas - joins all strings into one comma-separated string using mkString.
Iterates over the integer array using indices and prints each element with its index.

Concepts: Array, for loops, mkString, length, indices

Program 19 - Lists, Sets and Tuples

Program19_ListsSetsTuples.scala

Shows the basic immutable collection types in Scala.

Creates a List of the first five prime numbers.
squareList - returns a new list with every element squared using map.
Builds a Set[Char] of unique characters from "hello world" (spaces ignored) and prints its size.
intersectSets - returns the common characters of two sets ("hello world" and "scala world") using intersect.
Creates a tuple (Int, String, Boolean) and accesses each element using _1, _2, _3.

Concepts: List, Set, Tuple, map, intersect, toSet, tuple accessors

Program 20 - HashMaps and Collision Handling

Program20_HashMapCollisions.scala

Explores mutable.HashMap and how hash tables deal with collisions.

Creates a HashMap of student names and grades.
Inserts a duplicate key to show that the old value is overwritten.
mergeByHigherGrade - merges two HashMaps; when a key exists in both, the higher grade is kept.
ChainedHashMap - a simple custom hash table that resolves collisions by separate chaining (each bucket stores a list of key-value pairs; the bucket index is name length % buckets).
Retrieves all values stored for a key from the chained table, showing that colliding and duplicate keys are all preserved.

Concepts: mutable.HashMap, pattern matching on Option, hashing, separate chaining, collision resolution

Program 21 - Functional Combinators

Program21_FunctionalCombinators.scala

Applies the main higher-order functions on a list of integers from 1 to 10.

filter - keeps only the even numbers.
map - multiplies each element by 3.
flatMap - pairs each integer with its square, giving (n, n^2).
foldLeft - computes the product of all elements (10! = 3628800).
Chains filter -> map -> foldLeft to get the sum of the tripled even numbers (90).

Concepts: filter, map, flatMap, foldLeft, method chaining, anonymous functions

How to Run

Requires Scala installed (or Scala CLI).

bash
# Using scalac / scala
scalac Program18_ArraysInScala.scala
scala Program18_ArraysInScala

# Using Scala CLI
scala-cli run Program18_ArraysInScala.scala

Replace the file/object name with Program19_ListsSetsTuples, Program20_HashMapCollisions, or Program21_FunctionalCombinators to run the others.
