Download Link: https://assignmentchef.com/product/solved-cs519-hw3-k-closest-numbers-two-pointers
<br>
Need to submit: report.txt, closest_unsorted.py, closest_sorted.py, xyz.py.

closest_sorted.py will be graded for correctness (1%).

Textbooks for References:[1] CLRS

1. Given an array A of n numbers, a query x, and a number k,find the k numbers in A that are closest (in value) to x.For example:

find([4,1,3,2,7,4], 5.2, 2) returns [4,4]find([4,1,3,2,7,4], 6.5, 3) returns [4,7,4]find([5,3,4,1,6,3], 3.5, 2) returns [3,4]

Filename: closest_unsorted.pyMust run in O(n) time.The elements in the returned list must be in the original order.In case two numbers are equally close to x, choose the earlier one.

2. [WILL BE GRADED]Now what if the input array is sorted? Can you do it faster?

find([1,2,3,4,4,7], 5.2, 2) returns [4,4]find([1,2,3,4,4,7], 6.5, 3) returns [4,4,7]

Filename: closest_sorted.pyMust run in O(logn + k) time.The elements in the returned list must be in the original order.

Note: in case two numbers are equally close to x, choose the smaller one:find([1,2,3,4,4,6,6], 5, 3) returns [4,4,6]find([1,2,3,4,4,5,6], 4, 5) returns [2,3,4,4,5]

Hint: you can use Python’s bisect.bisect for binary search.

3. For a given array A of n *distinct* numbers, find all triples (x,y,z)s.t. x + y = z. (x, y, z are distinct numbers)

e.g.,

find([1, 4, 2, 3, 5]) returns [(1,3,4), (1,2,3), (1,4,5), (2,3,5)]

Note that:1) no duplicates in the input array2) you can choose any arbitrary order for triples in the returned list.

Filename: xyz.pyMust run in O(n^2) time.

Hint: you can use any built-in sort in Python.

Debriefing (required!): ————————–

0. What’s your name?1. Approximately how many hours did you spend on this assignment?2. Would you rate it as easy, moderate, or difficult?3. Did you work on it mostly alone, or mostly with other people?Note you are encouraged to discuss with your classmates,but each students should submit his/her own code.4. How deeply do you feel you understand the material it covers (0%-100%)?

5. Which part(s) of the course you like the most so far?6. Which part(s) of the course you dislike the most so far?

This section is intended to help us calibrate the homework assignments.Your answers to this section will *not* affect your grade; however, skipping itwill certainly do.


