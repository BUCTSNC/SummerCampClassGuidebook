## BUCTSNC 暑期学校 指导说明

以下内容来自上游仓库[2021红岩网校工作站移动开发部Android方向寒假考核说明文档](https://github.com/SpreadWater/RedRockWinnterWork)，暂未进行Localization工作，还请稍安勿躁

------

2月20日更新
经过大家1个月时间的辛苦奋斗，到了收关展示的时间。
暂定2月24日使用腾讯会议的方式，对作品App进行展示。
展示内容：App功能以及实现的知识点，觉得使用的好的地方，不足改进之处。
1月21日更新
### 写在最前面

------

紧张的期末考试结束了，大学生活初体验完成，终于迎来了网校的~~寒假考核~~

从10月份的网校招新，到12月14日最后一次课结束，从最开始的“Hello，world”，从最开始的接触编程，到现在能够开发一个简单的app。这段时间你们上的每一节课，熬得每一个夜，掉过的每一根头发，每一次报错，闪退，你受过的苦，将会照亮你前进的路。



有人曾说，世上只有一种英雄主义，那就是认清生活之后，依然拥抱，热爱生活。对于我们，其实也一样，我们就是在一次次的不断尝试，不断总结中逐渐成长。希望大家能够再接再厉，利用好寒假的时间，认真完成我们的寒假考核，我相信，这一个月，可能会学到比你之前更多的东西，因为有万能的baidu和bing加持！





### 考核的目的

------

- **本次考核不通过的同学，将无法参与移动部门下学期的培训，务必认真对待本次考核**
- **下学期开学时，每个同学需要对自己的考核进行介绍**
- **下学期将采取导师制培训，双向选择，本次考核将成为你能力的主要体现。请务必认真对待。**



### 考核形式

------

- 在规定时间完成一个完整的app
- 采取评分制，分数达到合格，评分具体规则如下



### 评分规则

------

#### 基本内容

- 完整性，根据所提供的API文档，实现绝大部分的功能
- 代码规范，命名，分包，values。
- 本地数据的缓存
- UI，毕竟好的UI总会给人一种好感
- 禁止使用第三方库（Glide除外）

#### 加分内容

- 了解并使用MVP或者MVVM架构
- 好看的UI
- 使用Kotlin语言开发项目
- 自定义View（封装一些好看的控件等等）
- 封装常用工具类（网络请求，sp数据库等）
- 自己实现API后端接口

#### 减分内容

- 态度敷衍，app简陋

- 熬夜写代码

  

### App要求

------

- API兼容到Android5.0（API21）
- 使用AndroidX
- 将项目推到Github（禁止提交一次Commit，建议每天写一部分，写好commit信息，多次提交）
- 需要在Github附上完整的README，README必须包含
  - App的简要介绍（功能，主要功能界面的实现方法（设计思路））
  - 功能展示GIF图片（格式工厂可以转换）
  - 心得体会
  - 待提升优化的地方
- 将项目打包成APK
- 除了Glide图片加载库，其他网络请求，gson解析方法不能使用第三方库。（Retrofit和Rxjava除外)或者Kotlin的协程

### 考核提交

------

- 截止日期：2021年2月21日
- 提交方式：发送邮件到[mredrock@163.com](mailto:mredrock@163.com)
  - 邮件标题：2021寒假考核-学号-姓名。如：2021寒假考核-2019210xxx-邱天
  - 邮件正文：Github仓库地址
  - 邮件附件：正式版APK（需要数字签名）
- 未按时提交考核的视为放弃



### 考核内容选项

------

1. 一个自己想做的App

   - 但是需要包含网络请求，可以自己找接口，也可以自己撸后端

2. 玩Android(参考app可以下载玩Andorid)

   - ApI文档：https://www.wanandroid.com/blog/show/2

3. 彩云天气

   - https://dashboard.caiyunapp.com/彩云官方注册一个账号
   - 申请令牌信息。提交申请，得到令牌值
   - 使用彩云天气提供的各种APi接口。

4. POST 那年今日的接口  https://v1.alapi.cn/api/eventHitory

   

5. 图灵机器人：https://qiyukf.com/robot?hmsr=baidu&hmkw=bd1_tzc_p55419&renqun_youhua=254323&bd_vid=8094320582130189116

   

6. 高德地图https://lbs.amap.com/

