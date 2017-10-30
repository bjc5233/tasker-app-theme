# tasker-via-browser-homepage


## 说明
via浏览器主页背景随桌面壁纸变更，也可以设置背景图片与[nextday-tasker](https://github.com/bjc5233/next-day-tasker)一致；模糊使得搜索和书签更清晰；设置边缘色调使得背景更加具有沉浸感；底部为每日一句
* 安装via浏览器
* 安装tasker
* 导入tasker项目
* 必须配置项目根路径[root_path]为自己的路径
* 可配置壁纸模糊程度变量[blur_degree]，默认值[10px]
* 可配置书签标识颜色透明程度[bookmark_trans_degree]，默认值[0.5]
* 临时生成的图片会保存在项目根路径[root_path]下
* 程序会自动读取/data/data/mark.via/databases/via数据库中bookmarks表生成书签信息[书签标识的颜色随机]
* 设置边缘色调需要[tasker-common](https://github.com/bjc5233/tasker-common)中的[tasker-comm-wallpaper-color]支持

## 预览
[在线demo](https://bjc5233.github.io/demo-tasker-via-browser-homepage.html)
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-via-browser-homepage/raw/master/resources/Screenshot_2017-09-09-13-32-39-868.png"/></div>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-via-browser-homepage/raw/master/resources/Screenshot_2017-09-09-13-31-10-777.png"/></div>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-via-browser-homepage/raw/master/resources/Screenshot_2017-09-09-13-33-17-276.png"/></div>
