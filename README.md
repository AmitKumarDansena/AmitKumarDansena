#include<iostream>
#include<conio.h>
using namespace std;
class length1
{
int a;
int temp;

public:
	int count=0;
length1()
{
}
length1(int a)//6789.4
{
 temp = a;
    
    while(temp != 0) {

        // Increment counter
        count++;

        // Remove last digit of 'temp'
        temp /= 10;
    }
}
void display()
{
cout<<"Count of digit"<<count;
};

};
int main()
{
length1 l1;
float integer;
cout<<"Enter the integer";
cin>>integer;
l1=integer;
l1.display();
return 0;
}
