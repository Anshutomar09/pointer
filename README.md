# pointer

#include <iostream>

using namespace std;

int main()
{
    double num=10;
    double *ptr= &num;
    cout<<"size of : "<<sizeof(num)<<endl;
    cout<<"address : "<<ptr<<endl;
    cout<<"value: "<<*ptr<<endl;
    (*ptr)++;
    cout<<"after"<<num<<endl;
     cout<<"before"<<ptr<<endl;
    ptr=ptr+1;
    cout<<"after"<<ptr<<endl;
    return 0;
}
