# lx-music-script change log

All notable changes to this project will be documented in this file.

Project versioning adheres to [Semantic Versioning](http://semver.org/).
Commit convention is based on [Conventional Commits](http://conventionalcommits.org).
Change log format is based on [Keep a Changelog](http://keepachangelog.com/).

## 0.1.0 - 2021-12-30

### 新增

- 同步功能新增对列表位置调整的支持（需v1.15.3以上的PC端版本才支持）
- 新增播放详情页歌词字体大小调整设置，可在详情页右上角的按钮进行调整
- 新增同步服务地址历史列表功能
- 横屏播放详情页新增评论入口
- 我的列表歌曲三个点的菜单新增复制歌曲名

### 优化

- 修改对播放模块的调用，杜绝应用显示正在播放的歌曲与实际播放歌曲不一致的问题（这是播放模块歌曲队列与应用内歌曲队列在某些情况下出现不一致时导致的）
- 支持PC端同步功能添加对列表顺序调整的控制，确保手动调整位置后的列表与不同的电脑同步时，列表位置不会被还原
- 调整横屏下的导航栏、播放详情页布局，提高屏幕空间利用率并使其更易操作
- 调整歌单类别、我的列表弹出层界面
- 播放栏移除上一曲按钮，将多出来的空间加给播放、下一曲按钮
- 现在点击、长按播放栏歌曲标题也可以进入详情页、定位当前播放歌曲了

### 修复

- 修复kw源某些歌曲的歌词提取异常的问题

### 其他

- 升级react-native到v0.66.4
