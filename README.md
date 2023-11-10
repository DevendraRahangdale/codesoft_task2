# codesoft_task2

#include<iostream>
using namespace std;

void print(int n){
    cout<<"==========**********============"<<endl;
cout<<"==========**********============";
cout<<endl;
cout<<"     CALCULATOR"<<endl;

cout<<"==========**********============"<<endl;
cout<<"==========**********============";
cout<<endl;
}

int main()

{ 
    int n;
print(n);

    float a,b;
    cout<<"enter value of n1 and n2:";
    cin>>a>>b;
    char op;

    cout<<"[+   ,  -   ,   *  ,  /   ]"<<endl;


    cout<<"enter operator:";
    cin>>op;

    switch(op)
    {
    case '+':
    cout<<a+b<<endl;
    break;
    case '-':
    cout<<a-b<<endl;
    break;
    case '*':
    cout<<a*b<<endl;
    break;
    case '/':
    cout<<a/b<<endl;
    break;
    default:
    cout<<"enter proprer operator"<<endl;


   } 
   cout<<"enter 1 for continue"<<endl;
   cout<<"enter 0 for exit"<<endl;

   int choice;
   cin>>choice;
   if(choice==1){
        main();
        }
        else {
            exit;
        }
   return 0;

}
