- 验证用户名是否存在(第一部分讲完可以自行练习一下+录视频)
    + 1.html是静态页面
    + 2.html --> 为按钮添加点击事件，当点击的时候打印文本框的值
    + 3.html --> ajax方法
    + 4.html --> 修改tip信息
    + 5.html --> tip效果弄好看一些
    + 6.html --> 验证用户名是否为空,如果为空，则退出
    + 7.html --> 使用beforeSend的方式来写
    + 8.html --> 修改validateUsername.php睡3秒钟 --> 设置超时时间(timeout)为2000毫秒 --> error(注册失败)

- 获取验证码（这块是为了做效果的，都是假的模拟出来的，真实的手机验证码需要 https://www.yuntongxun.com/product/smscode.html?ly=sem-baidu&qd=pc-dasou&cp=sms&xl=dj-smsdan&kw=10349088）
    + 9.html是静态页面
    + 10.html --> 为按钮添加点击事件，当点击的时候打印手机文本框的值
    + 11.html --> 请求ajax数据
    + 12.html --> 验证手机号码是否符合规范（正则表达式）
    + 13.html --> 修改getCode.php,让其睡5秒
        - 思考：手机号收到验证码慢一点是正常的，所以不用设置timeout+error值
        - 可以设置一个倒计时5秒的时间
        - 设置按钮为class="disabled"类名
    + 14.html
        - 为了体验效果更好一点，设置一个倒计时效果

    + 15.html 
        - 频繁点击按钮，发现，虽然变灰色了，但还是可以重复发送信息

- 注册功能完成
    + 16.html是静态页面
    + 17.html把15.html,8.html中的js拷贝过来，稍微改造一下
    + 18.html --> 点击提交按钮，打印要提交的数据
    + 19.html --> 发送ajax
    + 20.html --> 如果成功，则提示注册成功
    + 21.html --> 其实我们还可以这样玩 ---> 
    + 22.html --> 讲解一个方法叫serialize方法
    + 23.html --> 设置注册后台的超时时间为3秒
        1. 在注册的这个阶段，让submit按钮变灰，值设置为注册中
        2. 设置timeout+error
    + 24.html --> 发现我们在success,error当中最后不管怎么样都需要设置 --> completed
