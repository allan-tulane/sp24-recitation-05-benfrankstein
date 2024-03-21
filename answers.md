# CMPS 2200 Reciation 5
## Answers

**Name:** Ben Frankstein


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**

Fixed Pivot -
work = O(n^2)
span = O(n log n)

Random - 
work = O(n log n)
span = O((log n)^2)

Tim - 
work = O(n log n)
span = O((log n)^2)



- **1c.**

|      n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |
|--------|---------------------|----------------------|------------|
|    100 |               0.054 |                0.065 |      0.006 |
|    200 |               0.114 |                0.170 |      0.011 |
|    500 |               0.366 |                0.400 |      0.032 |
|   1000 |               0.732 |                1.060 |      0.074 |
|   2000 |               1.635 |                1.863 |      0.152 |
|   5000 |               4.507 |                4.835 |      0.387 |
|  10000 |               8.654 |               10.007 |      0.844 |
|  20000 |              18.744 |               20.628 |      1.983 |
|  50000 |              53.569 |               57.722 |      5.024 |
| 100000 |             105.369 |              117.575 |     10.678 |

tim_sort impelementation is faster than our qsort
