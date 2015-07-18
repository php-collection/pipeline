#Ideas
##Java Collections
* addAll (Adds all of the specified elements to the specified collection.)
* asLifoQueue (Returns a view of a Deque as a Last-in-first-out (Lifo) Queue.)
* binarySearch (Searches the specified list for the specified object using the binary search algorithm.)
* checkedCollection (Returns a dynamically typesafe view of the specified collection.)
* checkedList (Returns a dynamically typesafe view of the specified list.)
* checkedMap (Returns a dynamically typesafe view of the specified map.)
* checkedNavigableMap (Returns a dynamically typesafe view of the specified navigable map.)
* checkedNavigableSet (Returns a dynamically typesafe view of the specified navigable set.)
* checkedQueue (Returns a dynamically typesafe view of the specified queue.)
* checkedSet (Returns a dynamically typesafe view of the specified set.)
* checkedSortedMap (Returns a dynamically typesafe view of the specified sorted map.)
* checkedSortesSet (Returns a dynamically typesafe view of the specified sorted set.)
* copy (Copies all of the elements from one list into another.)
* disjoint (Returns true if the two specified collections have no elements in common.)
* emptyEnumeration (Returns an enumeration that has no elements.)
* emtpyIterator (Returns an iterator that has no elements.)
* emptyList (Returns an empty list (immutable).)
* emptyListIterator (Returns a list iterator that has no elements.)
* emptyMap (Returns an empty map (immutable).)
* emptyNavigableMap (Returns an empty navigable map (immutable).)
* emptyNavigableSet (Returns an empty navigable set (immutable).)
* emptySet (Returns an empty set (immutable).)
* emptySortedMap (Returns an empty sorted map (immutable).)
* emptySortedSet (Returns an empty sorted set (immutable).)
* enumeration (Returns an enumeration over the specified collection.)
* fill (Replaces all of the elements of the specified list with the specified element.)
* frequency (Returns the number of elements in the specified collection equal to the specified object.)
* indexOfSublist (Returns the starting position of the first occurrence of the specified target list within the specified source list, or -1 if there is no such occurrence.)
* lastIndexOfSublist (Returns the starting position of the last occurrence of the specified target list within the specified source list, or -1 if there is no such occurrence.)
* list (Returns an array list containing the elements returned by the specified enumeration in the order they are returned by the enumeration.)
* max (Returns the maximum element of the given collection, according to the natural ordering of its elements.)
* max (Returns the maximum element of the given collection, according to the order induced by the specified comparator.)
* min (Returns the minimum element of the given collection, according to the natural ordering of its elements.)
* min (Returns the minimum element of the given collection, according to the order induced by the specified comparator.)
* nCopies (Returns an immutable list consisting of n copies of the specified object.)
* newSetFromMap (Returns a set backed by the specified map.)
* replaceAll (Replaces all occurrences of one specified value in a list with another.)
* reverse (Reverses the order of the elements in the specified list.)
* reverseOrder (Returns a comparator that imposes the reverse of the natural ordering on a collection of objects that implement the Comparable interface.)
* reverseOrder (Returns a comparator that imposes the reverse ordering of the specified comparator.)
* rotate (Rotates the elements in the specified list by the specified distance.)
* shuffle (Randomly permutes the specified list using a default source of randomness.)
* shuffle (Randomly permute the specified list using the specified source of randomness.)
* singleton (Returns an immutable set containing only the specified object.)
* singletonList (Returns an immutable list containing only the specified object.)
* singletonMap (Returns an immutable map, mapping only the specified key to the specified value.)
* sort (Sorts the specified list into ascending order, according to the natural ordering of its elements.)
* sort (Sorts the specified list according to the order induced by the specified comparator.)
* swap (Swaps the elements at the specified positions in the specified list.)
* vannak thread-safe függvények is
* unmodifiableCollection (Returns an unmodifiable view of the specified collection.)
* unmodifiableList (Returns an unmodifiable view of the specified list.)
* unmodifiableMap (Returns an unmodifiable view of the specified map.)
* unmodifiableNavigableMap (Returns an unmodifiable view of the specified navigable map.)
* unmodifiableNavigableSet (Returns an unmodifiable view of the specified navigable set.)
* unmodifiableSet (Returns an unmodifiable view of the specified set.)
* unmodifiableSortedMap (Returns an unmodifiable view of the specified sorted map.)
* unmodifiableSortedSet (Returns an unmodifiable view of the specified sorted set.)
* euals
* clone

Clojure collections:
* count
* conj (add)
* seq (each)

Scala collections (mutable, immutable, generic):
(Immutable BitSets intersting)
* +, ++, -, --, /: , :/ (Applies a binary operator to a start value and all elements of this traversable or iterator, going left to right or left.)
* addString (Appends all bindings of this map to a string builder using start, end, and separator strings.)
* aggregate (Aggregates the results of applying an operator to subsequent elements.)
* andThen (Composes this partial function with a transformation function that gets applied to results of this partial function.)
* apply (Retrieves the value which is associated with the given key.)
* applyOrElse (Applies this partial function to the given argument when it is contained in the function domain.)
* canEqual (Method called from equality methods, so that user-defined subclasses can refuse to be equal to other collections of the same kind.)
* collect [use case] Builds a new collection by applying a partial function to all elements of this immutable hashmap on which the function is defined.
* collectFirst (Finds the first element of the traversable or iterator for which the given partial function is defined, and applies the partial function to it.)
* companion (The factory companion object that builds instances of class immutable.Iterable.)
* compose (Composes two instances of Function1 in a new Function1, with this function applied last.)
* contains (Tests whether this map contains a binding for a key.)
* copyToArray ([use case] Copies elements of this immutable hash map to an array.) slice
* copyToArray ([use case] Copies values of this immutable hash map to an array.)
* copyToBuffer (Copies all elements of this traversable or iterator to a buffer.)
* count (Counts the number of elements in the traversable or iterator which satisfy a predicate.)
* default (Defines the default value computation for the map, returned when a key is not found The method implemented here throws an exception, but it might be overridden in subclasses.)

Functions to implement:
* add
* each
* map
* reduce
* callback
* select | column
* where | filter
* collect | result
* reject
* remove
* indexOf
