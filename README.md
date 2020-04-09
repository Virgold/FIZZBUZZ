# FIZZBUZZ PROGRAM
#include <iostream>

int main(){
  
  //Brain explodes here:
  std::cout<<"\t================\t\n\t~~~~FIZZBUZZ~~~~\t\n\t================\t\n";
  
  for (int i = 1;i <= 100; i++){
    
    /*we will write the code here with the 
     the condition statement for the code*/
  if (i%3!=0&&i%5!=0){
      std::cout<<i<<"\n";
    }
    
  else if (i%3==0&&i%5==0){
    std::cout<<"FizzBuzz\n";
  }
    
 else if (i%3==0){
   std::cout<<"Fizz\n";
 }
   
  else if (i%5==0){
    std::cout<<"Buzz\n"; 
  }
  
  }
  return 0;
}
