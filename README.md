
0x1B. C - Sorting algorithms & Big O
C
Algorithm
Data structure
 By: Alexandre Gautier
 Weight: 2
 Project to be done in teams of 2 people (your team: Uwiringiyimana Marthe)
 Ongoing second chance project - started Jul 20, 2023 6:00 AM, must end by Jul 30, 2023 6:00 AM
 An auto review will be launched at the deadline
In a nutshell…
Contribution: 100.0%
Auto QA review: 0.0/48 mandatory & 0.0/100 optional
Altogether:  0.0%
Mandatory: 0.0%
Optional: 0.0%
Contribution: 100.0%
Calculation:  100.0% * (0.0% + (0.0% * 0.0%) )  == 0.0%

   
2. Selection sort
mandatory
Score: 0.0% (Checks completed: 0.0%)



Write a function that sorts an array of integers in ascending order using the Selection sort algorithm

Prototype: void selection_sort(int *array, size_t size);
You’re expected to print the array after each time you swap two elements (See example below)
Write in the file 2-O, the big O notations of the time complexity of the Selection sort algorithm, with 1 notation per line:

in the best case
in the average case
in the worst case
alex@/tmp/sort$ cat 2-main.c
#include <stdio.h>
#include <stdlib.h>
#include "sort.h"

/**
 * main - Entry point
 *
 * Return: Always 0
 */



Write a function that sorts an array of integers in ascending order using the Quick sort algorithm

Prototype: void quick_sort(int *array, size_t size);
You must implement the Lomuto partition scheme.
The pivot should always be the last element of the partition being sorted.
You’re expected to print the array after each time you swap two elements (See example below)
Write in the file 3-O, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:

in the best case
in the average case
in the worst case
alex@/tmp/sort$ cat 3-main.c
#include <stdio.h>
#include <stdlib.h>
#include "sort.h"

   
Copyright © 2023 ALX, All rights reserved.