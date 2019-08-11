# 其他使用命令

### 1、type命令-显示命令的类型
````aidl
type ls
type cp
````
### 2、which显示可执行程序的位置
````aidl
which ls
````
### 3、help-获取shell内置脚本的帮助文档
````aidl
help cd
cd --help显示命令的帮助行
````
### 4、man显示程序的手册页


# 重定向命令-重要重要重要
### 1、重定向符号
````aidl
> 号的使用 ex:ls /app > data.txt 但是会覆盖
>> 双重定向符 于上同 可以实现文本追加
````
### 2、将标准输入和输出重定向到同一个文件
````aidl
ls -l /app > test.txt 2>&1 
````
### 3、管道
````aidl
ls /app /app/app-mysql | sort | less
解释：将上一个标准的输出作为输入传送到后面的命令
````
### 4、去重
````aidl
uniq
````
### 5、打印行数,字数，字节数
````aidl
wc(world,count)
wc -l只报告行数
````
