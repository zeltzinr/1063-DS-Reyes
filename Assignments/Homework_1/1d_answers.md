#include <iostream>
#include <ctime>

using namespace std;

int main()
{
// Number 1
  int a[] = {25, -3, 6, 0, -3, 6};
  int n = a[1];
  cout<<n<<endl;

// Answer: -3

//Number 2
int nn = 0;
for (int i=0; i<6; i++)
{
  if(a[i]<0)
  {
    nn++;
  }
}
cout<<"The amount of negative numbers is: "<<nn<<endl;

// Answer: The amount of negative numbers is: 2

// Number 3
int n3;
  for (int i=0; i<6; i++)
  {
    a[i] = a[i]+1;
  }
n3 = a[2];
cout<<"The third entry of a is now: "<<a[2]<<endl;

// Answer The third entry of a is now: 7

// Number 4
int n4 = 0;
  for (int i=0; i<5; i++)
  {
    for (int j=i+1; j<6; j++)
    {
      if (a[i] == a[j])
      {
         n4++;
      }
    }
  }
cout<<"Amount of repeated numbers: "<<n4<<endl;

// Answer Amount of repeated numbers: 2

// Number 5
int n5 = a[3]+1;
cout<<"n5 = "<<n5<<endl;
// Answer n5 = 1

// Number 6
int n6 = a[3+1];
cout<<"n6 = "<<n6<<endl;

// Answer n6 = -3

// Number 7
int n7 = a[3+1]+1;
cout<<"n7 = "<<n7<<endl;

// Answer n7 = -2

// Number 8
int n8 = a[3+1]+a[1];
cout<<"n8 = "<<n8<<endl;

// Answer n8 = -6

// Number 9
a[3+1] = a[3]+1;
cout<<"New array is: "<<a[0]<<" "<<a[1]<<" "<<a[2]<<" "<<a[3]<<" "<<a[4]<<" "<<a[5] <<endl;

// Answer New array is: 25 -3 6 0 1 6

// Number 10
a[3] = a[3]+a[1+3]*2;
cout<<"New array is: "<<a[0]<<" "<<a[1]<<" "<<a[2]<<" "<<a[3]<<" "<<a[4]<<" "<<a[5] <<endl;

// Answer New array is: 25 -3 6 2 1 6
}
