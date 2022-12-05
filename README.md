# SORT_AN_ARRAY_OF_0_1_2




// SORT AN ARRAY OF 0,1,2'S............
#include <iostream>
class solution{
public:
  void sortColors(vector<int>&nums){
      int lo=0;
      int high=nums.size()-1;
      int mid=0;
      
      while(mid<=high){
      switch(nums[mid]){
              case 0:
              swap(a[lo++], a[mid++]);
              break;
              
              case 1:
              mid++;
              break;
              
              case 2:
              swap(num[mid], num[high--]);
              break;
          }
      }
  }
    
};
