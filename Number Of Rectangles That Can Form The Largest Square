class Solution {
    public int countGoodRectangles(int[][] rectangles) {
        int max = 0;
        int res = 0;
        for(int i = 0;i< rectangles.length;i++){
            int key = Math.min(rectangles[i][0],rectangles[i][1]);
            if(key > max){
                res = 1;
                max = key;
            }
            else if (key == max){
                res++;
            }
        }
        
        return res;
    }
}
