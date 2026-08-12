# Container With Most Water - Java

## Problem Statement

You are given an integer array `height`.

Each element represents the height of a vertical line.
Find two lines that together with the x-axis form a container
that can hold the maximum amount of water.

## Example

### Input

[1, 8, 6, 2, 5, 4, 8, 3, 7]

### Output

49

## Explanation

The maximum amount of water that can be stored is 49.

The two lines with heights 8 and 7 provide the maximum area.

Area is calculated as:

Area = Width × Minimum Height

Area = 7 × 7

Area = 49

## Approach

This solution uses the Two Pointer technique.

1. Place the `left` pointer at the beginning.
2. Place the `right` pointer at the end.
3. Calculate the area between the two pointers.
4. Store the maximum area.
5. Move the pointer with the smaller height.
6. Continue until the two pointers meet.

Moving the smaller height is important because the smaller height
limits the amount of water that can be stored.

## Complexity

- Time Complexity: O(n)
- Space Complexity: O(1)

## Language

Java

## Author

M. Pallavi
