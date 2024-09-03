## 字符串相关操作

#### 1.最长前后公共子串

直接上例子：

abcdabc --->  abc

aaaaaaa--> aaaaaa

#### 2.字符串的增删改查
string str1; //生成空字符串
|函数名|用途|代码|
|--:|:--:|:--|
|size()|返回字符串个数|str.size()|
|push_back()|尾插一个字符|str.push_back()|
|append() += |两个都是字符串拼接|str.append("abc")<br>str2 += str3.c_str()|
|erase()|字符的删除|s1.erase(1,6)|
|interator ite = s1.begin();|遍历字符串|for循环遍历|
|replace(pos,n,s)|从pos索引开始的第n个字符，替换成字符串s|s1.replace(6,5,"girl");|
|find(const char** s,size_t pos)|查找子串|s.find("chicken");|
#### 3.返回字符串个数
```c++
	string str = "abcdabc";
	int size = str.size();
	printf("%d",size);
```

