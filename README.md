# Codeforcescpp-265A
#include <bits/stdc++.h>
using namespace std;

int main() {
	string s,t;
  int count(0);
  cin >> s;
  cin >> t;
  for(int i=0;i<t.size();i++){
    if(t[i]==s[count]){
      count++;
    }
  }
  cout << count+1;
	return 0;
}
