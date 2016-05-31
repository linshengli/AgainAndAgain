这是一部分文件，并不是全部，STandfordCPPLib中有这些.cpp  .h用到的头文件
要将这些运行需要将 所有文件的后缀名 .txt 删掉

文件组织方式

---evalstate.h  evalstate.cpp
提供一个字符串名字与值对应的MAP

--parse.h parse.cpp
将表达式构造成树（优先级）

--statement.h statement.cpp
提供Basic解释器的几个关键词类

--program.h program.cpp
处理与statement中关键词，将这些关键词组织到一起

--Basic.cpp
主程序（其中函数过长。。。。。。（不好，不好））