#include<bits/stdc++.h>
using namespace std;
int main() {
	int n, f[101], a,x;
	cin >> n;
	for (int i = 1; i <= n; ++i) cin >> f[i];
	cin >> a;
	x = a;
	for(int i=1;i<=n;++i){
		cout << x << ' ';
		x = f[x];
	}
}
