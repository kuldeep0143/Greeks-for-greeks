class Solution {
    long[] countZero(int n, int k, int[][] arr){
        // code here
        int row [] = new int[n+1];
        int col [] = new int[n+1];
        long ans [] = new long[k];
        long oneR = 0;
        long oneC = 0;
        for(int i=0;i<k;i++){
            int r = arr[i][0];
            if(row[r]==0){
                row[r]++;
                oneR++;
            }
            int c = arr[i][1];
            if(col[c]==0){
                col[c]++;
                oneC++;
            }
            ans[i] = (long)n*(long)n -(long)n*(oneR+oneC)+(oneR*oneC);
        }
        return ans;
    }
}
