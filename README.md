# for-Actions
听说有action这个工具了，建一个repository尝试尝试。
本来就是复制粘贴来的，但是commit了好几次，都没有通过，总结下来，有几处是需要注意的：
1、weather.sh要放在这里的目录下啊
2、on后面的schedule
3、Settings里面可以设置secret，{{secrets.MAIL_USERNAME}} 这变量名，我把secret也加上去了，是不是智障呀...

163邮箱修改密码会关闭smtp/pop3服务，所以今天早晨没发邮件，现在更新了一下授权码，commit一下看可不可以。
