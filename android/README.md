
### Android开发工具

#### [Android Studio](http://developer.android.com/intl/zh-cn/sdk/index.html)
> Android开发环境，基于IntelliJ IDEA，谷歌2013年I/O大会发布，类似 Eclipse ADT；现已更新到1.3版本（截止15年8月），并支持NDK开发；渐渐取代之前用的Eclipse ADT 成为新的Android开发工具，不管你是新手还是大神，建议全部转移到新的IDE上面来。

#### [Eclipse ADT](http://developer.android.com/intl/zh-cn/tools/sdk/eclipse-adt.html)
> Eclipse做java开发的一定不会陌生，甚至一度成为java的代名词，而如今将渐渐退出Android开发舞台，Google宣布将在15年年底前停止对Eclipse ADT开发工具的一切支持。建议开发者全面转到Android Studio上面来，对于那些还没有转向Android Studio的开发者来说，现在则不得不面对这个问题了，因为Google已经宣布终止Eclipse Android工具的开发与支持，这也意味着包括ADT插件、Ant构建系统、DDMS、Traceview与其他一系列性能和监控工具。

#### [IntelliJ IDEA](http://www.jetbrains.com/idea/)
  > 部分开发者之前有基于此开发Android，随着Android Studio的稳定与普及，且后者基于前者基础上开发，所以无需再切换到这个上面上来了。

#### [genymotion](https://www.genymotion.com)
> genymotion是一套完整的工具，它提供了Android虚拟环境。由于比自带模拟器的速度快而备受开发者喜欢。  

#### [Gradle](http://gradle.org/)
> Gradle是一种依赖管理工具，基于Groovy语言，面向Java应用为主，它抛弃了基于XML的各种繁琐配置，取而代之的是一种基于Groovy的内部领域特定（DSL）语言。它支持已有的Maven或者Ivy仓库基础建设，有取代Maven之势。

#### [Maven](https://maven.apache.org/)
> Maven是一个采用纯Java编写的开 源项目管理工具。Maven采用了一种被称之为project object model (POM)概念来管理项目，所有的项目配置信息都被定义在一个叫做POM.xml的文件中，通过该文件，Maven可以管理项目的整个声明周期，包括编 译，构建，测试，发布，报告等等。目前Apache下绝大多数项目都已经采用Maven进行管理。而Maven本身还支持多种插件，可以方便更灵活的控制 项目。

#### [Ant](https://ant.apache.org/)
> Apache软件基金会JAKARTA目录中的一个子项目,同前面两个一样属于Java的build工具，早期项目用的还是比较多，后来渐渐被maven和Gradle所代替。

#### [Android Studio 中文组](http://www.android-studio.org/)
> Android Studio 中文组是一支针对Android Studio做本地化支持的团队，其工作包括：Android Studio 汉化，文献翻译，BUG收集，安装，配置过程中常见问题的发现和解决，以及中文教程的编写。

#### [Android Studio 中文社区](http://forum.Android-Studio.org)
>  Android Studio 的中文用户交流心得，收集问题，解决问题的平台。

#### [Android Studio 知识问答](http://ask.Android-Studio.org)
> Android Studio 知识问答社区。

#### [Android Asset Studio](http://romannurik.github.io/AndroidAssetStudio/)
> 在线的图标生成工具，包括Launcher icons、Action bar icons、Notification icons、Device-framed screenshots、Simple nine-patches、Generic icons、Android Action Bar Style Generator、Android Holo Colors Generator。

#### [AndroidDrawableFactory](https://github.com/tizionario/AndroidDrawableFactory)
> 一个生成Android应用所需尺寸图片的工具。

#### [AppIconSizes](http://appiconsizes.com/)
> 在线生成图标：包括iPhone, Android, IOS, Facebook, web touch icons, Blackberry, Windows Phone, Bada and WebOS app icons and splash/default images。

#### [Android Layout Binder](http://android.lineten.net/layout.php)
> 一个在线布局控件绑定工具，可以根据你给出的xml代码对应生成初始化好的java代码。

####  [android-contentprovider-generator](https://github.com/BoD/android-contentprovider-generator)
> 一个生成ContentProvider的小工具。

#### [Android Button Maker](http://angrytools.com/android/button/)
> 一个在线生成Android应用按钮代码的工具。其中的XML文件定义的几何形状，包括颜色，边框和梯度。

