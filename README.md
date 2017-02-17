# burpsuite-changeU

使用说明：

http://xdxd.love/2015/04/20/burpsuite%E6%8F%92%E4%BB%B6%E5%BC%80%E5%8F%91%E4%B9%8Bpython%E7%AF%87/

burpsuite 插件。将返回值中的unicode明文

比如：{"result":"passwd_error","msg":"\u7528\u6237\u540d\u5bc6\u7801\u9519\u8bef"}

转码为中文{"result":"passwd_error","msg":"--用户名密码错误--"}

提高测试效率
