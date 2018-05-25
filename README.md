# ll_xcode_tool

Xcode 一键导入常用代码块  

使用:
```
cd YY_Tool
./setup_snippets.sh
成功之后输出:
Done  
重新新打开Xcode (需要先完全退出Xcode)
```


如果喜欢，亲可以按照以下步骤clone到本地安装试试
```
1. check out the project using: git clone https://github.com/Cysdia/ll_xcode_tool.git
2. cd ll_xcode_tool
3. ./setup_snippets.sh
4. 成功之后输出:
        Done  
        重新新打开Xcode (需要先完全退出Xcode)
```
```
或者手动打开: Finder->前往->前往文件夹
~/Library/Developer/Xcode/UserData/CodeSnippets/
```

删除代码块:
```
cd ll_xcode_tool
./clear_snippets.sh
```
清除Xcode 缓存垃圾,释放磁盘存储空间:
```
cd ll_xcode_tool
./clear_Temp_data.sh
```

```
只能初始化一次 ./setup_snippets.sh 
如果想要重复初始化  
手动到:
~/Library/Developer/Xcode/UserData/CodeSnippets.backup/ 
(如果上一层没有CodeSnippets文件夹 拖动到外面 如果外面有)删除CodeSnippets.backup内的CodeSnippets文件夹 
然后./setup_snippets.sh
```
