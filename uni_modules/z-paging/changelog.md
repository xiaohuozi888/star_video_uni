## 1.6.7（2021-05-24）
1. 支持展示上次下拉刷新更新时间。  
2.新增加载失败view描述、图片、点击重新加载等。
3.新增`clean`方法，支持直接清空分页数据。  
## 1.6.6（2021-05-19）
1.新增`refresher-only`，支持只开启下拉刷新功能，关闭其他分页相关功能。  
2.nvue中，`nvue-list-is`新增支持scroller。  
3.`enable-back-to-top`默认值修改为true。  
4.修复使用页面滚动时，先向上滚动一段距离手指不松开下拉刷新，报错：Ignored attempt to cancel...的BUG。
## 1.6.5（2021-05-17）
1.支持i18n国际化，并添加相关demo。  
2.修复在微信小程序上偶现的`nv_setTimeout is not defined`的报错问题。
## 1.6.4（2021-05-14）
1.所有使用px的属性调整为兼容px和rpx。  
2.新增单z-paging tab切换保证数据一致解决方案和案例。  
3.修复在安卓nvue中，空数据图片无法显示的BUG。  
4.微调下拉刷新组件样式。

## 1.6.3（2021-05-13）
1.修复在wxs中使用箭头函数报错的问题 。 
2.新增`back-to-top-bottom`，可直接控制返回顶部按钮与底部的距离。  
3.返回按钮与底部距离计算加上`windowBottom`高度和安全区域高度。
## 1.6.2（2021-05-12）
1.新增nvue聊天记录模式，在nvue中可完全解决聊天记录分页闪动问题。  
2.新增slot="bottom"，支持在底部插入固定的view。  
3.新增nvue禁止回弹属性。  
4.新增全局配置方案二，支持在main.js中进行全局配置。  
5.修复猛烈下拉并松开时偶现的下拉刷新无法复位的问题。
