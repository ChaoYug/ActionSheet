# ActionSheet
一种类似微信弹窗的效果

使用方法:

将ActionSheet拖入工程
导入头文件#import "ActionSheet.h"


[[ActionSheet actionSheetView] showActionSheetWithArray:@[@"微信"] selectedIndexBlock:^(NSInteger index) {
NSLog(@"点击了第: %ld",(long)index);
}];

实现和用法都很简单,欢迎反馈.


