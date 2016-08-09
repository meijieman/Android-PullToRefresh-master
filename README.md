# Android-PullToRefresh-master
Android-PullToRefresh-master 项目迁移到 as 上

[原项目地址](https://github.com/chrisbanes/Android-PullToRefresh)

替换了过时的`FloatMath.float()`为`Math.float()`

bug？
在 `onRefresh()` 中直接调用 `onRefreshComplete()` 刷新不消失
