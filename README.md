#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

//Complete the following function

int marks_summation(int* marks, int number_of_students, char gender) {
  int sum=0;
  if(gender=='b')
  {
      for(int i=0;i<number_of_students;i=i+2)
      sum=sum+marks[i];
  }
  else{
      for(int i=1;i<number_of_students;i=i+2)
      sum=sum+marks[i];
  }
  return(sum);
}

int main() {

Input (stdin)

Download
3
3
2
5
b
Your Output (stdout)
8
Expected Output

Download
8
