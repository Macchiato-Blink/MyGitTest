# 笔记

1. sparksql列可以是集合(暂时只用到了list)可以利用$“列名”(下标)获取然后自成一列
2.  saprksql的explode方法可以与withcolumn结合循环遍历某一列的集合生成一个新列
3. sparksql拥有窗口函数(包括具体的分析函数等)便于计算指标

4. sparksession和sparkcontext用过之后一定要stop不然广播变量等有可能存在缓存一定要注意！