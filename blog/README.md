# DSA

DSA（Data structure Algorithm），数据结构与算法对写出一个高性能的程序至关重要。回想在以往的开发中，为什么会有如此多的 Bug，因为一直在写 Bug。想想为什么会有那么多 Bug。一个合理的数据结构，一个合适的算法或许能帮到你。

## 数据结构

### 线性表

线性表是一种最常用的数据结构，它是包含很多数据节点的序列，它包含一个头和一个尾。比如常见的有**栈**，**队列**

链表是由数据节点组成的一个序列，它就像一个数组，数组是同时申请一块连线的内存空间来存储数据，而链表是使用指针把分散的数据连接起来的一个序列。

**单链表**

其中数据段被称为节点（Node），每个节点仅仅有一个指针来连接下一个节点。

	+--------+    +--------+    +--------+    +--------+
	|        |    |        |    |        |    |        |
	| node 0 |--->| node 1 |--->| node 2 |--->| node 3 |
	|        |    |        |    |        |    |        |
	+--------+    +--------+    +--------+    +--------+

**双向链表**

它含有一个指向上一个节点的指针和下一个节点的指针。

	+--------+    +--------+    +--------+    +--------+
	|        |--->|        |--->|        |--->|        |
	| node 0 |    | node 1 |    | node 2 |    | node 3 |
	|        |<---|        |<---|        |<---|        |
	+--------+    +--------+    +--------+    +--------+
	
通常需要一个头节点 **head** 来记录链表的第一个节点，一个尾节点 **tail** 指向最后一个节点。

	         +--------+    +--------+    +--------+    +--------+
	head --->|        |--->|        |--->|        |--->|        |---> nil
	         | node 0 |    | node 1 |    | node 2 |    | node 3 |
	 nil <---|        |<---|        |<---|        |<---|        |<--- tail
	         +--------+    +--------+    +--------+    +--------+

## 算法

- 快速排序
- 冒泡排序


## 参考

- [VisuAlgo](https://visualgo.net/en/hashtable?slide=1)