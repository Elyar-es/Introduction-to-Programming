**Optimal non-oblivious sorting.** Write a program that sorts 5 inputs using only 7 comparisons. Hint: First compare the first two numbers, the second two numbers, and the larger of the two groups, and label them so that a < b < d and c < d. Second, insert the remaining element e into its proper place in the chain a < b < d by first comparing against b, then either a or d depending on the outcome. Third, insert c into the proper place in the chain involving a, b, d, and e in the same manner that you inserted e (with the knowledge that c < d). This uses 3 (first step) + 2 (second step) + 2 (third step) = 7 comparisons. This method was first discovered by H. B. Demuth in 1956.