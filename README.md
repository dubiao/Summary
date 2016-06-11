
####以下为杜标的主要项目简介

> #### 青萍科技（2015-7 ~ Now）

	我加入一加硬件的创业公司。主要负责 iOS 上 app 的开发工作，次要负责公司官网、运营后台、公司网络、IT等杂项工作。
#### 1.  Amber -iOS （2015-7 ~ Now）<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_icon_amber.png" height="25">
![Amber App](https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_amber.png)
Amber 是一个给 Apple Watch 充电的移动电源，充电时可以盖上盖子把手表保护起来。
Amber-app 是一个和 Amber 配合使用的应用。通过蓝牙与 Amber 连接后可以监看 Amber 的状态，电量，是否充放，固件升级等功能。

	* 使用 `Swift` 语言编写代码
	* 使用 Alamofire 进行网络通信
	* 使用 Storyboard 编写界面
	* 使用 SnapKit 优化界面适配屏幕

[<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/App_Store_Badge.png" height="40">]
(https://itunes.apple.com/cn/app/amber-power-bank-for-apple/id1067704859?l=en&mt=8)

>相关小项目
>##### 1.  工厂测试 Debug App
	工厂生产中要对 Amber 进行连接测试，功能测试，感应器校准，固件烧写 等行为。
	所以也写了一个 Amber Dr. 做生产测试和 Debug 使用。也有记录跟踪状态的作用。
>##### 2. Log 查看后台
	Amber 到了用户手中难免会遇到问题，使用 App 会记录 Amber 使用过程中的一部分数据。
	如 电流、电压、电量、温度等，上传到后台。后台的数据要给专业人士看。
	所以有一个网站后台查询记录，能将记录转码成专业人士能看懂的表格样式，方便定位问题所在。
>##### 3. 公司官网
	 http://cleargrass.com
	 相关技术：PHP(Slim, Twig), NodeJS(Express, Jade), MySql, Python等
>##### 4.群发（或单发）邮件
	使用 http://mailgun.com/ 的服务。
>##### 5. 各种后台各种脚本
	大部分后台页面都是为了增加效率编写。
	

------

> #### 友录科技（2010-11 ~ 2015-7）

	2010 年 11 月以实习生身份加入友录科技。至 2015 年离开时参与过多个项目。大部分是 Android 项目。
	可惜的是这些项目目前均已停止服务或不再支持。

### 1. 友录通讯录-Android （2010～2012）<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_icon_yl.png" height="25">
![友录通讯-Android](https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_yl.png)
当时国内比较早且有名的通讯录项目，这个app 的主要功能就是 T9 快速拨号，有备份功能。上过 Google Play 的热榜。不吹牛地说，这款 app 当年很牛逼。
刚开始是负责各种反馈上来的 bug，还有一小模块的编码。后来在加入“友信”功能后，负责短信和“友信”的来消息的 拦截/通知/弹窗/快速回复 等功能。
在同类产品中，QQ 通讯录/ 360 通讯录/触宝拨号等 app 都不同程度的“参考”过友录通讯录的设计和功能。后来加入了短信和网络信息的功能。我们在做“友信”功能时， QQ 通讯录的网络信息功能比我们晚了 2 个迭代。后来……项目无疾而终。
	
项目生在 Android 2.1 时代。app 最远支持到 2.3 后在4.0 及更高版本上会闪退，后来改名为微博通讯录（参考第 4 个项目）。
	
媒体报道
	http://www.leiphone.com/news/201406/yolu-let-own-function-shame.html
获得了第一期的豌豆荚设计奖，不过官方的页面打不开了，唏嘘。
	http://zhan.renren.com/huoxing7?gid=3602888497996405267&from=template&checked=true
	
### 2. 友联系-Android （2011～2012）<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_icon_ylx.png" height="25">
![友联系-Android](https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_ylx.png)

以下是链接，可以看看图片和介绍不用下载，因为服务已经不可用。

[<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/Google_Play_Badge.png" height="40">]
(https://play.google.com/store/apps/details?id=com.ycontact&hl=zh_HK)
[<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/App_Store_Badge.png" height="40">]
(https://itunes.apple.com/cn/app/you-lian-xi-shang-wu-he-zhi/id484456145?mt=8)

> 友联系是友录在2011年12月推出的职场社交产品，为用户提供“便捷”、“有商务价值”的社交服务。用户可以扫描纸质名片，交换电子名片，创建或参加聚会，并以此维护和拓展人脉圈。友联系的商务价值体现在用户可以通过自己的“人脉”发现他们的朋友，交换名片通过请求后，可以查看对方包括工作履历在内的详细资料，可以称赞对方，还可以给对方发私信，也可以发邀请给通讯录联系人一起来用友联系。 
主要特色：准确率极高的纸质名片“云识别”、交换电子名片后自动跟踪并通知交换双方的名片资料变化、用户自发创建聚会创造内容并形成圈子。 

我在项目中负责 附近的人/摇一摇/拍名片（云端识别）/个人详情 等功能
    
#### 技术要点：
1. 附近的人/摇一摇
	使用百度和 Google 两种定位 SDk，配合提高服务可靠性
2. 个人详情
	* 封装详情控件
	* 封装编辑控件
3. 拍名片
    后来这个功能单独立一项目。
    当时安卓碎片化很严重，适配各种手机的相机很麻烦。
    


百科 
	http://www.baike.com/wiki/友联系

### 3. 友名片-Android （2012～2014）<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_icon_ycard.png" height="25">
![友名片-Android](https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_ycard.png)

[<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/Google_Play_Badge.png" height="40">]
(https://play.google.com/store/apps/details?id=com.ycard&hl=zh_HK)
[<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/App_Store_Badge.png" height="40">]
(https://itunes.apple.com/cn/app/you-ming-pian-ming-pian-shi-bie/id534966036?mt=8)

> 友名片”（Yolu Card Reader）是一款基于云端识别的名片管理工具，可以准确地将您的纸质名片转化为电子信息，并自动保存更新，让您轻松有效管理人脉资源。

因为友联系项目中的拍名片识别功能比较受欢迎，所以单独拿出来为一个 app。我负责项目 Android 平台的搭建及开发。功能包括但不限于 拍名片/编辑名片/保存联系人/交换名片 等功能。用户以国外为主，支持中/英/日/韩 4 种语言。
    
#### 技术要点：
1. 相机相关技术
	* 相机适配工作
	* 二维码生成与解析（库）
	* 拍照图片转码压缩，合并等
2. 自定义模块封装
	* 封装 TitleBar
	* 封装 名片控件
	* 封装 各种提示界面、对话框、空内容/错误提示等
	* 封装 网络请求
3. 列表项目拖动分组
4. 数据库优化

>相关项目
>##### 1. 名片识别后台（PHP，MySQL，HTML，JS，CSS）
>##### 2. 友联系

### 4. 微博通讯录-Android （2014～2015）<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_icon_wbtxl.png" height="25">
![微博通讯录-Android](https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_wbtxl.png)
后来公司内的一部分力量认为友录通讯录应该再做起来，正好这个时候公司与微博（新浪公司）有了点关系，所以冠名微博通讯录。我算是对原项目比较了解的人，所以负责这个新项目的 Android 部分（共 2.5 人）。
    App 主要还是 T9 拨号功能，有备份功能。
    
主要工作有 联系人列表排序、详情编辑、T9 性能优化、界面优化、合并微信、导入微博头像 等，还做一些界面上的功能（动画、切换等）。
    当时有两个功能比较亮：
    1.  可以从通讯录调用起微信里这个人的聊天界面。
    2.  绑定新浪微博后可以导入联系人在微博的头像。
   
[<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/Google_Play_Badge.png" height="40">]
(https://play.google.com/store/apps/details?id=com.youlu&hl=zh_HK)
[<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/App_Store_Badge.png" height="40">]
(https://itunes.apple.com/cn/app/wei-bo-tong-xun-lu-zhi-chi/id412378447?mt=8)

### 5. 微人脉-Android （2014～2015）<img src="https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_icon_wrm.png" height="25">
![微人脉-Android](https://raw.githubusercontent.com/dubiao/Summary/gh-pages/images/project_app_wrm.png)

与微博合作后，开发的一个职场社交 app 。进入项目的时间比较晚。负责项目中消息（群聊）/约见/活动 等新功能的开发。

> 相关项目
> ##### * 微人脉 iOS 项目（短暂）

	 我 2015 年 7 月离开友录公司加入青萍。在职 5 年期间参与了公司的大部分项目，我目前的大部分专业技能也是在这里习得。

-----
	
#### 技能
* App
	* Android
		* Java
		* JNI
	* iOS
		* Swift
		* Objective-C
	* React Native
* Server
	* PHP
		* Slim
		* Zend
		* Twig
	* NodeJS
		* Express
		* Jade(Pug)
	* Python
		* Django
* Front End
	* HTML
	* Javascript
		* JQuery
		* Zopto
	* CSS
		* Bootstrap 
* Database
	* MySQL
	* Sqlite
	* MongoDB
* Cloud Service
	* LeanCloud (Parse / Bmob)
	* 野狗 Wilddog (Firebase)
	* MailGun
* Tool
	* Git / Svn
		* Github.com 
		* GitCafe.com (Coding.net)
	* IDE
		* Android Studio
		* Xcode 
		* IntelliJ IDEA
		* Eclipse
		* PhpStorm
		* SublimeText
		* Atom
	* Distribute
		* 蒲公英
		* TestFlight
		* fir.im

...

