# zzmo
Mach-O ModifyTools

The system is not limited. It can be used after installing JDK
### Usage:
-o path [(optional parameter at the end) write to save path]

-f path [parse mach-o file]

-t path index [extract mach-o single schema index]

-r path libname index > [mach-o injection lib path name optional index (- 1 silent tail)]

-d path index [remove CMD instruction to remove index]

-md path index [modify CMD instruction dylib name address modify index]

不限制系统，安装JDK即可使用
### 用法:
-o path > [(末尾可选参数)写入保存路径]

-f path> [解析Mach-O文件]

-t path index> [提取Mach-O单架构 架构索引]

-r path libname index> [Mach-O注入 lib路径名 可选索引(-1默尾)]

-d path index [移除cmd指令 移除索引]

-md path index [修改cmd指令 DYLIB名称地址 修改索引]
