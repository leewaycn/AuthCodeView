如果要显示数字的话：
            NSString *textC = [NSString stringWithFormat:@"%C", c];
改为：
            NSString *textC = [NSString stringWithFormat:@"%d", c%10];
