# ijkPlayer

自定义播放器   创建方法   
    _playerView = [[SYMediaPlayerView alloc] initWithFrame:CGRectMake(0, TopMargin, kDWidth, MinPlayerHeight) uRL:[NSURL URLWithString:mvUrl] title:@"这是视频标题"];
    _playerView.delegate=self;
    [self.view addSubview:_playerView];
    代理自己实现 。我也不多说了
   写的 不是很好，只是完成了简单的一些功能。如有建议，请给我留言。大家共同学习，共同进步！