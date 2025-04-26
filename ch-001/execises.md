# Exercises

## 1.1-1

> Decribe your own real-world example that requires sorting. \
  Describe one that requires finding the shortest distance \
  between two points.

If we think abstract enough, many computational problems can be narrowed down to sorting.

Sorting is the basis for optimizing other algorithms, for example; if we put the limit far 
away, sorting can indeed be applied to thousands of problems, even though it wasn't the original purpose.

On the other hand, problems which extract the "finding shortest path" idea can be reduced to graphs,
as many other problems would, but one example are ride apps, like Uber, or even
Google Maps, Waze, etc; the idea of shortest path fit like a glove for those examples, but
actually they fit nicelly to many other fields as well. 

Internet providers, for example, expand their coverage areas by finding the shortest path to
deliver internet access to the most distant communities.

## 1.1-2

> Other than speed, what other measures of efficiency might you need to consider
  in a real-world setting?

Resource usage will at many circunstaces be a metric.

## 1.1-3

> Select a data structure that you have seen, and discuss its strenghts and limitations.

I pick stacks. Stacks are the ds behind compilers, function calls, graphs traversal, and many real world examples as well.

Stacks make it easy to get context to be stored and restore, thus, a living state machine.

At other hand, they will not hold to *all* problems, but when they fit in, they fit in nicelly.

## 1.1-4

> How are the shortest-path and traveling-salesperson problems given above similar? \
  How are they different?

Both run on a graph implementation

## 1.1-5

> Suggest a real-world problem in which only the best solution will do. Then come up \
  with one in which "approximately" the best solution is good enough.

Systems that deal with highly sensitive data will *need* to pick the best solution. For example,
medical device systems, in which a person's live is at risk.

## 1.1-6

> Describe a real-world problem in which sometimes the entire input is available before \
  you need to solve the problem, but other times the input is not entirely available in advance \
  and arrives over time.

Algorithms that sense data, that is, run over batch and streaming/online mode will fit.

Insertion sort will fit into online algorithms field: they can correctly maintain a sorted
list as new elements arrive one by one, thus, the correctness of such algorithm is given by
an not entirely available input as it can arrive over time.

Merge sort, on the other hand, will *need* all the data to be set up before running, thus,
not an online algorithm.

