# ll_xcode_tool

Xcode 一键导入常用代码块  

如果喜欢，亲可以按照以下步骤clone到本地安装试试
```
1. check out the project using: git clone https://github.com/Cysdia/ll_xcode_tool.git
2. cd ll_xcode_tool
3. ./setup_snippets.sh
4. 成功之后输出:Done  
5. 重新新打开Xcode (需要先完全退出Xcode)
```
手动导入：
```
1. Finder->前往->前往文件夹
2. 前往路径：~/Library/Developer/Xcode/UserData/CodeSnippets/
3. 复制ll_xcode_tool/CodeSnippets内容，到Xcode的CodeSnippets文件夹下
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
