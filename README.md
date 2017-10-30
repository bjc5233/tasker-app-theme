# tasker-app-theme



## 说明
通过tasker处理，统一app主题[背景壁纸\主色调]
* [支付宝alipay](#支付宝alipay)
* [酷安coolapk](#酷安coolapk)
* [快牙kuaiya](#快牙kuaiya)
* [网易云音乐netease-cloud-music](#网易云音乐netease-cloud-music)
* [qq](#qq)
* [rainpaper](#rainpaper)
* [淘宝taobao](#淘宝taobao)
* [滴答清单ticktick](#滴答清单ticktick)
* [tsf桌面](#tsf桌面)
* [via浏览器via-browser](#via浏览器via-browser)
* [微信wechat](#微信wechat)
    
    
------------
## 支付宝alipay
### 说明
* 安装tasker
* 导入tasker项目
* 创建profile->event->system->Wallpaper Changed，关联导入的任务
* 配置根路径[root_path]变量为自己的路径
* 配置壁纸模糊程度[blur_degree]，默认值为[40]
* 必须先在支付宝设置中手动自定义聊天背景
* 需要[tasker-common](https://github.com/bjc5233/tasker-common)中的[tasker-comm-img-blur]模块支持
* 目前actionBar颜色无法动态适配


### 预览
<div align=center><img height="960" width="570" src="https://github.com/bjc5233/tasker-app-theme/raw/master/alipay/resources/Screenshot_2017-10-30-14-14-46-179.png"/></div>


    
    
------------
## 酷安coolapk
### 说明
* 安装tasker
* 导入tasker项目
* 创建profile->event->system->Wallpaper Changed，关联导入的任务
* 配置根路径[root_path]变量为自己的路径
* 进入酷安应用->主题风格->配置自定义颜色->颜色随便选择
* 主页背景色跟随壁纸，需要tasker-common中的[tasker-comm-wallpaper-color]模块支持


### 预览
<div align=center><img height="960" width="570" src="https://github.com/bjc5233/tasker-app-theme/raw/master/coolapk/resources/Screenshot_2017-10-30-14-08-07-454.png"/></div>
<br>
<div align=center><img height="960" width="570" src="https://github.com/bjc5233/tasker-app-theme/raw/master/coolapk/resources/Screenshot_2017-10-30-14-13-16-575.png"/></div>

  
  
  
  
  
  
  
------------
## 快牙kuaiya
### 说明
快牙主页很多功能不会用到，配置自动设置快牙主页样式，背景跟随系统当前壁纸
* 安装tasker
* 导入tasker项目
* 创建profile->event->system->Wallpaper Changed，关联导入的任务
* 配置根路径[root_path]变量为自己的路径
* 配置壁纸模糊程度[background_blur_degree]，默认值为[0px]
* 配置当前皮肤背景名[skin_wallpaper_path]（必须先手动自定义皮肤）
* 主页背景色跟随壁纸，需要tasker-common中的[tasker-comm-wallpaper-color]模块支持


### 预览[after\before]
<div align=center><img height="960" width="570" src="https://github.com/bjc5233/tasker-app-theme/raw/master/kuaiya/resources/after.png"/></div>
<br>
<div align=center><img src="https://github.com/bjc5233/tasker-app-theme/raw/master/kuaiya/resources/before.png"/></div>
  



------------
## 网易云音乐netease-cloud-music
### 说明
自动设置网易云音乐皮肤背景
* 安装tasker
* 导入tasker项目
* 创建profile->event->system->Wallpaper Changed，关联导入的任务
* 配置根路径[root_path]变量为自己的路径
* 配置当前皮肤背景名[skin_wallpaper_path]（必须先手动自定义皮肤）
* 配置背景模糊程度[skin_wallpaper_blur_degree]，值[0-30]，默认值为[8]
* **注意任务执行时会自动关闭网易云音乐APP**


### 预览
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/netease-cloud-music/resources/Screenshot_2017-09-13-13-42-23-441.png"/></div>
<br>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/netease-cloud-music/resources/Screenshot_2017-09-13-13-49-21-903.png"/></div>
     



	 

------------
## qq
### 说明
* 安装tasker
* 导入tasker项目
* 创建profile->event->system->Wallpaper Changed，关联导入的任务
* 配置根路径[root_path]变量为自己的路径
* 配置当前皮肤背景名[skin_wallpaper_path]
* 配置背景模糊程度[blur_degree]，默认值为[40]
* [tasker-common](https://github.com/bjc5233/tasker-common)中的[tasker-comm-img-blur]模块支持
* 必须先手动在QQ设置中自定义聊天背景
* 目前actionBar颜色无法动态适配


### 预览
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/qq/resources/Screenshot_2017-10-30-14-20-53-966.png"/></div>

	 
	 
	 
	 
------------
## rainpaper

	 
	 
	 
	 
------------
## 淘宝taobao
### 说明
自动设置淘宝ActionBar背景，颜色跟随壁纸
* 安装tasker
* 导入tasker项目
* 为淘宝配置官方skinBlue皮肤
* 配置根路径[root_path]变量为自己的路径
* 需要[tasker-common](https://github.com/bjc5233/tasker-common)中的[comm-wallpaper-color][comm-image-draw-rect][comm-image-paint-png]模块支持


### 预览
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/taobao/resources/Screenshot_2017-09-25-20-10-26-999.png"/></div>
<br>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/taobao/resources/Screenshot_2017-09-25-20-20-15-170.png"/></div>
     



	 
------------
## 滴答清单ticktick
### 说明
滴答清单ticktick是android下比较好用好看的TODO应用。这个tasker任务可以在设置桌面壁纸时，动态更新滴答清单的banner图。
### 配置
* 安装tasker
* 导入tasker任务文件[切换壁纸更新ticktick.tsk.xml]
* 配置根据经[root_path]为自己的路径
* 配置滴答清单当前正在使用的皮肤名[skin_name]，滴答清单皮肤文件夹是[Android/data/cn.ticktick.task/files/skin/]
* 手动设置桌面壁纸
* 重启滴答清单查看效果


### 预览
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/ticktick/resources/demo.png"/></div>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/ticktick/resources/demo2.png"/></div>
     



	 
------------
## tsf桌面
### 说明
动态更新tsf文件夹颜色[目前使用不方便，需要手动重启tsf桌面才会生效]


	 
------------
## via浏览器via-browser
### 说明
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

### 预览
[在线demo](https://bjc5233.github.io/demo-tasker-via-browser-homepage.html)
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/via-browser/resources/Screenshot_2017-09-09-13-32-39-868.png"/></div>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/via-browser/resources/Screenshot_2017-09-09-13-31-10-777.png"/></div>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/via-browser/resources/Screenshot_2017-09-09-13-33-17-276.png"/></div>
     



	 
------------
## 微信wechat
### 说明
自动设置微信聊天背景与ActionBar颜色，背景是当前壁纸[模糊处理]，颜色跟随壁纸
* 安装tasker
* 导入tasker项目
* 安装xposed
* 安装xposed模块wechatUI
* 配置根路径[root_path]变量为自己的路径
* 配置壁纸模糊程度根路径[blur_degree],，默认值为[40]
* 配置ActionBar颜色透明度[bar_color_trans]，可选值为[0-1]，默认值为[1]
* 需要[tasker-common](https://github.com/bjc5233/tasker-common)中的[comm-wallpaper-color][comm-trans2hex-color][comm-image-blur]模块支持


### 预览
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/wechat/resources/Screenshot_2017-09-25-20-11-19-58.png"/></div>
<br>
<div align=center><img height="960" width="540" src="https://github.com/bjc5233/tasker-app-theme/raw/master/wechat/resources/Screenshot_2017-09-25-20-19-37-695.png"/></div>
    