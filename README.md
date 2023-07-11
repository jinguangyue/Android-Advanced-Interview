如今安卓开发不像前几年那么热门，但是高级人才依然紧缺，大家看着这句话是不是很熟悉，因为 web 高级人才也紧缺，c++ 高级人才一样紧缺，那么到了人工智能时代，人工智能时代的高级人才也同样会紧缺！似乎是高级人才的人在其他领域也是高级人才，而不是因为选择了热门才会一帆风顺。

**网上高级工程师面试相关文章鱼龙混杂，要么一堆内容，要么内容质量太浅**， 鉴于此我整理了如下安卓开发高级工程师面试题以及答案帮助大家顺利进阶为高级工程师，目前我就职于某大厂安卓高级工程师职位，在当下大环境下也想为安卓工程师出一份力，通过我的技术经验整理了面试经常问的题，答案部分会是一篇文章或者几篇文章，都是我认真看过并且觉得不错才整理出来，大家知道高级工程师不会像刚入门那样被问的问题一句话两句话就能表述清楚，所以我通过过滤好文章来帮助大家理解，进入正题：

## Handler 相关知识，面试必问！

常问的点：</br>
Handler Looper Message 关系是什么？</br>
Messagequeue 的数据结构是什么？为什么要用这个数据结构？</br>
如何在子线程中创建 Handler?</br>
Handler post 方法原理？</br>
ThreadLocal 必备 </br>

