### 子表
在日常工作中，一个主表单里面通常还会嵌套另一个表格，我们称之为“子表”。子表的作用类似于明细表，它拥有多行数据，且字段名都是相同的，用户在填写表单时，可以输入任意多行数据。以“日常报销申请单”为例，报销明细就是子表。

##### 子表添加的方式如下：
- 设计表单时，选择“添加字段”下的表格
- 选中表格，“属性”的描述中输入“报销明细”
- 在该表格中添加不同的字段，比如增加下拉框“报销类别”，输入办公用品、交通费等选项
- 添加数值字段“报销金额”,添加日期字段“费用产生日期”
 
 这样，用户在填写日常报销申请单时，点击“+”就会出现“报销类别”“报销金额”“费用产生日期”三个字段，填写完内容后，子表中会出现这一条记录，再点击“+”，输入一行数据，重复操作，可以将每一笔报销的费用都输入到表格中。
