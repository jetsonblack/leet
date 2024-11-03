
class Solution(object):
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
        "SOLUTION"
        
        matches = {}
        for index, number in enumerate(nums):
            comp = target - number
            if comp in matches:
                return [matches[comp], index]
            else:
                matches[num] = i
            return []

        "RUNTIME"
        # 12.35MB of mem, 0ms runtime
        "NOTES"
        # enumerate(array): stores both the index and value, for example this has stores the index in 'index'
        # and the value in the number variable
        # dictionary/map{}: python's dynamic dictionary that acts like a set or a hashmap/dictionary depending on data
            # my_set = {1,2,3}
            # my_dict = {'a':1, 'b':2}

