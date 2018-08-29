#include<iostream>
using namespace std;

int main(){
int i,num,j,multiple;
bool result;
result=true;
  cout<<"Please Enter an integer\n";
  cin>>num;
          for(i=2; i<num; i++){
                for(j=2; j<num; j++){ multiple=i*j;
                     if(multiple==num){ 
                  result=false; break;}
         }
     }
   if(result==false)
   cout<<num<<" is integer not prime\n";
     else cout<<num<<" is a prime\n";
            return 0;
}
               
