in this process
######
可以实现对多进程文件的拷贝，但是在process_wait.c中的代码感觉并未执行。
在运行时日志并没有看到process_wait.c中printf的信息，同时运行另一个终端，并没找到父进程以及n个子进程，推断所有进程正常结束。
