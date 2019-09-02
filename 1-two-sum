class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        dict1={}
        for i,m in enumerate(nums):
            j=dict1.get(target-m)
            if j is not None and (j!=i):
                return [j,i]
            dict1[m]=i
