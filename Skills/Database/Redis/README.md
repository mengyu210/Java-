**Redis非关系型数据库**
# Redis基本知识点<br>
## Redis定义<br>
   Redis是一个开源的key—value型数据库<br>
## Redis支持存储的数据类型<br>
   String、List、set、zset、Hash<br>
## Redis基础知识<br>
   1、端口：6379<br>
   2、默认16个数据库，下标从0开始<br>
   3、单线程：Redis是单线程+IO多路复用<br>
## 常见的面试问题<br>
   1、使用Redis有哪些好处？<br>
      （1）速度快，数据存在内存<br>
      （2）支持丰富的数据类型<br>
      （3）支持事务<br>
      （4）丰富的特性：可用于缓存，消息，按key设置过期时间，过期后将会自动删除<br>
   2、redis相比memcached有哪些优势？<br>
       (1) memcached所有的值均是简单的字符串，redis作为其替代者，支持更为丰富的数据类型<br>
       (2) redis的速度比memcached快很多<br>
       (3) redis可以持久化其数据<br>


# Redis使用场景<br>
   1、数据高并发的读写<br>
   2、海量数据的读写<br>
   3、对扩展性要求高的数据<br>
   作用如下：<br>
   配合关系型数据库做高速缓存<br>
   缓存高频次访问的数据，降低数据库IO<br>
   分布式架构做session共享<br>
   可以持久化特定数据<br>
   利用zset类型可以存储排行榜<br>
   利用list的自然时间排序存储最新n个数据<br>
   
   详细-->[https://blog.csdn.net/u011277123/article/details/78692603](https://blog.csdn.net/u011277123/article/details/78692603)<br>


  
