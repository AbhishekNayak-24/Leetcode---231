# Leetcode---231
Power of Two 
//code in java 
class Solution {
  public boolean isPowerOfTwo(int n) {
    return n >= 0 && Integer.bitCount(n) == 1;
  }
}