#### [androidkickstartr](http://androidkickstartr.com/)
> 可以根据你的配置，在线快速生成Android工程。

#### [DroidDraw](http://code.google.com/p/droiddraw/)
> 一个基于Java Swing的Android可视化界面设计器，可以通过它来生成复杂的Android Layout XML文件。

#### [SDK Tools](http://developer.android.com/intl/zh-cn/tools/help/index.html)
> 容易被初学者忽略的开发工具，也是官方提供的：
  1. Virtual Device Tools
    * Android Virtual Device Manager
    * Android Emulator (emulator)
    * mksdcard
  2. Development Tools
    * android
    * Hierarchy Viewer (hierarchyviewer)
    * lint
    * SDK Manager
    * sqlite3
  3. Debugging Tools
    * adb
    * ADB Shell Commands
    * Dalvik Debug Monitor Server (ddms)
    * Device Monitor
    * dmtracedump
    * hprof-conv
    * Systrace
    * traceview
    * Systrace
  4. Build Tools
    * JOBB
    * ProGuard
    * zipalign
  5. Image Tools
    * Draw 9-patch
    * etc1tool
    * Tracer for OpenGL ES
  6. Platform Tools
    * bmgr
    * logcat
  7. Android Testing Tools
    * Android Testing Support Library：
AndroidJUnitRunner、Espresso、UI Automator
    * Monkey
    * monkeyrunner
  8. NDK

### Android Studio插件

#### [ADBWIFI](https://github.com/layerlre/ADBWIFI)
> 能够通过WiFi连接你的Android设备，无需USB连接线就可以来进行应用的安装与调试。

#### [AndroidWiFiADB](https://github.com/pedrovgs/AndroidWiFiADB)
> IntelliJ/AndroidStudio插件：能够通过WiFi连接你的Android设备，无需USB连接线来进行应用的安装与调试。

#### [android-postfix-plugin](https://github.com/takahirom/android-postfix-plugin)
> 可根据后缀快速完成代码，这个属于拓展吧，系统已经有这些功能，如sout、notnull等，这个插件在原有的基础上增添了一些新的功能

#### [AndroidAccessors](https://github.com/jonstaff/AndroidAccessors)
> 快速生成get和set方法的插件，其实系统的也有类似功能，这个更快。

#### [Lifecycle-Sorter](https://github.com/armandAkop/Lifecycle-Sorter)
> 可以根据Activity或者fragment的生命周期对其生命周期方法位置进行先后排序， 快捷键Ctrl + alt + K

#### JsonOnlineViewer
> 可实现直接在android studio中调试接口数据，可以选择请求类型，自定义请求头及请求体，json数据格式化后展示

#### [CodeGlance](https://github.com/Vektah/CodeGlance)
> 可用于快速定位代码，类似于Sublime编辑器右侧定位视图

#### [idea-android-studio-plugin](https://github.com/Haehnchen/idea-android-studio-plugin)
> IntelliJ IDEA / Android Studio plugin with some tools and usability improvements

#### [folding-plugin](https://github.com/dmytrodanylyk/folding-plugin)
> 可以给资源文件分组，并且不移动文件，也不会创建文件夹：Android File Grouping Plugin

#### [Android  Drawable Importer](https://github.com/winterDroid/android-drawable-importer-intellij-plugin)
>为了适应所有Android屏幕的大小和密度，每个Android项目都会包含drawable文件夹。任何具备Android开发经验的开发人员都知道，为了支持所有的屏幕尺寸，你必须给每个屏幕类型导入不同的画板。Android  Drawable Importer插件能让这项工作变得更容易。它可以减少导入缩放图像到Android项目所需的工作量。Android  Drawable Importer添加了一个在不同分辨率导入画板或缩放指定图像到定义分辨率的选项。这个插件加速了开发人员的画板工作。

#### [Android ButterKnife Zelezny](https://github.com/avast/android-butterknife-zelezny)
> 用于在活动、片段和适配器中，从所选的XML布局文件生成ButterKnife注入。该插件提供了生成XML对象注入的最快方式。

