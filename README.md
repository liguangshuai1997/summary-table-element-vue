# summary-table-element-vue
vue+element做的表格计算总和显示在第一行
# 效果
![avatar](https://image-static.segmentfault.com/320/918/3209189978-5f1e3660cdd6c_articlex)

# 实现方法：
没有用饿了么的summary-method方法，因为这个方法只能添加在最后一行。我把summary-method提出来改了下，把方法返回的数组改成了和表格数据一样的key：value格式，然后用unshift插入到第一行。

