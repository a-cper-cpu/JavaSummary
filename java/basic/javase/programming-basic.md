### 概论

​	计算机是个机器，这个机器主要由CPU、内存、硬盘和输入/输出设备组成。计算机上跑着操作系统，如Windows或Linux，操作系统上运行着各种应用程序，如eclipse、IDEA等。

​	应用程序看上去能做很多事情，比如能读写文档、能听音乐、能聊天等，但本质上，计算机只会执行预先写好的指令，这些指令也只是操作数据或者设备。

##### 	所谓程序，基本上就是告诉计算机要操作的数据和执行的指令序列，即对什么数据做什么操作。

​	**读/写文档**：读文档，就是将数据从磁盘加载到内存，然后输出到显示器上；写文档，就是将数据从内存写回磁盘；就是将数据从内存写回磁盘；

​	**听音乐**：就是将音乐的数据加载到内存，然后写到声卡上；

​	 **聊天**：就是从键盘接收聊天数据，放到内存，然后传给网卡，通过网络传给另一个人的网卡，再从网卡传到内存，显示在显示器上。



### 数据类型

​		Java中的数据类型分为两大类，**基本数据类型**和**引用数据类型**。

#### 		基本数据类型：

​			 	**整数类型**：有4种整型byte/short/int/long，分别有不同的取值范围；

​						byte：1字节

​						short：2字节

​						int：4字节

​						long：8字节

​			    **浮点类型**：有两种类型float/double，有不同的取值范围和精度；

​						float：4字节

​						double：8字节

​				**字符类型**：char，2字节

​				**布尔类型**：boolean，true或false

#### 		引用数据类型

​			 引用数据类型包括**数组、接口、类**。



### 变量

​	变量其本质就是指向某块内存空间所在的位置，那块内存空间就存放数据，之所以叫“变”量，是因为这个位置存放的值是可以变化的。

​	一般情况下变量的值可变，但其含义不应该变，如定义一个age变量，age可以是30也可以40，但age表示年龄这个含义不变。

​	为变量应该赋予一个数据类型和一个有意义的名字。

#### 	对变量的操作

##### 			赋值

​				声明变量之后，就在内存分配了一块位置，但这个位置的内容是未知的，赋值就是把这块位置的内容设为一个确定的值，如 int age = 23；

​			 **对基本数据类型的赋值操作**

​					**long**：在给long类型赋值时，如果常量超过了int的表示范围，需要在常量后面加大写或小写字母L，即L或l，之所以需要加L或l，是因为数字常量默认为是int类型。

​					**float**：在给float类型赋值时，需要在数字后面加大写字母F或小写字母f

​						

​							

​							

