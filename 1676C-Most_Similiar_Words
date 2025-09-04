#include <bits/stdc++.h>
using namespace std;

int main(){
    ios::sync_with_stdio(false); cin.tie(NULL);
    int t; cin >> t;
    while(t--){
        int n, m, ans = INT_MAX; cin >> n >> m;
        string s[n];
        for(int i = 0; i < n; i++) cin >> s[i];
        for(int i = 0; i < n; i++){
            for(int j = i + 1; j < n; j++){
                int diff = 0;
                for(int k = 0; k < m; k++){
                    diff += abs(s[i][k] - s[j][k]);
                }
                ans = min(ans, diff);
            }
        }
        cout << ans << "\n";
    }
}
