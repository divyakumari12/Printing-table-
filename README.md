# Printing-table-
#include <iostream>
using namespace std;
int main()
{
  int x;
  cin>>"Enter the number: ">>x;
  cout<<"here is the table of "<<x<<endl;
  for(int i=1; i<=10; i++)
  {
    cout<<x*i<<" ";
  }
