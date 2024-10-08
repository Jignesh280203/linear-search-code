# linear-search-code
#include <iostream>
using namespace std;
int main() {
  int arr[] = {10,20,30,40,50,71,54};
  int target_element, i;
  cout<<"enter the value of target element"<<endl;
  cin>>target_element;
  for(i=0;i<=6;i++){
      if(arr[i]==target_element){
          cout<<"element found"<<endl;
          break;
      }
  }
  if(arr[i]!=target_element){
      cout<<"element not found";
  }

    return 0;
}
