**数据库知识总结**
# Oracle与MySQl的区别？<br>
1.	Oracle没有offet，limit，在MySQL中分页用limit，Oracle中分页要换成rownum<br>
2.	Oracle建表时，没有自动递增，所以要自己创建序列，插入值时把序列的值插入进入<br>
3.	表中的字段类型不同MYSQL中的int，float合成Oracle中的Number类型<br>
4.	Oracle对单引号，双引号的要求的很死，一般不准用双引号用了会报错，MYSQL要求就不会那么严格<br>
5.	Oracle中有一个dual表 （伪表）<br>
