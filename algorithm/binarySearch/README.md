# 二分查找方法
算法描述：在一组有序数组中，将数组一分为二，将要查询的元素和分割点进行比较，分为三种情况
* 相等直接返回
* 元素大于分割点，在分割点右侧继续查找
* 元素小于分割点，在分割点左侧继续查找

时间复杂： **O(lgn)**.
## 要求
* 必须是有序的数组，并能支持随机访问