#### [Android  Holo Colors Generator](https://github.com/jeromevdl/android-holo-colors-idea-plugin)
> 开发Android应用程序需要伟大的设计和布局。Android  Holo Colors Generator则是定制符合喜好的Android应用程序的最简单方法。Android  Holo Colors Generator是一个允许你为你的应用程序随心所欲地创建Android布局组件的插件。此插件会生成所有必要的可在项目中使用的相关的XML画板和样式资源。

#### [Android Parcelable code generator](https://github.com/mcharmas/android-parcelable-intellij-plugin)
> 生成实现了Parcelable接口的代码的插件。在你的类中，按下alt + insert键弹出插入代码的上下文菜单，你会看到在下面有一个Parcelable，如下所示。选择它之后，就会在你的类当中插入实现了Parcelable接口的代码。从此不用再手动写Parcelable代码。

####  [AndroidCodeGenerator](https://github.com/spacecowboy/AndroidCodeGenerator)
> 可以生成ViewHolder和findView方法的代码。尤其是在Adapter实现类的getView当中很有用。

#### [Android Layout ID Converter](https://github.com/funnything/OffingHarbor)
> 生成findView代码的使用方法。

#### [SelectorChapek for Android](https://github.com/inmite/android-selector-chapek)
> 生成Selector的插件。你需要在drawable文件夹中右键，在弹出的菜单中选择Generate Android Selectors，如下所示，它就会根据你的几个drawable文件夹里的资源的命名，帮你生成Selector代码。当然，你的资源文件需要根据约定的后缀来命名。比如按下状态为_pressed，正常状态为_normal，不可用状态为_disable，等等。

####  [genymotion-gradle-plugin](https://github.com/Genymobile/genymotion-gradle-plugin)
> 不同于图形化的genymotion插件，这个允许你通过脚本来配置，创建device。

####  [sdk-manager-plugin](https://github.com/JakeWharton/sdk-manager-plugin)
> SDK管理插件，自动检测更新并下载。

####  [otto-intellij-plugin](https://github.com/square/otto-intellij-plugin)
> otto事件导航工具。

####  [dagger-intellij-plugin](https://github.com/square/dagger-intellij-plugin)
> dagger可视化辅助工具。

#### [eventbus-intellij-plugin](https://github.com/kgmyshin/eventbus-intellij-plugin)
> eventbus导航插件

#### [eventbus3-intellij-plugin](https://github.com/kgmyshin/eventbus3-intellij-plugin)
> eventbus导航插件

#### [strings-xml-tools](https://github.com/constantine-ivanov/strings-xml-tools)
> 管理Android工程中字符串国际化的插件

####  [gradle-packer-plugin](https://github.com/mcxiaoke/gradle-packer-plugin)
> Android多渠道打包工具。

####  [gradle-retrolambda](https://github.com/evant/gradle-retrolambda)
> 在java 6 7中使用 lambda表达式的插件。

####  [lint-cleaner-plugin](https://github.com/marcoRS/lint-cleaner-plugin)
> 移除Android中无用资源。

####  [dexcount-gradle-plugin](https://github.com/KeepSafe/dexcount-gradle-plugin)
> 方法数计算，对于较大应用避免方法爆棚很有用。

####  [android-unit-test](https://github.com/JCAndKSolutions/android-unit-test)
> 添加Android单元测试。

####  [robolectric-gradle-plugin](https://github.com/robolectric/robolectric-gradle-plugin)
> Robolectric测试辅助工具。

####  [GradleDependenciesHelperPlugin](https://github.com/ligi/GradleDependenciesHelperPlugin)
> maven gradle 依赖支持自动补全。

####  [idea-markdown](https://github.com/nicoulaj/idea-markdown)
> markdown插件

####  [Codota](http://www.codota.com/)
> 搜索最好的Android代码。

####  [adb-idea](https://github.com/pbreault/adb-idea)
> 支持直接在AS面板中进行ADB操作，操作快捷菜单，快速清除数据，重启应用，卸载应用等操作。

####  [GsonFormat](https://github.com/zzz40500/GsonFormat)
> 根据Gson库使用的要求,将JSONObject格式的String 解析成实体。

#### Settings Repository：
> 不同设备之间同步Android Studio的配置。

#### idea vim
> 兼具ide和vim的优点。

#### .ignore：
> .gitignore配置插件。

####  [AndroidLocalizationer](https://github.com/westlinkin/AndroidLocalizationer)
> 可用于将项目中的 string 资源自动翻译为其他语言的 Android Studio/IntelliJ IDEA 插件

