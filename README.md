# 数据结构复习阶段典型题目

 - 代码是自己写的，因此有一些题目跟书上或者网上答案不一样，请谅解。 
 - 在答案或算法的重点难点中加了详尽的注释。
 - 当前正在完成的是数据结构高分笔记题目。之后会有天勤DS和其他一些经典题目。后续也会写一些经典DS相关的OJ题目。
 - 保证每一题是自己思考得出的结果。不敷衍，不将就。
 - 此项目为个人所用，不代表标准答案，不承担内容错误造成的损失。若有人关注或看到错误，欢迎及时pr，感谢。
 - 三跨考生，本科教育。编程经验一年半，现辞职考研中。考研相关交流请加qq：632176758

>项目开始时间：2017.2.17

---

###第二章 线性表

 1. 链表基本操作--[LinkedList][1]
 2. 双链表基本操作--[DoubleLinkedList][2]
 3. 真题模拟：
    设顺序表用数组A[]表示,表中元素存储在数组下表1~m+n的范围内，前m个元素递增有序，后n个元素也递增有序，设计算法使整个顺序表有序--[FakeQuestions][3]
 4. Codeup-1323：集合union--[CodeUp-1323][4]
 5. Codeup-1324：有序线性表的有序合并--[Codeup-1324][5]
 6. Codeup-1329：一元多项式加法--[Codeup-1329][6]
 7. Practice-1-(5)：
  （快速排序）将顺序表L中所有小于表头元素的整数放在前半部分，大于表头元素的整数放在后半部分--[Practice-1-(5)][7]
 8. OldExam-1：
  已知一个带表头结点的单链表，假设该链表只给出了头结点head。在不改变链表的前提下，请设计一个尽可能搞笑的算法，查找链表中倒数第k个位置上的结点。若查找成功，输出该结点的data，返回1，否则返回0--[OldExam-1][8]
 9. OldExam-2：
 将个数为n的数组R的元素向右平移p个--[OldExam-2][9]
 10. OldExam-3：
 找出数量为n的数组A中的主元素（元素数量大于n/2）--[OldExam-3][10]

###第三章 栈、队列和数组

 1.  判断一个表达式中的小括号是否正确配对--[Exam3-1][11]
 2.  后缀式计算函数--[Exam3-2][12]
 3.  共享栈操作--[FakeQuestion-1][13]
 4.  Codeup-1330： 将十进制数转化为八进制数--[Codeup-1330][14]
 5.  Practice-2-(1)： 递归求n个不同字符的全排列--[Practice-2-(1)][15]

###第四章 串

 1. KMP算法及其优化--[KMP][16]

###第五章 数组、稀疏矩阵与广义表

 1. Practice-2：数组递归的几个练习（和、最大值、平均数）--[Practice-2][17]

###第六章 树与二叉树

 1. LevelTraversal：树的层次遍历（循环队列）--[LevelTraversal][18]
 2. Example-6-5：求二叉树的宽度（层次遍历+队列）--[Example-6-5][19]
 3. BinaryThreadTree：线索二叉树的线索化和遍历--[BinaryThreadTree][20]
 4. FakeQ-2：根据先序遍历和中序遍历递归构建二叉树--[FakeQ-2][21]
 5. Practice-1-3：计算叶子结点个数，遍历和左右递归两种方法--[Practice-1-3][22]
 6. Practice-1-4：将叶子结点链接成链表--[Practice-1-4][23]
 7. Practice-1-5：遍历二叉树，设置双亲， 输出某结点到根结点的路径--[Practice-1-5][24]
 8. Practice-1-6：将完全二叉树的先序遍历转化为后序遍历，此处操作同一数组--[Practice-1-6][25]
 9. Practice-1-7：找到值为x的结点的层号，一种层次遍历方法，一种记录指针上下游走方法--[Practice-1-7][26]
 10. Practice-1-10：双序遍历（好像没啥卵用）--[Practice-1-10][27]
 11. Practice-2-1：输出根结点到每个叶子结点的路径--[Practice-2-1][28]
 12. Practice-2-3：二叉树的非递归遍历，先序和中序--[Practice-2-3][29] **（此处应扩展非递归后序遍历，抽空补上）**
  
  [1]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/LinkedList.cpp
  [2]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/DoubleLinkedList.cpp
  [3]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/FakeQuestions.cpp
  [4]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/Codeup-1323.cpp
  [5]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/Codeup-1324.cpp
  [6]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/Codeup-1329.cpp
  [7]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/Practice-1-%285%29.cpp
  [8]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/OldExam-1.cpp
  [9]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/OldExam-2.cpp
  [10]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/LinearList/OldExam-3.cpp
  [11]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/StackQueueArray/Exam3-1.cpp
  [12]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/StackQueueArray/Exam3-2.cpp
  [13]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/StackQueueArray/FakeQuestion-1.cpp
  [14]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/StackQueueArray/Codeup-1330.cpp
  [15]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/StackQueueArray/Practice-2-%281%29.cpp
  [16]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/String/KMP.cpp
  [17]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/LinearList/ArraySMGTB/Practice-2.cpp
  [18]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/LevelTraversal.cpp
  [19]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/Example-6-5.cpp
  [20]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/BinaryThreadTree.cpp
  [21]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/FakeQ-2.cpp
  [22]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/Practice-1-3.cpp
  [23]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/Practice-1-4.cpp
  [24]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/Practice-1-5.cpp
  [25]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/Practice-1-6.cpp
  [26]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/Practice-1-7.cpp
  [27]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/Practice-1-10.cpp
  [28]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/Practice-2-1.cpp
  [29]: https://github.com/lfny2580832/Data_Structure/blob/master/GFBJ/Tree/Tree/Practice-2-3.cpp
