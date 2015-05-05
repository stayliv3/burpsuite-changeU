# burpsuite-changeU

burpsuite 插件。将返回值中的unicode明文

比如：{"result":"passwd_error","msg":"\u7528\u6237\u540d\u5bc6\u7801\u9519\u8bef"}

转码为中文{"result":"passwd_error","msg":"--验证码错误--"}

提高测试效率
