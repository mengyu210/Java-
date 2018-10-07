# Java<br>
# Java常用概念<br>
## 1、Java语言的优点<br>
   （1）简单性<br>
   （2）面向对象<br>
   （3）网络技能<br>
   （4）健壮性<br>
   （5）安全性<br>
   （6）体系结构中立<br>
   （7）可移植性<br>
   （8）解释性<br>
   （9）高性能<br>
## 2、字节码校验器验证那些内容<br>
   （1）代码和jvm规范是否一致<br>
   （2）代码不能破坏系统的完整性<br>
   （3）没有堆栈的上溢和下溢<br>
   （4）参数类型是否正确<br>
   （5）类型转换是否正确<br>
## 3、Java中的标识符<br>
   （1）必须以字母、下划线或者$开头，区别大小写<br>
   （2）由数字、字母、下划线、美元符号和人民币符号组成<br>
## 4、Java中8个基本类型<br>
   byte、short、int、long、boolean、char、double、float<br>
## 5、面向对象的七大设计原则<br>
   SOLID原则（单一职责原则、开放关闭原则、里氏替换原则、接口隔离原则和依赖倒置原则）<br>
   迪米特法则、组合优于继承原则（合成复用原则）<br>
## 6、&和&&的区别？<br>
   &运算符有两种用法：(1)按位与；(2)逻辑与<br>
   &&运算符是短路与运算<br>
## 7、接口和抽象类的区别是什么？<br>
   抽象是对类的抽象，是一种模板设计，接口是行为的抽象，是一种行为的规范<br>
   接口中所有的方法隐含的都是抽象的。而抽象类则可以同时包含抽象和非抽象的方法<br>
   类可以实现很多个接口，但是只能继承一个抽象类<br>
   Java接口中的成员函数默认是public的。抽象类的成员函数可以是private，protected或者是public。<br>
   Java接口中声明的变量默认都是final的。抽象类可以包含非final的变量。<br>
## 8、String和StringBuilder、StringBuffer的区别？<br>
   String：不可变字符串、String可以空赋值<br>
   StringBuffer：可变字符串、效率低、线程安全<br>
   StringBuilder：可变字符序列、效率高、线程不安全<br>
## 9、Iterator和ListIterator的区别是什么？<br>
   Iterator可用来遍历Set和List集合，但是ListIterator只能用来遍历List<br>
   Iterator对集合只能是前向遍历，ListIterator既可以前向也可以后向<br>
   ListIterator实现了Iterator接口，并包含其他的功能<br>
## 10、HashMap和Hashtable有什么区别？<br>
   1、HashMap是非线程安全的，HashTable是线程安全的。<br>
   2、HashMap的键和值都允许有null值存在，而HashTable则不行。<br>
   3、因为线程安全的问题，HashMap效率比HashTable的要高。<br>
   4、HashMap适合于单线程环境，而Hashtable适合于多线程环境（同步）。<br>
## 11、Array和ArrayList有何区别？什么时候更适合用Array？<br>
   Array可以容纳基本类型和对象，而ArrayList只能容纳对象。<br>
   Array是指定大小的，而ArrayList大小是固定的。<br>
## 12、ArrayList和Vector有何异同点<br>
   （1）两者都是基于索引的，内部由一个数组支持。<br>
   （2）两者维护插入的顺序，我们可以根据插入顺序来获取元素。<br>
   （3）ArrayList和Vector的迭代器实现都是fail-fast的。 <br>
   （4）ArrayList和Vector两者允许null值，也可以使用索引值对元素进行随机访问<br>
    不同点：<br>
   （1）Vector是同步的，而ArrayList不是<br>
   （2）ArrayList比Vector快，它因为有同步，不会过载。<br>
## 13、Switch能使用的参数类型<br>
   支持byte, short, char, int或者其对应的封装类以及Enum类型和String类型<br>
## 14、==和eqauls()的区别<br>
   ==是运算符、用于比较两个变量是否相等<br>
   equals是Object类的方法，用于比较两个对象是否相等、默认Object类的equals方法是比较两个对象的地址<br>
   基本类型比较用==，比较的是他们的值。对象用==比较时，比较的是内存地址，如果需要比较对象内容，需要重写equal方法比如String类<br>
## 15、LinkedList的是单向链表还是双向?<br>
   双向循环列表<br>
     




