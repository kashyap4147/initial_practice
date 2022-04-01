# initial_practice
Basic C++ projects for understanding basic concepts.

#include<iostream>
using namespace std;


int main(){
 int num;
 int check=0;
 cin>>num;
for(int i=2;i<num;i++){
   if(num%i==0){
    check++;
    break;
   }
  
}
if(num==1)
  cout<<"Neither prime nor composite";
else if(check==0)
  cout<<"prime";
else 
      cout<<" not Prime";

  	
	  

return 0;	
	
}


	
	
