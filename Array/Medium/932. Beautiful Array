#include <bits/stdc++.h>
using namespace std;

class Solution {
public:
    vector<int> beautifulArray(int n) {
        if (n == 1)
            return {1};

        vector<int> prev = beautifulArray((n + 1) / 2);

        vector<int> ans;

        for (int x : prev) {
            if (2 * x - 1 <= n)
                ans.push_back(2 * x - 1);
        }

        for (int x : prev) {
            if (2 * x <= n)
                ans.push_back(2 * x);
        }

        return ans;
    }
};