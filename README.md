AuthCodeView
============

绘制验证码，支持两种形式
 * 第一、给一个简单的字符串，我自己来画，主要用于客户端验证。eg:(DGCC)
 * 第二、给我一个连接，传给我一张图片，我来显示，用于服务端验证。eg:http://IP/.../.../codeImages.jsp

如果要显示数字的话：
            NSString *textC = [NSString stringWithFormat:@"%C", c];
改为：
            NSString *textC = [NSString stringWithFormat:@"%d", c%10];
