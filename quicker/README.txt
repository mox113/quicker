帮助自己和朋友提高Android开发效率和稳定性而开始着手编写的一个Android框架
已有功能：
1.快速加载网络图片，已有内存缓存和磁盘缓存  (不足：只有加载网络图片、字符串功能、网络请求基于AsyncTask 导致API11之后单线程加载图片并压缩图片 效率上... )
2.View注解和事件注解 (不足：基于反射 性能...)
3.常用工具类(屏幕信息获取、App信息获取、Http请求封装、键盘弹起关闭、Log信息管理、
   Toast封装避免相同内容不停Toast、单位转换、网络状态获取、SDCard状态获取、SharedPreferendce put get remove clear方法封装
4.常用自定义View (上拉刷新 下拉加载ListView 、 侧边栏)以及适配器的封装