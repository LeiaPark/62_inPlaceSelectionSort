# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow 3 times. The algorithm is run for each element in the list. Therefore, if the number of elements multiplies by 3, the the algorithm has to also run 3 more times, and the time it takes must increase 3 times.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow 3 times. The algorithm is run for each element in the list. Therefore, if the number of elements multiplies by 3, the the algorithm has to also run 3 more times
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by 3 times. The selection sort also invokes the reigning champ algorithm, which runs for each element in the list. Therefore, if the number of elements multiplies by 3, the the algorithm has to also run 3 more times, leading to the selection short taking 3 times the time.
[Justify, in about 2 sentences.]
