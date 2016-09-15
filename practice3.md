## HARD

### Burst Balloons

Given n balloons, indexed from 0 to n-1. Each balloon is painted with a number on it represented by array nums. You are asked to burst all the balloons. If the you burst balloon i you will get nums[left] * nums[i] * nums[right] coins. Here left and right are adjacent indices of i. After the burst, the left and right then becomes adjacent.

Find the maximum coins you can collect by bursting the balloons wisely.

`Note`:
 
(1) You may imagine nums[-1] = nums[n] = 1. They are not real therefore you can not burst them.

(2) 0 ≤ n ≤ 500, 0 ≤ nums[i] ≤ 100

`Example`:

Given [3, 1, 5, 8]

Return 167

``` sh
    nums = [3,1,5,8] --> [3,5,8] -->   [3,8]   -->  [8]  --> []
   coins =  3*1*5      +  3*5*8    +  1*3*8      + 1*8*1   = 167

```   

What's your solution?

``` sh
public class Solution {
    public int maxCoins(int[] nums) {
        
    }
}

```

### Distinct Subsequences
Given a string **S** and a string **T**, count the number of distinct subsequences of **T** in **S**.

A subsequence of a string is a new string which is formed from the original string by deleting some (can be none) of the characters without disturbing the relative positions of the remaining characters. (ie, **"ACE"** is a subsequence of **"ABCDE"** while **"AEC"** is not).

Here is an example:
S = **"rabbbit"**, T = **"rabbit"**

Return **3**.

What's your solution?

``` sh
public class Solution {
    public int numDistinct(String s, String t) {
        
    }
}

```


### Russian Doll Envelopes

You have a number of envelopes with widths and heights given as a pair of integers (w, h). One envelope can fit into another if and only if both the width and height of one envelope is greater than the width and height of the other envelope.

What is the maximum number of envelopes can you Russian doll? (put one inside other)


`Example`:

Given envelopes = [[5,4],[6,4],[6,7],[2,3]], the maximum number of envelopes you can Russian doll is 3 ([2,3] => [5,4] => [6,7]).

What's your solution?

``` sh

public class Solution {
    public int maxEnvelopes(int[][] envelopes) {
        
    }
}

```