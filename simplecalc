#include<iostream>
using namespace std;
class calculator
{
   public:
   int opt=1;
   float a,b;

   int option();
   int addition();
   int subtraction();
   int multiplication();
   int division();

};

int calculator::option()
{
  while(opt==1)
  {
    cout<<"1: ADDITION \n";
    cout<<"2: SUBTRACTION \n";
    cout<<"3: MULTIPLICATION \n";
    cout<<"4: DIVISION \n";
    
    cout<<"ENTER YOUR CHOICE \n";
    cin>>opt;
    //cout<<opt;    
    switch(opt)
    {
       case 1: addition();
       break;

       case 2: subtraction();
       break;

       case 3: multiplication();	       
       break;

       case 4: division();
       break;	       

       default: cout<<"INVALID CHOICE\n";	       
    }
       cout<<"CONTINUE [TYPE 0 OR 1]";
       cin>>opt;
       //cout<<opt; 
  }	  
  return 0;
}

int calculator::addition()
{
  cout<<"ENTER ANY TWO VALUE \n";	
  cin>>a>>b;
  //cout<<a<<b;
  
  cout<<"SUM = "<<a+b<<endl;
  return 0;
}

int calculator::subtraction()
{
  cout<<"ENTER ANY TWO VALUE \n";
  cin>>a>>b;
  //cout<<a<<b;

  cout<<"DIFF = "<<a-b<<endl;
  return 0;
}	

int calculator::multiplication()
{
  cout<<"ENTER ANY TWO VALUE \n";
  cin>>a>>b;
  //cout<<a<<b;
  cout<<"PRODUCT = "<<a*b<<endl;
  return 0;
}

int calculator::division()
{
  cout<<"ENTER ANY TWO VALUE \n";
  cin>>a>>b;
  //cout<<a<<b;
  if(b!=0)
  {	  
   cout<<"QUOTIENT = "<<a/b<<endl;
  }
  else
  {
   cout<<"ERROR: cannot be divided by zero";	  
  }
  return 0;
	
}

int main()
{
  calculator obj;
  obj.option();
  return 0;
}
