# First LISP Program
This project is comprised of a collection of LISP function definitions.

##Function Definitions

* (myLast L) - Evalulates to the last element of list L
* (myCount X L) - Evaluates to the number of occurences of X in list L
* (myMember X L) - Evaluates to 'true' if X is in list L, 'false' otherwise
* (myPurge L) - Evalulates to a list with all elements of L minus repetition
* (myCommon L1 L2) - Evalulates to a list of elements that are common in both L1 and L2 assuming both lists do not contain any repeated elements.
* (myGen X Y Z) - Given integers X, Y, and Z, evaluates to the list of increasing integers between X and Y (inclusive) with Z as the increment (nil if such a list does not exist)
* (myMap F L) - Evaluates to the list which results from applying function F to every element of list L
* (myReduce F L) - Evaluates to the results of applying aggregate function F to the elements of L. L will be of size >= 2. F will be a commutative function.

Common LISP pre-defined forms are not utilized in this project.
