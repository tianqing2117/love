# linux 命令

### wc (Word Count)
- 命令格式：`wc [选项] 文件...`
- 功能：为统计指定文件中的字节数、字数、行数，并将统计结果显示输出。如果没有给出文件名，则从标准输入读取。wc同时也给出所指定文件的总统计数。
- 参数说明：     
    -c 统计字节数;       
    -l 统计行数;        
    -m 统计字符数。这个标志不能与 -c 标志一起使用;     
    -w 统计字数。一个字被定义为由空白、跳格或换行字符分隔的字符串;       
    -L 打印最长行的长度;        
    -help 显示帮助信息;       
    --version 显示版本信息.       
- 示例：
``` 
pstree -p PID | wc -l //查看指定 PID 进程的线程数
```

