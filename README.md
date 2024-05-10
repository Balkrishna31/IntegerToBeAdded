# IntegerToBeAdded
class Solution {
public:
    int addedInteger(vector<int>& nums1, vector<int>& nums2) {
        int max1=nums1[0];
        int max2=nums2[0];
        int n=nums1.size();
        for(int i=0; i<n; i++)
        {
              if(nums1[i]>max1)
                 max1=nums1[i];
               if(nums2[i]>max2)
                 max2=nums2[i];             
        }
        int X=max2-max1;
        return X;
    }
};
