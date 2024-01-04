## 强引用，软引用，弱引用，虚引用
[软引用、弱引用、虚引用-他们的特点及应用场景](https://www.jianshu.com/p/825cca41d962)</br>
[Android中的四种引用及其使用场景](https://juejin.cn/post/6844903959065264142)</br>
![强引用弱引用对比图](https://github.com/jinguangyue/Android-Advanced-Interview/assets/8803674/d0595e9a-dc30-4a91-b83e-734429f35086)
![image](https://github.com/jinguangyue/Android-Advanced-Interview/assets/8803674/f6dd8d22-1a9e-46b5-a28a-7440f73e218b)


## 生产者消费者模式相关
[Java生产者、消费者模式的几种实现方式](https://mp.weixin.qq.com/s/aVaO5VZSoPSdZFEit6jrwQ)</br>

## java 多线程相关
[史上最全 Java 多线程面试题及答案](https://mp.weixin.qq.com/s/0CI9od4DIxRrmOGFJw0SuQ)</br>

## 字节码讲解
[字节码在虚拟机的执行逻辑](https://www.51cto.com/article/705265.html)</br>

## ==和equals()

在Java中，==和equals()在基本类型上的比较有一些不同之处。

==操作符：

对于基本数据类型（如int、double等），==用于比较它们的值是否相等。
对于引用类型，==比较的是对象的引用是否相同，即它们是否指向同一个内存地址。
equals()方法：

equals()是Object类中的方法，被许多类（包括基本数据类型的包装类如Integer、Double等）重写。
对于基本数据类型的包装类，equals()比较的是对象的值是否相等，而不是引用是否相同。例如，new Integer(5).equals(new Integer(5))返回true。
注意：在使用equals()之前，需要确保对象不是null，否则会抛出NullPointerException。

## 浅拷贝 & 深拷贝
浅拷贝：如果字段是引用类型，复制的是引用而不是引用指向的对象。
深拷贝：新对象和原对象的引用类型字段引用的是不同的对象实例，因此它们之间是独立的。需要实现Serializable
