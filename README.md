structure
=========

go语言实现的数据结构问题
-------------------------

### 1.左旋字符串 <br />
题目描述： 定义字符串的左旋转操作：把字符串前面的若干个字符移动到字符串的尾部。
如把字符串abcdef左旋转2位得到字符串cdefab。
请实现字符串左旋转的函数，要求对长度为n的字符串操作的时间复杂度为O(n)，空间复杂度为O(1)。

解法：通过三次字符串翻转算法，
如"abc123"向左旋2位，ab翻转为ba,c123翻转为321c，字符串变为ba321c,再次翻转，得结果c123ab