####  [robolectric-gradle-plugin](https://github.com/robolectric/robolectric-gradle-plugin)
> Gradle plugin for Robolectric.

####  [FIR_Plugin_Android](https://github.com/FIRHQ/FIR_Plugin_Android)
> 一键上传应用到fir.im


### Apk反编译工具

####  [android-apktool](http://ibotpeaches.github.io/Apktool/)

####  [Smali](https://github.com/JesusFreke/smali)

#### [Android APK Decompiler](http://www.decompileandroid.com/)

#### [dex2jar](https://github.com/pxb1988/dex2jar)
> Tools to work with android .dex and java .class files

#### [jd-gui](https://github.com/skylot/jadx)
> 用来查看反编译.class文件

#### [AndroidDecompiler](https://github.com/dirkvranckaert/AndroidDecompiler)
> Decompile any APK

#### [jadx-gui](https://github.com/skylot/jadx/tree/master/jadx-gui/src/main/java/jadx/gui)
> 方便的jadx工具，可以直接反编译apk

#### [enjarify](https://github.com/google/enjarify)
> Google的反编译工具：Enjarify is a tool for translating Dalvik bytecode to equivalent Java bytecode. This allows Java analysis tools to analyze Android applications.

#### [androguard](https://github.com/androguard/androguard)
> 使用DAD作为反编译器,可以分析恶意软件,有python api，可以写扩展

#### [show-java](https://github.com/niranjan94/show-java)
>   Android APK反编译客户端

### Android防护

####  [ProGuard](http://developer.android.com/intl/zh-cn/tools/help/proguard.html)

### 静态代码分析工具

#### [infer](https://github.com/facebook/infer)
> Facebook 开源的静态代码分析工具，用于在发布移动应用之前对代码进行分析，找出潜在的问题。

### Debug调试工具

####  [Stetho](http://facebook.github.io/stetho/)
> Stetho是Facebook出品的一个强大的Android调试工具，使用该工具你可以在Chrome Developer Tools查看App的布局，网络请求，sqlite，preference，一切都是可视化的操作，无须自己在去使用adb，也不需要root你的设备。使用的方式很简单，配置好之后，在Chrome地址栏输入chrome://inspect

#### [Augmented Traffic Control](http://facebook.github.io/augmented-traffic-control/)
> Facebook发布的开源移动网络测试工具Augmented Traffic Control（ATC），该工具能够利用Wi-Fi网络模拟2G、2.5G（Edge）、3G以及LTE 4G移动网络环境，测试工程师们可以快速在各种不同的模拟网络环境中切换，从而实现对智能手机和App在不同国家地区和应用环境下的性能表现进行测试。

####  [adbWireless](https://github.com/Skywriter-se/adbWireless)
> adbWireless能够让手机用无线来取代USB连接而使用ADB工具,但是需要你的手机root。

### 尺寸计算/转换工具

####  [androidpixels](http://androidpixels.net/)
> Android像素计算工具

####  [pixplicity](http://pixplicity.com/dp-px-converter/)
> Android像素计算工具

### JSON/XML转POJO

#### [jsonschema2pojo](http://www.jsonschema2pojo.org/)

### Chrome插件(辅助Android开发)

####  [Vysor](https://chrome.google.com/webstore/detail/vysor-beta/gidgenkbbabolejbgbpnhbimgjbffefm)
> 通过电脑可以操作手机，并实现手机与电脑同步。

####  [json-editor](https://chrome.google.com/webstore/detail/json-editor/lhkmoheomjbkfloacpgllgjcamhihfaj?hl=en)
> json可视化工具，并支持编辑。

### 数据库

#### [sqlitebrowser](https://github.com/sqlitebrowser/sqlitebrowser)
> SQLite可视化工具

### 综合

#### [AndroidDevTools](http://www.androiddevtools.cn/)
> 关于Android开发的大部分工具都在这里可以找到，除了有开发指南，视频教程，另外关于设计的也应有尽有：如PS插件，矢量图设计工具、切图工具、设计稿尺寸标记工具、原型设计工具、交互设计工具、配色工具、图标处理工具、取色工具、gif录制等等。

#### [SQLite Viewer](http://inloop.github.io/sqlite-viewer/)
> View SQLite file online
