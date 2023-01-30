# ARRAY-DELETION-FROM-ANY-PLACE
Here i had provided you the code that how to delete any element weather from beginning ending or from the middle .JUST FOLLOW THE CODE. !!


#include<iostream>
#include<conio.h>
using namespace std;
class A
{
    public:
    void func()
    {
        int pos,i;
        
        int arr[7]={1,2,3,4,5};
        int size=sizeof(arr)/sizeof(arr[0]);
        cout<<"the elements of the array are "<<endl;
        for(i=0;i<5;i++)
        cout<<arr[i]<<endl;
        cout<<"enter the position"<<endl;
        cin>>pos;
        for(i=pos-1;i<size;i++)
        {
            arr[i]=arr[i+1];
            size=size-1;
            
        }
        cout<<"elements after deletion are"<<endl;
        for(i=0;i<size;i++)
        cout<<arr[i]<<endl;
    }
};
int main()
{
    A obj;
    obj.func();
    return 0;
}
  //PLEASE DROP A STAR !!
