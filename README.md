# Leetcode

C++ 

data structure 

s.find(nums[i])：
s.find(element) 是 unordered_set 提供的一個方法，用來在集合中查找指定的 element。
如果 element 存在於集合中，find 方法會返回一個指向該元素的迭代器。如果 element 不存在，則返回一個指向集合末尾的迭代器，即 s.end()。

使用的資料結構：
unordered_set<int> s: 使用了一個無序集合（unordered_set）來儲存已經遇到的數字。無序集合具有 O(1) 的平均查找時間複雜度，因此適合用來檢查是否存在某個元素。
