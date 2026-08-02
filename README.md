#include<stdio.h>
int main(){
  int are[4],i,n, element,pos, delete;
  printf("Enter the no.of elements:");
  scanf("%d",&n);
  printf("Enter the array elements:");
  for(i=0;i<n;i++){
  scanf("%d",&arr[i]);
  }
  printf("Enter the position of the  insert:");
  scanf("%d",&pos);
  printf("Enter the element to insert:");
  scanf("%d",& element);
  //shift the element to right side
  for(i=n;i>=pos;i--){
  arr[i]=arr[i-1];
  }
  // Insertion of the element 
  arr[pos-1]=element;
  n++;
  //Array after the insertion 
  printf("Enter the array elements:");
  for(i=0;i<4;i++){
  scanf("%d",& element);
  }
  //Deletion of the element 
  print("Enter the position of the delete:");
  scanf("%d",& delete);
  printf("Enter the element to delete:");
  arr[delete -1]=element;
  return 0;
  }
  
