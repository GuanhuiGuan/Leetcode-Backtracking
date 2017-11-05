# Leetcode-Backtracking

One sort of Greedy: try out all possibilities, walk through the tree; Searching for all suitable solutions

Basic Pseudocode:

Set up a helper;

Check if terminate(sublist size or sum or nothing and just return(all sizes));

Usually a loop through elements(Permutation: start from 0; Combination(subset): start from "start" past from parent structure;

Add one element -> iterate the subproblem -> minus the last added element

Permutation duplicate: used[k] != true && (k == 0 || nums[k] != nums[k - 1] || nums[k] == nums[k - 1] && used[k - 1] == true)

Combination duplicate: k == start || nums[k] != nums[k - 1]

Ref: https://discuss.leetcode.com/topic/46159/a-general-approach-to-backtracking-questions-in-java-subsets-permutations-combination-sum-palindrome-partitioning
