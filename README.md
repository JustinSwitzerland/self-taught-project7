# self-taught-project7

这个是写银行账户/转账/借款/流水的应用<br>

随意登陆一个账号密码<br>
user: js pin: 1111<br>
user: jd pin: 2222<br>
user: stw pin: 3333<br>
user: ss pin: 4444<br>

我这里出现了一个BUG无法解决<br>
https://justinswitzerland.github.io/self-taught-project7/

这两个按钮我都没有设置帧听函数addEventLister，但是每次点击，就直接自动刷新了。<br>

解决思路：起初我觉得是因为我的JS代码写错了。一遍一遍找出来，后面对照标准答案再尝试寻找出来。但是还是没有结果。<br>
最后，还是网上找大神去解决问题：
原来原因是HTML：Form 标签里的 button，没设置 type，会自动设置成 submit
