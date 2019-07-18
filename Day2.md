### Day2  (2019-7-17)
- #### start: 20:30
- #### end: 23:10
### 网易云信的SDK
##### 1.代码见 YX-VideoPlayer
##### bug解决记录：
```
解决github push错误The requested URL returned error: 403 Forbidden while accessing
github push错误：
git push
error: The requested URL returned error: 403 Forbidden while accessing https://github.com/wangz/future.git/info/refs
git version 1.7.1
解决方案：
vim .git/config
修改
[plain] view plain copy
[remote "origin"]
    url = https://github.com/wangz/example.git
为：
[remote "origin"]
    url = https://wangz@github.com/wangz/example.git
再次git push，弹出框输入密码，即可提交
```
- ps:两次遇到的问题，记录一下解决方法

