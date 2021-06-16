感谢大家的关注与支持，最近工作上比较忙，一直没有抽出时间来更新~

8月份终于赶在最后几天把性能优化补全了，结构方面还会再优化一下。然后这个月，也就是9月份开始着手第三方框架的内容，10月底前打算先把面试题给整理出来，后面计划会给大家制作一份知识体系图……

TM……我是真的好辛苦啊……**你确定不来个star？**

> 部分内容收集整理于网络，在此也再次感谢所有内容产出者的贡献！
>
> > [版权声明](https://github.com/BlackZhangJX/Android-Notes#版权声明)
> >
> > > 如果觉得看起来比较麻烦，需要PDF版本，或是需要更多学习资料、面试资料，进阶、架构资料，都可以加上[QQ群](https://jq.qq.com/?_wv=1027&k=ZzEmip7o)领取。祝愿每一位有追求的Android开发同胞都能进大厂拿高薪！

## 需要高清PDF版的小伙伴请加粉丝 Q Q群

Android开发交流QQ群：**930068172 （备注一下GitHub）**

快捷加群方式：[点击此处加入群聊Android开发交流群](https://jq.qq.com/?_wv=1027&k=ZzEmip7o)

![Android技术交流群](https://images.gitee.com/uploads/images/2020/0903/222921_a93c9881_8016301.png "屏幕截图.png")

## **获取方式二：添加微信:Lxy_Maniu**

<div align=center>
<img src="https://user-images.githubusercontent.com/68420976/121190665-da21c900-c89d-11eb-9b2c-58d878c5739d.png">
</div>

# Android-Notes

Android开发核心知识点笔记-目录：

| 1️⃣                                                            | 2️⃣                                                            | 3️⃣                                                            | 4️⃣                                                            | 5️⃣                                                            | 6️⃣                                                            | 7️⃣                                                            | 8️⃣                                                            | 9️⃣                                                            | 🔟                                                            |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Java**                                                     | **Android**                                                  | **Android扩展**                                              | **性能优化**                                                 | **开源库源码分析**                                           | **Kotlin**                                                   | **设计模式**                                                 | **Gradle**                                                   | **计算机网络基础**                                           | **常见面试算法题**                                           |
| [☕](https://github.com/BlackZhangJX/Android-Notes#Java-知识点汇总) | [📱](https://github.com/BlackZhangJX/Android-Notes#Android-知识点汇总) | [📳](https://github.com/BlackZhangJX/Android-Notes#Android-扩展知识点汇总) | [⚙️](https://github.com/BlackZhangJX/Android-Notes#性能优化知识点汇总) | [🔍](https://github.com/BlackZhangJX/Android-Notes#Android-开源库源码分析) | [🍭](https://github.com/BlackZhangJX/Android-Notes#Kotlin知识点汇总) | [🛠️](https://github.com/BlackZhangJX/Android-Notes#设计模式汇总) | [📔](https://github.com/BlackZhangJX/Android-Notes#Gradle知识点汇总) | [💻](https://github.com/BlackZhangJX/Android-Notes#计算机网络基础) | [📝](https://github.com/BlackZhangJX/Android-Notes#常见面试算法题汇总) |

## Java 知识点汇总

- JVM
  - [JVM 工作流程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#jvm-工作流程)
  - [运行时数据区（Runtime Data Area）](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#运行时数据区runtime-data-area)
  - [方法指令](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#方法指令)
  - [类加载器](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#类加载器)
  - 垃圾回收 gc
    - [对象存活判断](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#对象存活判断)
    - [垃圾收集算法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#垃圾收集算法)
    - [垃圾收集器](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#垃圾收集器)
    - [内存模型与回收策略](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#内存模型与回收策略)
- Object
  - [equals 方法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#equals-方法)
  - [hashCode 方法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#hashcode-方法)
- [static](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#static)
- [final](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#final)
- [String、StringBuffer、StringBuilder](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#stringstringbufferstringbuilder)
- [异常处理](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#异常处理)
- 内部类
  - [匿名内部类](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#匿名内部类)
- [多态](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#多态)
- [抽象和接口](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#抽象和接口)
- 集合框架
  - HashMap
    - [结构图](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#结构图)
    - [HashMap 的工作原理](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#hashmap-的工作原理)
    - [HashMap 与 HashTable 对比](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#hashmap-与-hashtable-对比)
  - ConcurrentHashMap
    - [Base 1.7](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#base-17)
    - [Base 1.8](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#base-18)
  - [ArrayList](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#arraylist)
  - [LinkedList](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#linkedlist)
  - [CopyOnWriteArrayList](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#copyonwritearraylist)
- [反射](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#反射)
- 单例
  - [饿汉式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#饿汉式)
  - [双重检查模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#双重检查模式)
  - [静态内部类模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#静态内部类模式)
- 线程
  - [状态](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#状态)
  - [状态控制](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#状态控制)
- [volatile](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#volatile)
- synchronized
  - [根据获取的锁分类](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#根据获取的锁分类)
  - [原理](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#原理)
- Lock
  - 锁的分类
    - [悲观锁、乐观锁](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#悲观锁乐观锁)
    - [自旋锁、适应性自旋锁](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#自旋锁适应性自旋锁)
    - [死锁](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#死锁)
- [引用类型](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#引用类型)
- [动态代理](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#动态代理)
- [元注解](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Java知识点汇总.md#元注解)

## Android 知识点汇总

- Activity
  - [生命周期](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#生命周期)
  - [启动模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#启动模式)
  - [启动过程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#启动过程)
- Fragment
  - [特点](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#特点)
  - [生命周期](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#生命周期-1)
  - [与Activity通信](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#与activity通信)
- Service
  - [启动过程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#启动过程-1)
  - [绑定过程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#绑定过程)
  - [生命周期](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#生命周期-2)
  - [启用前台服务](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#启用前台服务)
- BroadcastReceiver
  - [注册过程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#注册过程)
- ContentProvider
  - [基本使用](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#基本使用)
- [数据存储](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#数据存储)
- View
  - [MeasureSpec](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#measurespec)
  - [MotionEvent](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#motionevent)
  - [VelocityTracker](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#velocitytracker)
  - [GestureDetector](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#gesturedetector)
  - [Scroller](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#scroller)
  - [View 的滑动](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#view-的滑动)
  - [View 的事件分发](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#view-的事件分发)
  - [在 Activity 中获取某个 View 的宽高](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#在-activity-中获取某个-view-的宽高)
  - [Draw 的基本流程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#draw-的基本流程)
  - [自定义 View](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#自定义-view)
- 进程
  - [进程生命周期](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#进程生命周期)
  - [多进程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#多进程)
  - 进程存活
    - [OOM_ADJ](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#oom_adj)
    - [进程被杀情况](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#进程被杀情况)
    - [进程保活方案](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#进程保活方案)
- Parcelable 接口
  - [使用示例](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#使用示例)
  - [方法说明](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#方法说明)
  - [Parcelable 与 Serializable 对比](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#parcelable-与-serializable-对比)
- IPC
  - [IPC方式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#ipc方式)
  - Binder
    - [流程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#流程)
  - [AIDL 通信](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#aidl-通信)
  - [Messenger](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#messenger)
- Window / WindowManager
  - [Window 概念与分类](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#window-概念与分类)
  - [Window 的内部机制](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#window-的内部机制)
  - Window 的创建过程
    - [Activity 的 Window 创建过程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#activity-的-window-创建过程)
    - [Dialog 的 Window 创建过程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#dialog-的-window-创建过程)
    - [Toast 的 Window 创建过程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#toast-的-window-创建过程)
- Bitmap
  - [配置信息与压缩方式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#配置信息与压缩方式)
  - 常用操作
    - [裁剪、缩放、旋转、移动](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#裁剪缩放旋转移动)
    - [保存与释放](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#保存与释放)
    - [图片压缩](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#图片压缩)
  - BitmapFactory
    - [Bitmap创建流程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#bitmap创建流程)
    - [Option类](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#option类)
    - [基本使用](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#基本使用-1)
  - [内存回收](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#内存回收)
- 屏幕适配
  - [单位](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#单位)
  - [头条适配方案](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#头条适配方案)
  - [刘海屏适配](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#刘海屏适配)
- [Context](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#context)
- SharedPreferences
  - 获取方式
    - [getPreferences](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#getpreferences)
    - [getDefaultSharedPreferences](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#getdefaultsharedpreferences)
    - [getSharedPreferences](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#getsharedpreferences)
  - [架构](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#架构)
  - [apply / commit](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#apply--commit)
  - [注意](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#注意)
- 消息机制
  - [Handler 机制](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#handler-机制)
  - 工作原理
    - [ThreadLocal](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#threadlocal)
    - [MessageQueue](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#messagequeue)
    - [Looper](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#looper)
    - [Handler](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#handler)
- 线程异步
  - AsyncTask
    - [基本使用](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#基本使用-2)
    - [工作原理](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#工作原理-1)
  - [HandlerThread](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#handlerthread)
  - [IntentService](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#intentservice)
  - [线程池](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#线程池)
- [RecyclerView 优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#recyclerview-优化)
- Webview
  - 基本使用
    - [WebView](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#webview-1)
    - [WebSettings](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#websettings)
    - [WebViewClient](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#webviewclient)
    - [WebChromeClient](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#webchromeclient)
  - [Webview 加载优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#webview-加载优化)
  - [内存泄漏](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android知识点汇总.md#内存泄漏)

## Android 扩展知识点汇总

- ART
  - ART 功能
    - [预先 (AOT) 编译](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#预先-aot-编译)
    - [垃圾回收优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#垃圾回收优化)
    - [开发和调试方面的优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#开发和调试方面的优化)
  - [ART GC](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#art-gc)
- Apk 包体优化
  - [Apk 组成结构](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#apk-组成结构)
  - [整体优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#整体优化)
  - [资源优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#资源优化)
  - [代码优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#代码优化)
  - [.arsc文件优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#arsc文件优化)
  - [lib目录优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#lib目录优化)
- Hook
  - [基本流程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#基本流程)
  - [使用示例](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#使用示例)
- Proguard
  - [规则](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#规则)
  - [公共模板](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#公共模板)
  - [常用的自定义混淆规则](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#常用的自定义混淆规则)
  - [aar中增加独立的混淆配置](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#aar中增加独立的混淆配置)
  - [检查混淆和追踪异常](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#检查混淆和追踪异常)
- 架构
  - [MVC](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#mvc)
  - [MVP](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#mvp)
  - [MVVM](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#mvvm)
- Jetpack
  - [架构](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#架构-1)
  - [使用示例](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#使用示例-1)
- NDK 开发
  - JNI 基础
    - [数据类型](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#数据类型)
    - [String 字符串函数操作](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#string-字符串函数操作)
    - [常用 JNI 访问 Java 对象方法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#常用-jni-访问-java-对象方法)
  - NDK 开发
    - [基础开发流程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#基础开发流程)
    - [System.loadLibrary()](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#systemloadlibrary)
  - [CMake 构建 NDK 项目](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#cmake-构建-ndk-项目)
  - [常用的 Android NDK 原生 API](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#常用的-android-ndk-原生-api)
- 类加载器
  - [双亲委托模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#双亲委托模式)
  - [DexPathList](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android扩展知识点.md#dexpathlist)

## 性能优化知识点汇总

- 启动优化
  - 视觉优化
    - [启动主题优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#启动主题优化)
  - 代码优化
    - [冷启动耗时统计](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#冷启动耗时统计)
    - [Application 优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Application-优化)
    - [闪屏页业务优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#闪屏页业务优化)
    - [广告页优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#广告页优化)
  - [优化效果](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#优化效果)
  - [启动窗口](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#启动窗口)
- UI渲染优化
  - [CPU、GPU的职责](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#CPUGPU的职责)
  - [查找Overdraw](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#查找Overdraw)
  - [clipRect解决自定义View的OverDraw](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#clipRect解决自定义View的OverDraw)
  - [Hierarchy Viewer的使用](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Hierarchy-Viewer的使用)
  - [内存抖动现象](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#内存抖动现象)
- 崩溃优化
  - 崩溃
    - [崩溃的收集](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#崩溃的收集)
    - [ANR](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#ANR)
    - [应用退出](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#应用退出)
  - 崩溃处理
    - [崩溃现场](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#崩溃现场)
    - [崩溃分析](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#崩溃分析)
    - [系统崩溃](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#系统崩溃)
- 内存优化
  - 优化工具
    - [Memory Profiler](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Memory-Profiler)
    - [Memory Analyzer（MAT）](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Memory-AnalyzerMAT)
    - [LeakCannary](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#LeakCannary)
  - 内存管理
    - [内存区域](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#内存区域)
    - [对象存活判断](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#对象存活判断)
    - [垃圾回收算法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#垃圾回收算法)
  - 内存抖动
    - [模拟内存抖动](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#模拟内存抖动)
    - [分析并定位](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#分析并定位)
  - 内存泄露
    - [模拟内存泄露](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#模拟内存泄露)
    - [分析并定位](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#分析并定位-1)
  - MAT分析工具
    - [Overview](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Overview)
    - [Histogram](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Histogram)
    - [Dominator_tree](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Dominator_tree)
    - [SQL](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#SQL)
    - [Thread_overview](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Thread_overview)
    - [Top Consumers](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Top-Consumers)
    - [Leak Suspects](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Leak-Suspects)
  - 通过ARTHook检测不合理图片
    - [获取Bitmap占用内存](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#获取Bitmap占用内存)
    - [检测大图](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#检测大图)
  - 线上内存监控
    - [常规方案](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#常规方案)
    - [LeakCannary定制改造](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#LeakCannary定制改造)
    - [完整方案](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#完整方案)
- 卡顿优化
  - [卡顿](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#卡顿)
  - [帧率](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#帧率)
  - [卡顿原因](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#卡顿原因)
  - 卡顿检测
    - [使用dumpsys gfxinfo](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#使用dumpsys-gfxinfo)
    - [使用systrace](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#使用systrace)
    - [使用BlockCanary](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#使用BlockCanary)
    - [使用Choreographer](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#使用Choreographer)
  - [优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#优化)
- 存储优化
  - [交换数据格式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#交换数据格式)
  - [SharePreferences 优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#SharePreferences-优化)
  - [Bitmap 解码](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.mdBitmap-解码)
  - 数据库优化
    - [事务](https://github.com/BlackZhangJX/Android-Notes#事务)
    - [SQLiteStatement](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#SQLiteStatement)
    - [索引](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#索引)
  - [其它通用优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#其它通用优化)
- 网络优化
  - [网络连接对用户的影响](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#网络连接对用户的影响)
  - 分析网络连接的工具
    - [Network Monitor](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Network-Monitor)
    - [网络代理工具](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#网络代理工具)
  - 从哪些方面优化网络连接
    - [接口设计](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#接口设计)
    - [网络缓存](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#网络缓存)
    - [弱网测试&优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#弱网测试&优化)
- 耗电优化
  - 耗电监控
    - [Android Vitals](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Android-Vitals)
  - [耗电监控都监控什么](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#耗电监控都监控什么)
  - 如何监控耗电
    - [Java Hook](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Java-Hook)
    - [插桩](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#插桩)
- 多线程并发优化
  - Thread 使用
    - [Thread 中断](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Thread-中断)
    - [同步](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#同步)
  - Android Threading
    - [AsyncTask](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#AsyncTask)
    - [HandlerThread](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#HandlerThread)
    - [IntentService](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#IntentService)
    - [Loader](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Loader)
    - [ThreadPool](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#ThreadPool)
  - [线程优先级](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#线程优先级)
- 安装包优化
  - 常用的优化方式
    - [清理无用资源](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#清理无用资源)
    - [图片资源优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#图片资源优化)
    - [资源动态加载](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#资源动态加载)
    - [lib库优化](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#lib库优化)
    - [7zip压缩资源](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#7zip压缩资源)
    - [代码混淆](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#代码混淆)
    - [资源(res)混淆](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#资源res混淆)
    - [使用微信AndResGuard](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#使用微信AndResGuard)
    - [Facebook的redex优化字节码](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/性能优化知识点汇总.md#Facebook的redex优化字节码)

## Android 开源库源码分析

- LeakCanary
  - [初始化注册](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android开源库源码分析.md#初始化注册)
  - [引用泄漏观察](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android开源库源码分析.md#引用泄漏观察)
  - [Dump Heap](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android开源库源码分析.md#dump-heap)
- EventBus
  - [自定义注解](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android开源库源码分析.md#自定义注解)
  - [注册订阅者](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android开源库源码分析.md#注册订阅者)
  - [发送事件](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Android开源库源码分析.md#发送事件)

## Kotlin知识点汇总

- 语法
  - [对象](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#对象)
  - [类](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#类)
  - [继承](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#继承)
  - [变量](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#变量)
  - [常量](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#常量)
  - [静态常量](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#静态常量)
  - [定义方法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#定义方法)
  - [重载方法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#重载方法)
  - [基本数据类型](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#基本数据类型)
  - [比较类型](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#比较类型)
  - [转换符](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#转换符)
  - [字符串比较](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#字符串比较)
  - [数组](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#数组)
  - [循环](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#循环)
  - [角标循环](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#角标循环)
  - [高级循环](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#高级循环)
  - [判断器](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#判断器)
  - [构造函数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#构造函数)
  - [类创建](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#类创建)
  - [私有化 set 方法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#私有化-set-方法)
  - [私有化 get 方法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#私有化-get-方法)
  - [枚举](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#枚举)
  - [接口](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#接口)
  - [匿名内部类](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#匿名内部类)
  - [内部类](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#内部类)
  - [内部类访问外部类同名变量](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#内部类访问外部类同名变量)
  - [抽象类](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#抽象类)
  - [静态变量和方法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#静态变量和方法)
  - [可变参数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#可变参数)
  - [泛型](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#泛型)
  - [构造代码块](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#构造代码块)
  - [静态代码块](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#静态代码块)
  - [方法代码块](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#方法代码块)
  - [可见修饰符](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#可见修饰符)
  - [无需 findViewById](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#无需-findViewById)
  - [Lambda](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#Lambda)
  - [函数变量](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#函数变量)
  - [空安全](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#空安全)
  - [方法支持添加默认参数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#方法支持添加默认参数)
  - [类方法扩展](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#类方法扩展)
  - [运算符重载](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#运算符重载)
  - 扩展函数
    - [let 函数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#let-函数)
    - [with 函数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#with-函数)
    - [run 函数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#run-函数)
    - [apply 函数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#apply-函数)
    - [also 函数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#also-函数)
    - [总结](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#总结)
  - [协程](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Kotlin知识点汇总.md#协程)

## 设计模式汇总

- [设计模式分类](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#设计模式分类)
- [面向对象六大原则](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#面向对象六大原则)
- [工厂模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#工厂模式)
- [单例模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#单例模式)
- [建造者模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#建造者模式)
- [原型模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#原型模式)
- [适配器模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#适配器模式)
- [观察者模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#观察者模式)
- [代理模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#代理模式)
- [责任链模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#责任链模式)
- [策略模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#策略模式)
- [备忘录模式](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/设计模式汇总.md#备忘录模式)

## Gradle知识点汇总

- [依赖项配置](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/Gradle知识点汇总.md#依赖项配置)

## 计算机网络基础

- [网络体系的分层结构](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#网络体系的分层结构)
- HTTP 相关
  - 请求报文
    - [请求行](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#请求行)
    - [请求头](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#请求头)
  - [响应报文](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#响应报文)
  - [常见状态码](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#常见状态码)
  - [缓存机制](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#缓存机制)
  - [Https](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#https)
  - [Http 2.0](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#http-20)
- TCP/IP
  - [三次握手](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#三次握手)
  - [四次挥手](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#四次挥手)
  - [TCP 与 UDP 的区别](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#tcp-与-udp-的区别)
- Socket
  - [使用示例](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/计算机网络基础.md#使用示例)

## 常见面试算法题汇总

- 排序
  - 比较排序
    - [冒泡排序](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#冒泡排序)
    - [归并排序](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#归并排序)
    - [快速排序](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#快速排序)
  - 线性排序
    - [计数排序](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#计数排序)
    - [桶排序](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#桶排序)
- 二叉树
  - [顺序遍历](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#顺序遍历)
  - [层次遍历](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#层次遍历)
  - [左右翻转](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#左右翻转)
  - [最大值](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最大值)
  - [最大深度](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最大深度)
  - [最小深度](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最小深度)
  - [平衡二叉树](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#平衡二叉树)
- 链表
  - [删除节点](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#删除节点)
  - [翻转链表](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#翻转链表)
  - [中间元素](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#中间元素)
  - [判断是否为循环链表](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#判断是否为循环链表)
  - [合并两个已排序链表](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#合并两个已排序链表)
  - [链表排序](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#链表排序)
  - [删除倒数第N个节点](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#删除倒数第n个节点)
  - [两个链表是否相交](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#两个链表是否相交)
- 栈 / 队列
  - [带最小值操作的栈](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#带最小值操作的栈)
  - [有效括号](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#有效括号)
  - [用栈实现队列](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#用栈实现队列)
  - [逆波兰表达式求值](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#逆波兰表达式求值)
- 二分
  - [二分搜索](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#二分搜索)
  - [X的平方根](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#x的平方根)
- 哈希表
  - [两数之和](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#两数之和)
  - [连续数组](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#连续数组)
  - [最长无重复字符的子串](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最长无重复字符的子串)
  - [最多点在一条直线上](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最多点在一条直线上)
- 堆 / 优先队列
  - [前K大的数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#前k大的数)
  - [前K大的数II](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#前k大的数ii)
  - [第K大的数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#第k大的数)
- 二叉搜索树
  - [验证二叉搜索树](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#验证二叉搜索树)
  - [第K小的元素](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#第k小的元素)
- 数组 / 双指针
  - [加一](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#加一)
  - [删除元素](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#删除元素)
  - [删除排序数组中的重复数字](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#删除排序数组中的重复数字)
  - [我的日程安排表 I](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#我的日程安排表-i)
  - [合并排序数组](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#合并排序数组)
- 贪心
  - [买卖股票的最佳时机](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#买卖股票的最佳时机)
  - [买卖股票的最佳时机 II](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#买卖股票的最佳时机-ii)
  - [最大子数组](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最大子数组)
  - [主元素](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#主元素)
- 字符串处理
  - [生成括号](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#生成括号)
  - [Excel表列标题](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#excel表列标题)
  - [翻转游戏](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#翻转游戏)
  - [翻转字符串中的单词](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#翻转字符串中的单词)
  - [转换字符串到整数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#转换字符串到整数)
  - [最长公共前缀](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#最长公共前缀)
  - [回文数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#回文数)
- 动态规划
  - [单词拆分](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#单词拆分)
  - [爬楼梯](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#爬楼梯)
  - [打劫房屋](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#打劫房屋)
  - [编辑距离](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#编辑距离)
  - [乘积最大子序列](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#乘积最大子序列)
- 矩阵
  - [螺旋矩阵](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#螺旋矩阵)
  - [判断数独是否合法](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#判断数独是否合法)
  - [旋转图像](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#旋转图像)
- 二进制 / 位运算
  - [落单的数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#落单的数)
  - [格雷编码](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#格雷编码)
- 其他
  - [反转整数](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#反转整数)
  - [LRU缓存策略](https://github.com/BlackZhangJX/Android-Notes/blob/master/Docs/常见面试算法题汇总.md#lru缓存策略)

# 赞赏本库

如果这个库对您有很大帮助，您愿意支持这个项目的进一步开发以及这个项目的持续维护👇

**可以点个Star！！！！**

![谢谢](https://images.gitee.com/uploads/images/2020/0903/223815_98d79186_8016301.png "屏幕截图.png")

# Contanct Me

如果觉得看起来比较麻烦，**需要PDF版本，或是需要更多学习资料，都可以加上QQ群领取**

> 本群由我创立，目前已将群主权限交由合作方便于进行日常管理，介意的朋友们在GitHub上看最新版就好了
>
> > 如果你对于群管理有更好的建议，欢迎群内私聊我（我是-不管事不答疑的随缘冒泡废人）
> >
> > > 行了行了，名字很随意已经有很多人说过了…毕竟还是要恰饭的嘛…

**祝愿每一位有追求的Android开发同胞都能进大厂拿高薪！**


## Q Q群

Android开发交流QQ群：**930068172 （备注一下GitHub）**

快捷加群方式：[点击此处加入群聊Android开发交流群](https://jq.qq.com/?_wv=1027&k=ZzEmip7o)

![Android技术交流群](https://images.gitee.com/uploads/images/2020/0903/222921_a93c9881_8016301.png "屏幕截图.png")

## **获取方式二：添加微信:Lxy_Maniu**

<div align=center>
<img src="https://user-images.githubusercontent.com/68420976/121190665-da21c900-c89d-11eb-9b2c-58d878c5739d.png">
</div>

> PS：
> 平常很忙，找思思小姐姐领取就好了，别找我

## 微信公众号

**【程序猿养成中心】**

![程序猿养成中心](https://images.gitee.com/uploads/images/2020/0903/223133_01db9643_8016301.png "屏幕截图.png")

# 版权声明

[![知识共享许可协议](https://camo.githubusercontent.com/777429797f9180579ed59a4f95d148a0c213dfa8/68747470733a2f2f692e6372656174697665636f6d6d6f6e732e6f72672f6c2f62792d6e632d6e642f342e302f38387833312e706e67)](http://creativecommons.org/licenses/by-nc-nd/4.0/)
本作品采用[知识共享署名-非商业性使用-禁止演绎 4.0 国际许可协议](http://creativecommons.org/licenses/by-nc-nd/4.0/)进行许可。

Copyright © 2019-present BlackZhangJX

转载本作品内容须遵守上述协议，保证作品内容的完整并注明作者及出处。

任何个人或组织，未经作者本人沟通许可，不得将文中全部或部分内容洗稿和用于写书、卖课等商业活动。
