class Solution {
    public int[] getConcatenation(int[] nums) {

        if(nums.length<1)
            return nums;

        int ans[]=new int[nums.length*2];

        for(int i=0;i<nums.length*2;i++){
            if(i<nums.length){
                ans[i]=nums[i];
            }else
            {
                ans[i]=nums[i-nums.length];
            }
        }
    return ans;
    }
}
