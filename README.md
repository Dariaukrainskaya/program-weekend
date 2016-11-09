# program-weekend
#include <iostream>

using namespace std;

int main()
{
  setlocale(0,"");
  int a,b,c,n,k;

  cin >> a;
  cout << "\n";
  
  cin >> b;    
  cout << "\n";
  k = a*b;
  while(b != 0)  
  {
    c = a % b;
      a = b;
      b = c;
  }
  cout << a;
  cout << "\n";
  n = k/a;
  cout << n;  
  return 0;
}
