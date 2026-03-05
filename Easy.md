# RemoveDuplicates
I did an easy code for removing duplicates in an array. <br/>
---------------------
public class Solution {
    public int RemoveDuplicates(int[] nums) {
        
     int writeIndex = 1;
         
        for(int i = 1; i < nums.Length; i++)
        {
           if(nums[i] != nums[i-1])
           {
               nums[writeIndex] = nums[i];
               writeIndex++;
           }
        
        }
        
        return writeIndex;
    
    }
}
---------------

