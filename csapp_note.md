# 第一章：计算机系统漫游

1. 硬件：CPU，寄存器文件，高速缓存存储器，系统总线，主存，磁盘。

2. 操作系统管理硬件。进程（处理器，主存，i/o设备），虚拟内存（主存，i/o设备），文件（i/o设备）。

3. 并发运行：一个进程的指令和另一个进程的指令交错执行。这种交错执行的机制叫上下文切换，进程间切换由内核管理。

4. 上下文：操作系统保持跟踪进程运行所需的所有状态信息。

5. 内核：操作系统代码常驻主存的一部分，不是独立的进程。是系统全部进程所用代码和数据结构的集合。

6. 栈位于用户虚拟地址空间顶部，编译器用它来实现函数调用，和堆一样，用户栈在程序执行期间可以动态地扩展和收缩 。 调用函数时，栈会增长；从一个函数返回时，栈会收缩 。

7. 内核虚拟内存：程序无法读写，或调用内核代码定义的函数，需要调用内核来执行操作。
  
8. PC：程序计数器（寄存器），ALU（算数/逻辑单元）
