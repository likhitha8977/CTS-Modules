# SQL Exercise 1 - Ranking and Window Functions

## Objective

The objective of this exercise is to understand SQL Window Functions used for ranking and grouping records.

## Topics Covered

- OVER()
- PARTITION BY
- ROW_NUMBER()
- RANK()
- DENSE_RANK()

## Description

ROW_NUMBER() assigns a unique number to every row.

RANK() assigns the same rank for duplicate values but skips the next rank.

DENSE_RANK() assigns the same rank for duplicate values without skipping ranks.

PARTITION BY divides the data into groups before applying ranking.

OVER() specifies how the ranking operation should be performed.

## Output

The queries rank products based on their prices and also rank products within each category.

## Conclusion

Window functions make SQL queries more powerful by allowing ranking and partitioning without changing the original data.