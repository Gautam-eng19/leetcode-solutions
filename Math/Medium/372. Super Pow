class Solution {
public:
    int mod = 1337;
    int power(int a , int b){
        int ans =1;
        a = a % mod;
        for(int i =0;i<b;i++){
            ans = (ans * a) % mod;
        }
        return ans;
    }

    int superPow(int a, vector<int>& b) {
        int ans = 1;
        for(int digit:b){
            ans = (power(ans,10) * power(a , digit)) % mod;
        }
        return ans;
    }
};