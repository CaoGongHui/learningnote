
编译时 添加-g参数
gcc -g demo.c -o demo

调试时添加-tui参数可以可视化调试

gdb demo -tui

break line: 对应行号添加断点
run args: 运行程序(args是参数)
c: 继续
p:打印