[Android消息机制的原理及源码解析](https://www.jianshu.com/p/f10cff5b4c25)  源码角度完整解析 </br>
[Handler 都没搞懂，拿什么去跳槽啊？](https://juejin.im/post/5c74b64a6fb9a049be5e22fc)  </br>
[Android Handler 消息机制（解惑篇）](https://juejin.im/entry/57fb3c53128fe100546ea4f2)</br>
[Android 消息机制](https://blog.csdn.net/guolin_blog/article/details/9991569) **郭神的文章** </br>
[Android的消息机制之ThreadLocal的工作原理](https://blog.csdn.net/singwhatiwanna/article/details/48350919) **任玉刚的文章** </br>


## Activity 相关</br>

启动模式以及使用场景?</br>
onNewIntent()和onConfigurationChanged()</br>
onSaveInstanceState()和onRestoreInstanceState()</br>
Activity 到底是如何启动的</br>


[启动模式以及使用场景](https://blog.csdn.net/black_bird_cn/article/details/79764794) 详细的解释场景并且以及一些坑</br>
[onSaveInstanceState以及onRestoreInstanceState使用](https://www.jianshu.com/p/27181e2e32d2) 简单通透</br>
[onConfigurationChanged使用以及问题解决](https://www.jianshu.com/p/0127fb67516d) 全面得描述了各种情况</br>
[Activity 启动流程解析](https://blog.csdn.net/zhaokaiqiang1992/article/details/49428287)</br>

## Fragment </br></br>
Fragment 生命周期和 Activity 对比</br>
Fragment 之间如何进行通信</br>
Fragment的startActivityForResult</br>
Fragment重叠问题</br>

[Fragment 初探](https://blog.csdn.net/guolin_blog/article/details/8881711)</br>
[Fragment 重叠， 如何通信](https://blog.csdn.net/qq_24442769/article/details/77679147)</br>
[Fragment生命周期](https://www.jianshu.com/p/1b3f829810a1)</br>

## Service 相关</br>

**进程保活</br>
Service的运行线程（生命周期方法全部在主线程）</br>
Service启动方式以及如何停止</br>
ServiceConnection里面的回调方法运行在哪个线程？</br>**

[startService 和 bingService区别](https://www.jianshu.com/p/d870f99b675c) 完整讲解了它们之间得区别</br>
[进程保活一般套路](https://juejin.im/entry/58acf391ac502e007e9a0a11) 把进程保活手段都讲了一遍</br>
[关于进程保活你需要知道的一切](https://www.jianshu.com/p/63aafe3c12af) 10万+ 关于进程保活得文章</br>

## Android布局优化之ViewStub、include、merge</br>

什么情况下使用 ViewStub、include、merge？</br>
他们的原理是什么？</br>

[ViewStub、include、merge概念解析](https://blog.csdn.net/u012792686/article/details/72901531)</br>
[Android布局优化之ViewStub、include、merge使用与源码分析](https://blog.csdn.net/bboyfeiyu/article/details/45869393)</br>


## BroadcastReceiver 相关</br>
注册方式，优先级</br>
广播类型，区别</br>
广播的使用场景，原理</br>

[Android广播动态静态注册](https://blog.csdn.net/csdn_aiyang/article/details/68947014) 通俗易懂</br>
[常见使用以及流程解析](https://blog.csdn.net/carson_ho/article/details/52973504)</br>
[广播源码解析](https://www.jianshu.com/p/02085150339c)</br>

## AsyncTask相关</br>
AsyncTask是串行还是并行执行？</br>
AsyncTask随着安卓版本的变迁</br>

[AsyncTask完全解析](https://blog.csdn.net/guolin_blog/article/details/11711405) **郭神的文章 一篇足够 从使用到源码**</br>
[串行还是并行](https://blog.csdn.net/singwhatiwanna/article/details/17596225) </br>


## Android  事件分发机制</br>
onTouch和onTouchEvent区别，调用顺序</br>
dispatchTouchEvent， onTouchEvent， onInterceptTouchEvent 方法顺序以及使用场景</br>
滑动冲突，如何解决</br>

[事件分发机制](https://blog.csdn.net/guolin_blog/article/details/9097463) 郭神出品</br>
[事件分发解析](https://blog.csdn.net/lmj623565791/article/details/39102591) 鸿洋出品</br>
[dispatchTouchEvent， onTouchEvent， onInterceptTouchEvent方法的使用场景解析](https://www.jianshu.com/p/d3758eef1f72)</br>

## Android View 绘制流程</br>
简述 View 绘制流程</br>
onMeasure， onlayout， ondraw方法中需要注意的点</br>
如何进行自定义 View</br>
view 重绘机制</br>

[Android LayoutInflater原理分析，带你一步步深入了解View(一)](https://blog.csdn.net/guolin_blog/article/details/12921889)</br>
[Android视图状态及重绘流程分析，带你一步步深入了解View(二)](https://blog.csdn.net/guolin_blog/article/details/16330267)</br>
[Android视图状态及重绘流程分析，带你一步步深入了解View(三)](https://blog.csdn.net/guolin_blog/article/details/17045157)</br>
[Android自定义View的实现方法，带你一步步深入了解View(四)](https://blog.csdn.net/guolin_blog/article/details/17357967)</br>
**别问我为什么推荐这么多郭神的文章，因为我是看着郭神的文章长大的！**</br>


## Android Window、Activity、DecorView以及ViewRoot</br>
[Window、Activity、DecorView以及ViewRoot之间的关系](https://www.jianshu.com/p/8766babc40e0)</br>



## Android 的核心 Binder 多进程 AIDL</br>
常见的 IPC 机制以及使用场景</br>
为什么安卓要用 binder 进行跨进程传输</br>
多进程带来的问题</br>

[AIDL 使用浅析](https://blog.csdn.net/lmj623565791/article/details/38461079)</br>
[binder 原理解析](https://zhuanlan.zhihu.com/p/35519585) 真的不错</br>
[binder 最底层解析](https://blog.csdn.net/luoshengyang/article/details/6618363/)  很难理解，我看了几遍还是了解一个大概</br>
[多进程通信方式以及带来的问题](http://wuxiaolong.me/2018/02/15/AndroidIPC/)</br>
[多进程通信方式对比](https://blog.csdn.net/u011240877/article/details/72863432)</br>
</br>
## Android 高级必备 ：AMS,WMS,PMS</br>
这部分真的复杂！</br>
AMS,WMS,PMS 创建过程</br>

[AMS,WMS,PMS全解析](https://www.cnblogs.com/sunkeji/articles/7650482.html)</br>
[AMS启动流程](https://blog.csdn.net/itachi85/article/details/76405596) </br>
[WindowManagerService启动过程解析](https://blog.csdn.net/itachi85/article/details/78186741)</br>
[PMS 启动流程解析](https://blog.csdn.net/lilian0118/article/details/24455019)</br>
 
 ## Android ANR </br>
 为什么会发生 ANR？</br>
 如何定位 ANR？</br>
 如何避免 ANR？</br>
 
 [如何避免以及分析方法](https://www.jianshu.com/p/388166988cef)</br>
 [Android 性能优化之 ANR 详解](https://juejin.im/post/58e5bd6dda2f60005fea525c)</br>
 [非常详细的ANR监控和定位](https://juejin.cn/post/7171684761327370277)</br>
 [字节跳动ANR方案，震撼！](https://mp.weixin.qq.com/s/_Z6GdGRVWq-_JXf5Fs6fsw)</br>

## Android 内存相关</br>

**注意：内存泄漏和内存溢出是 2 个概念**</br>

什么情况下会内存泄漏？</br>
如何防止内存泄漏？</br>

[内存泄漏和溢出的区别](https://blog.csdn.net/u013435893/article/details/50608190)</br>
[OOM 概念以及安卓内存管理机制](http://hukai.me/android-performance-oom/)</br>
[内存泄漏的可能性](https://www.jianshu.com/p/ac00e370f83d)</br>
[防止内存泄漏的方法](https://www.jianshu.com/p/c5ac51d804fa)</br>
[LeakCanary原理从0到1](https://juejin.cn/post/6936452012058312740)</br>


## Android 屏幕适配</br>
屏幕适配相关名词解析</br>
现在流行的屏幕适配方式</br>

[屏幕适配名词以及概念解析](https://blog.csdn.net/zhaokaiqiang1992/article/details/45419023)</br>
[今日头条技术适配方案](https://zhuanlan.zhihu.com/p/37199709)</br>

## Android 缓存机制</br>
LruCache使用极其原理</br>

[Android缓存机制](https://www.jianshu.com/p/2608f036f362)</br>
[LruCache使用极其原理述](https://www.jianshu.com/p/b49a111147ee)</br>

## Android 性能优化</br>
如何进行 内存 cpu 耗电 的定位以及优化</br>
性能优化经常使用的方法</br>
如何避免 UI 卡顿</br>

我正在看极客时间的Android开发高手课，里面的性能优化文章不错</br>

[性能优化全解析，工具使用](https://juejin.im/post/5a0d30e151882546d71ee49e)</br>
[性能优化最佳实践](https://juejin.im/post/5b50b017f265da0f7b2f649c)</br>
[知乎高赞文章](https://zhuanlan.zhihu.com/p/30691789)</br>

## 性能优化-虚拟机调优

底层技术太有意思了

[性能优化-虚拟机调优](https://weishu.me/2016/12/23/dive-into-android-optimize-vm-heap/)</br>

## Android 性能监控</br>
[内存、cpu监控指令](https://juejin.cn/post/7103341017318817828)</br>
[性能监控采集、主线程卡顿监控](https://juejin.cn/post/6890754507639095303)
[ASM 无埋点监控](https://mp.weixin.qq.com/s/Xuc034VlR7TqjTaoaSuI2A)</br>

## Android 包体积优化
[android给apk瘦身全部技巧总结](https://juejin.cn/post/7022251588374757389)</br>
![包体积优化](https://github.com/jinguangyue/Android-Advanced-Interview/assets/8803674/c1ba687e-3a30-4ae0-9e9d-25d6c1d48308)


## Android MVC、MVP、MVVM</br>
好几种我该选择哪个？优劣点</br>

任玉刚的文章：
[设计模式选择](https://juejin.im/post/5b3a3a44f265da630e27a7e6)</br>

## Android Gradle 知识</br>
这俩篇官方文章基础的够用了</br>
[必须贴一下官方文档：配置构建](https://developer.android.com/studio/build?hl=zh-cn)</br>
[Gradle 提示与诀窍](https://developer.android.com/studio/build/gradle-tips?hl=zh-cn)</br>

Gradle插件 了解就好 </br>
[Gradle 自定义插件方式](https://blog.csdn.net/eclipsexys/article/details/50973205)</br>
[全面理解Gradle - 执行时序](https://blog.csdn.net/singwhatiwanna/article/details/78797506)</br>

[Gradle系列一](https://juejin.im/post/5af4f117f265da0b9f405221#heading-2)</br>
[Gradle系列二](https://juejin.im/post/5afa06466fb9a07aaa1163f1)</br>
[Gradle系列三](https://juejin.im/post/5b02113a5188254289190671)</br>


## RxJava</br>
使用过程，特点，原理解析</br>
[RxJava 名词以及如何使用](https://blog.piasy.com/2016/09/15/Understand-RxJava/index.html)</br>
[Rxjava 观察者模式原理解析](https://juejin.im/post/58dcc66444d904006dfd857a)</br>
[Rxjava订阅流程，线程切换，源码分析 系列](https://juejin.im/post/5a209c876fb9a0452577e830)</br>

## OKHTTP 和 Retrofit</br>
[OKHTTP完整解析](https://blog.csdn.net/lmj623565791/article/details/47911083)  --鸿洋出品</br>
[Retrofit使用流程，机制详解](https://blog.csdn.net/carson_ho/article/details/73732076)</br>
[从 HTTP 到 Retrofit](https://www.jianshu.com/p/45cb536be2f4)</br>
[Retrofit是如何工作的](https://www.jianshu.com/p/cb3a7413b448)</br>

## 最流行图片加载库： Glide</br>

**郭神系列 Glide 分析**</br>
[Android图片加载框架最全解析（一），Glide的基本用法](https://blog.csdn.net/guolin_blog/article/details/53759439)</br>
[Android图片加载框架最全解析（二），从源码的角度理解Glide的执行流程](https://blog.csdn.net/guolin_blog/article/details/53939176)</br>
[Android图片加载框架最全解析（三），深入探究Glide的缓存机制](http://blog.csdn.net/guolin_blog/article/details/54895665)</br>
[Android图片加载框架最全解析（四），玩转Glide的回调与监听](https://blog.csdn.net/guolin_blog/article/details/70215985)</br>
[Android图片加载框架最全解析（五），Glide强大的图片变换功能](http://blog.csdn.net/guolin_blog/article/details/71524668)</br>
[Android图片加载框架最全解析（六），探究Glide的自定义模块功能](http://blog.csdn.net/guolin_blog/article/details/78179422)</br>
[Android图片加载框架最全解析（七），实现带进度的Glide图片加载功能](http://blog.csdn.net/guolin_blog/article/details/78357251)</br>
[Android图片加载框架最全解析（八），带你全面了解Glide 4的用法](http://blog.csdn.net/guolin_blog/article/details/78582548)</br>


## Android 组件化与插件化</br>
业务大了代码多了会用到。</br>

为什么要用组件化？</br>
组件之间如何通信？</br>
组件之间如何跳转？</br>

[Android 插件化和热修复知识梳理](https://www.jianshu.com/p/704cac3eb13d)</br>
[为什么要用组件化](https://blog.csdn.net/guiying712/article/details/55213884)</br>
[1、Android彻底组件化方案实践](https://www.jianshu.com/p/1b1d77f58e84)</br>
[2、Android彻底组件化demo发布](https://www.jianshu.com/p/59822a7b2fad)</br>
[3、Android彻底组件化-代码和资源隔离](https://www.jianshu.com/p/c7459b59dcd5)</br>
[4、Android彻底组件化—UI跳转升级改造](https://www.jianshu.com/p/03c498e05a46)</br>
[5、Android彻底组件化—如何使用Arouter](https://www.jianshu.com/p/aa17cf4b2dca)</br>

[插件化框架历史](https://juejin.im/entry/59decdf36fb9a0451c39621b)</br>
[深入理解Android插件化技术](https://zhuanlan.zhihu.com/p/33017826) 阿里插件化技术</br>
[Android 插件化和热修复知识梳理</br>
](https://www.jianshu.com/p/704cac3eb13d)</br>

## Flutter 与 RN
[Flutter原理](https://zhuanlan.zhihu.com/p/36861174)</br>
[Flutter KO React Native? 让时间去决定吧...](https://juejin.im/post/5b0607c76fb9a07a9b365556)</br>
[如何评价 React Native？](https://www.zhihu.com/question/27852694)

## Kotlin 内联
[Kotlin-inline, noinline, crossinline关键字解析](https://blog.csdn.net/baidu_39589150/article/details/110920816)</br>

## Kotlin 协程
[详细介绍协程用法](https://juejin.cn/post/6908271959381901325)</br>

## Android 冷启动优化
使用冷启动闪屏页（Splash Screen）：在应用程序启动时显示一个简单的闪屏页，以给用户一个启动过程中的反馈，并允许应用程序后台进行一些初始化工作。

缓存数据和资源：使用缓存机制来存储常用的数据和资源，避免每次启动都重新加载。可以使用内存缓存、磁盘缓存或网络缓存等方式。

xml to view 减少xml解析耗时

减少启动 Activity 的依赖库和第三方插件：只加载必要的依赖库和插件，避免加载不必要的资源，以减少启动时间。

线程池



## 面试常问的点</br>
除了上面整理的安卓高级技术问题，还有一些面试官喜欢问的点，大家针对准备回答：</br>

 - 你在项目中遇到最难得点是什么？如何解决的？</br>
 - 平时遇到问题了是如何解决的？比较好的回答： 官方文档一定要看，通过源码解决问题，然后才是搜索引擎以及和同事讨论</br>
 - 你最近做的 APP 是如何架构的？为什么要这样架构？</br>
 - 平时怎么进行技术进阶，如何学习？</br>
 - 你觉得自己处于什么技术水平？</br>
 - 你的技术优势是什么？</br>
 - 用过什么开源技术？它的原理是什么？看过它的源码么？ 这里建议看上面 Glide 相关</br>
 - 如何设计一个框架？能不能回答上直接判断你的技术等级</br>


历时一周多终于整理完了，之所以准备这么久是因为以上每一篇文章我都认真看过，并且还有一些文章没有贴上来，因为质量上或者不易于理解，其中 **安卓技术问题** 我觉得基本逃不过上面我整理的，当然我会持续更新，**其次更重要的是**有的时候面试官问你问题如果你不会也很正常，不可能所有的问题我们都懂，但是我们必须有必要的思考过程，解决问题的过程与方式在职场中才是最重要的，而不是结果！这也是面试官最喜欢考察的。**另外**，我没有整理算法以及 java 基础问题，因为我是面向 Android 高级开发工程师准备的面试题，所以算法和 java 基础相信大家可以自行搜索复习。</br>
</br>


