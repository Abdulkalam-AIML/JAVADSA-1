import java.util.*;
class Solution {
    public int[] twoSum(int[] nums, int target) {
    HashMap<Integer,Integer>s=new HashMap<>();
    for(int i=0;i<nums.length;i++){
        int c=nums[i];
        int cn=target-c;
        if(s.containsKey(cn)){
            return new int[] {s.get(cn),i};
        }
        s.put(c,i);
    }
    return new int[]{};

        
    }
}
