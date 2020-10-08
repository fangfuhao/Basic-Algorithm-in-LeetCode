# Basic-Algorithm-in-LeetCode
Review 
//滑动窗口 cpp;
Leetcode 03
1.用HASH集合记录出现过的字符，
2.count()判断重复字符；
3.尾指针初始-1；
4.尾指针+1 知道末尾&&出现重复字符；
5.外层遍历数组，i++；
6.当i>0时，去除HASH集合键值为s[i-1]的记录；if(i>0) cur.erase(s[i-1])；
7.不含重复字符的最长字串 ans=max(ans,first - i + 1);
