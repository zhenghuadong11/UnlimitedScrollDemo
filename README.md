# UnlimitedScrollDemo
封装一个无限滚动的控件，传入图片之后自动生成
使用方法：

    CGUnilimiteScrollView * scrollView = [[CGUnilimiteScrollView alloc] initWithFrame:CGRectMake(0, 0,self.view.width, 150)];
    UIImage * iamge1 = [UIImage imageNamed:@"1"];
    UIImage * image2 = [UIImage imageNamed:@"2"];
    UIImage * image3 = [UIImage imageNamed:@"3"];
    NSMutableArray<UIImage *> * imageArray = [NSMutableArray arrayWithObjects:iamge1,image2,image3, nil];
    scrollView.imageStrs = imageArray;
    [self.view addSubview:scrollView];
