stack-memory-playground
=======================
![](./godbolt.jpg)
### Notes
- The address direction (High to low / low to high) is different for linux and Windows
- ```
  Push the value of EBP onto the stack, and then copy the value of ESP into EBP using the following instructions:
    push ebp # preserve previous
    mov  ebp, esp #
  ```
- Use coding to get memory layout
  - [从C++取地址操作看对象内存布局 - 与MPI做斗争 - 博客园](https://www.cnblogs.com/zhcpku/p/16362695.html)

### Tutorials
- [A - Z Nasm Assembly 64Bit Programming - Loop, Stack, prinf, scanf, conditions - YouTube](https://www.youtube.com/watch?v=5eWiz3soaEM)
- [The Call Stack - YouTube](https://www.youtube.com/watch?v=Q2sFmqvpBe0)
- [Stack Memory: An Overview (Part 3)](https://www.varonis.com/blog/stack-memory-3)
- [CS 225 | Stack and Heap Memory](https://courses.grainger.illinois.edu/cs225/sp2023/resources/stack-heap/)
- [L12: Procedures and Stacks](https://computationstructures.org/lectures/stacks/stacks.html)
