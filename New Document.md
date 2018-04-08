	```
		int* twoSum(int* nums, int numsSize, int target) {
			     int *p=(int*)malloc(2*sizeof(int));
			       for(int i=0;i<numsSize-1;i++){
			         for(int j=i+1;j<numsSize;j++){
			            if(nums[i]+nums[j]==target){
			                *p=i;
			                *(p+1)=j;
			            }
			             }
			    }
			    return p;
			}
	```