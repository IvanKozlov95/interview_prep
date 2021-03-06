
# [Daily Coding Problem](https://dailycodingproblem.com/)

Daily Coding Problem is a mailing list for coding interview problems. Get exceptionally good at coding interviews by solving one problem every day.
See their [blog](https://dailycodingproblem.com/blog).

---

### Problem 297

This problem was asked by Amazon.

At a popular bar, each customer has a set of favorite drinks, and will happily accept any drink among this set. For example, in the following situation, customer 0 will be satisfied with drinks 0, 1, 3, or 6.

    preferences = {
        0: [0, 1, 3, 6],
        1: [1, 4, 7],
        2: [2, 4, 7, 5],
        3: [3, 2, 5],
        4: [5, 8]
    }

A lazy bartender working at this bar is trying to reduce his effort by limiting the drink recipes he must memorize. Given a dictionary input such as the one above, return the fewest number of drinks he must learn in order to satisfy all customers.

For the input above, the answer would be 2, as drinks 1 and 5 will satisfy everyone.

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/297/solution.py)

---

### Problem 298

A girl is walking along an apple orchard with a bag in each hand. She likes to pick apples from each tree as she goes along, but is meticulous about not putting different kinds of apples in the same bag.

Given an input describing the types of apples she will pass on her path, in order, determine the length of the longest portion of her path that consists of just two types of apple trees.

For example, given the input `[2, 1, 2, 3, 3, 1, 3, 5]`, the longest portion will involve types `1` and `3`, with a length of four.

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/298/solution.py)

---

### Problem 299

A group of houses is connected to the main water plant by means of a set of pipes. A house can either be connected by a set of pipes extending directly to the plant, or indirectly by a pipe to a nearby house which is otherwise connected.

For example, here is a possible configuration, where A, B, and C are houses, and arrows represent pipes:

        A <--> B <--> C <--> plant

Each pipe has an associated cost, which the utility company would like to minimize. Given an undirected graph of pipe connections, return the lowest cost configuration of pipes such that each house has access to water.

In the following setup, for example, we can remove all but the pipes from plant to A, plant to B, and B to C, for a total cost of 16.

        pipes = {
            'plant': {'A': 1, 'B': 5, 'C': 20},
            'A': {'C': 15},
            'B': {'C': 10},
            'C': {}
        }

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/299/solution.py)

---

### Problem 305

Given a linked list, remove all consecutive nodes that sum to zero. Print out the remaining nodes.

For example, suppose you are given the input `3 -> 4 -> -7 -> 5 -> -6 -> 6`. In this case, you should first remove `3 -> 4 -> -7`, then `-6 -> 6`, leaving only 5.

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/305/solution.py)

---

### Problem 305

Given an unsorted array, in which all elements are distinct, find a "peak" element in `O(log N)` time.

An element is considered a peak if it is greater than both its left and right neighbors. It is guaranteed that the first and last elements are lower than all others.

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/311/solution.py)

---

### Problem 309

There are `M` people sitting in a row of `N` seats, where `M < N`. Your task is to redistribute people such that there are no gaps between any of them, while keeping overall movement to a minimum.

For example, suppose you are faced with an input of `[0, 1, 1, 0, 1, 0, 0, 0, 1]`, where `0` represents an empty seat and `1` represents a person. In this case, one solution would be to place the person on the right in the fourth seat. We can consider the cost of a solution to be the sum of the absolute distance each person must move, so that the cost here would be **five**.

Given an input such as the one above, return the lowest possible cost of moving people to remove all gaps.

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/309/solution.py)

---

### Problem 301

Implement a data structure which carries out the following operations without resizing the underlying array:

    add(value): Add a value to the set of values.
    check(value): Check whether a value is in the set.

The check method may return occasional false positives (in other words, incorrectly identifying an element as part of the set), but should always correctly identify a true element.

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/301/solution.py)

___

### Problem 303

This problem was asked by Microsoft.

Given a clock time in `hh:mm` format, determine, to the nearest degree, the angle between the hour and the minute hands.

Bonus: When, during the course of a day, will the angle be zero?

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/303/solution.py)

---

### Problem 310

Write an algorithm that finds the total number of set bits in all integers between `1` and `N`.

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/310/solution.py)

---

### Problem 315

In linear algebra, a Toeplitz matrix is one in which the elements on any given diagonal from top left to bottom right are identical.

Here is an example:
```
1 2 3 4 8
5 1 2 3 4
4 5 1 2 3
7 4 5 1 2
```
Write a program to determine whether a given input is a Toeplitz matrix.

[Solution](https://github.com/ivankozlovcodes/interview_practice/blob/master/daily_coding_problem/315/solution.py)
