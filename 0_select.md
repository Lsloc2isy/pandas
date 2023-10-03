# 条件筛选
* 最常见的两个筛选运算符 & | 但是要注意在条件之间用（）进行分隔
* .isin()方法筛选某个属性在另外的表中出现的所在记录，常和~取反符号一起使用
* .rename(columns={'old':'new'})将属性改名
* .drop_duplicates(['column',replace=True])删除重复列,replace=True表示原地操作，否则不改变原二维表
* .sort_values(by=['column1','column2'],replace=True,ascending=True)按照by中的字段先后顺序排列，ascending=True则表示按升序排列反之降序
