# HHAlertView
An iOS AlertView Library ,with Error,Success,Warning 

 ![image](https://raw.githubusercontent.com/mrchenhao/HHAlertView/master/images/error.png)
 
 It's very esay to use HHAlertView

##setup


 
## How to use
 
 ```
 HHAlertView *alertview = [[HHAlertView alloc] initWithTitle:@"成功" detailText:@"恭喜你，操作顺利的实行了！\n换个行试试看效果" cancelButtonTitle:nil otherButtonTitles:@[@"确定"]];
 [alertview setEnterMode:HHAlertEnterModeTop];
 [alertview setLeaveMode:HHAlertLeaveModeBottom];
 [alertview showWithBlock:^(NSInteger index) {
    NSLog(@"%ld",index);
 }];
 
 ```
 
 there are three styles
 
 ```
 HHAlertViewModeSuccess,
 HHAlertViewModeError,
 HHAlertViewModeWarning,
 HHAlertViewModeInfo,
 HHAlertViewModeDefault,
 HHAlertViewModeCustom
 ```
 
It's easy to use,enjoy it!
 
## demo
 
 ![image](https://raw.githubusercontent.com/mrchenhao/HHAlertView/master/images/success.png)
 
 ![image](https://raw.githubusercontent.com/mrchenhao/HHAlertView/master/images/warning.png)
 
 
图文 都是原作者的, 觉得达不到自己的需求, 自己更改了, 自定义显示2 和 修改自适应大小, 文本和按钮的位置等等,  类型2  是把自定义view 放到标题下面 , 自定义View 大小 如果太大会自动缩小,不固定自定义View 的大小,以后有时间在改改

