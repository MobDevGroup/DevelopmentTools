
### iOS开发工具

#### [Xcode](https://developer.apple.com/xcode/downloads/)
> Xcode 允许你开发基于iOS的iPad、iPhone、iPod Touch 设备应用程序的一款IDE，利用它可以完成用户界面设计、编码、测试、调试、发布等一系列工作。是开发苹果应用一款必不可少的工具。

#### [AppCode](http://www.jetbrains.com/objc/)
> AppCode是JetBrains用以替代的Xcode的一款产品,早在2011年,AppCode就崭露头角并被广大开发者所喜爱。它和idea同属一个公司开发的产品，其秉承了jetBrains一贯的“快捷键丰富，自动化程度高，代码提示无处不在，界面简洁”的特点，是一个不错的第三方IDE。

#### [CocoaPods](https://cocoapods.org/)
> 一个用来帮助我们管理第三方依赖库的工具，它可以解决库与库之间的依赖关系，下载库的源代码，同时通过创建一个Xcode的workspace来将这些第三方库和我们的工程连接起来，供我们开发使用。让我们能自动化的、集中的、直观的管理第三方开源库。

#### [Carthage](https://github.com/Carthage/Carthage)
> 同样是用来帮助我们管理第三方依赖库的工具，具体可以看介绍与cocopods之间的不同。

#### [Reveal](http://revealapp.com/)
> 为了查看UI发生的变化，我们过去常常会重新编译我们的应用，不过效率非常低。Reveal为开发者带来了类似Firebug和Web Inspector的强大工具。


#### [Unused](https://github.com/jeffhodnett/Unused)
> 用来检查Xcode项目中没有用到的资源。

#### [Nomad](http://nomad-cli.com/)
> 是一个优秀的iOS开发命令行集，方便你操作苹果开发者中心（Apple Developer Center）的命令行工具，可以做的事情包括方便地添加测试设备，更新证书文件，增加App id，验证IAP的凭证等。

#### [xctool](https://github.com/facebook/xctool)
> facebook开源的一个iOS编译和测试的工具。使用它而不是用Xcode的UI界面是因为它是一个纯命令行工具。

#### [appledoc](https://github.com/tomaz/appledoc)
> 是一个从源码中抽取文档的工具。类似Java语言本身自带的javadoc命令，可以从源码中抽取文档。而appledoc就是这样一个命令行程序，可以从iOS工程的源代码中抽取相应的注释，生成帮助文档。

#### [xScope](http://xscopeapp.com/)
> 一款与界面开发相关的工具集。对于iOS开发，比较好用的功能包括它的放大镜取色工具、标尺工具等。其中放大镜取色工具可以将取到的多个色集收集起来，方便后续使用，并且支持直接粘贴成相关的程序颜色代码。

#### [PonyDebugger](https://github.com/square/PonyDebugger)
> 一个很给力的iOS调试工具,它的监视器安装在Chrome浏览器下做为插件使用,通过监视器和PonyDebugger的iOS SDK相辅相成,可以很好的监视App的运作情况.

#### [SimPholders](http://simpholders.com/)
>   SimPholders是一个可以帮助开发者快速定位到iOS模拟器沙盒文件夹的小工具,通常我们开发的App会有不少文件要存储在沙盒内,而开发途中我们需要经常去浏览沙盒内的文件,而这个目录太深了,最关键的,及时你好不容易进到沙盒文件目录时,在你选择你要具体查看的App沙盒时,又纠结了. 因为这些App文件夹的命名都是用UUID来命名的,这对于我们定位来说毫无意义,没办法也只有挨个点击看看是不是自己要看的App沙盒,每一次去到那里感觉像是爬一座山一样那么辛苦. 而SimPholders的出现就是来帮助开发者解决这个问题

#### [Opera Mobile Emulator](http://www.opera.com/zh-cn/developer/mobile-emulator)
> Opera Mobile Emulator主要是为从事手机Web项目的开发者准备的.在软件上通过内置的一些初始化设定可以配置出任意尺寸的浏览器.这样很方便的模拟在真实手机尺寸上面的显示情况.从而加速调试的效率,并且,当你需要两种此存的手机时,你无需准备两台手机. 只需要配置出两种尺寸的界面即可.

### 网络抓包

#### [Charles](http://www.charlesproxy.com/)
> Mac下常用的截取网络封包的工具，我们为了调试与服务器端的网络通讯协议，常常需要截取网络封包来分析。Charles通过将自己设置成系统的网络访问代理服务器，使得所有的网络访问请求都通过它来完成，从而实现了网络封包的截取和分析。

#### [Fiddle2](http://www.telerik.com/fiddler)
> Windows平台一款免费且功能强大的数据包抓取软件，它通过代理的方式获取程序http通讯的数据，可以用其检测网页和服务器的交互情况，能够记录所有客户端和服务器间的http请求，支持监视、设置断点、甚至修改输入输出数据等功能。

### Xcode插件

#### [GoOutside](https://github.com/dbgrandi/GoOutside)
> An Xcode plugin to track how much time you have spent waiting for Xcode to build.

#### [BBUncrustifyPlugin-Xcode](https://github.com/benoitsan/BBUncrustifyPlugin-Xcode)
> Xcode plugin to format source code using ClangFormat or Uncrustify

#### [Refactorator](https://github.com/johnno1962/Refactorator)
> SourceKit based Plugin for Xcode that Refactors Swift

#### [XActivatePowerMode](https://github.com/qfish/XActivatePowerMode)
> An Xcode plug-in makes POWER MODE happen in your Xcode.

#### [Swimat](https://github.com/Jintin/Swimat)
> 一个格式化swift代码的插件

#### [XBookmark](https://github.com/everettjf/XBookmark)
> Bookmark Plugin for Xcode

#### [xcode-wakatime](https://github.com/wakatime/xcode-wakatime)
> Xcode plugin to quantify your coding with automatic time tracking and metrics about your programming.

#### [Multiplex](https://github.com/kolinkrewinkel/Multiplex)
> Simultaneous editing for Xcode, inspired by Sublime Text.

####  [VVDocumenter](https://github.com/onevcat/VVDocumenter-Xcode)
> 自动生代码注释的工具，类似JavaDoc风格。

#### [ClangFormat](https://github.com/travisjeffery/ClangFormat-Xcode)
> 一款格式化代码工具，能够让开发者使用Clang将代码格式化为LLVM、Google、Chromium、Mozilla或WebKit等格式，其开发者为来自37signals的Travis Jeffery。通过ClangFormat，开发者不仅可以实现对代码的自动或批量格式化，还可以进行自定义配置。

#### [Code Pilot](http://codepilot.cc/)
> Code Pilot是Xcode 5的一款扩充插件，能够帮助开发者无需鼠标操作，即可在项目中快速方便地查找文件、方法和符号。

#### [XcodeBoost](https://github.com/fortinmike/XcodeBoost)
> XcodeBoost是一款可以让开发者轻而易举地检查和修改Objective-C代码的插件。XcodeBoost能够自动进行一些繁琐的操作，比如方法的定义与声明、添加基于命令行的代码处理（剪切/复制/粘贴/重复/删除行）、持续高亮等。

#### [XAlign](https://github.com/qfish/XAlign)
> XAlign是一款专门用于代码整理的Xcode插件，其作者为来自Geek Zoo Studio的开发者QFish。XAlign能够对开发者的代码非常快速地进行对齐优化，有“=”、宏定义、属性三种对齐模式。当然，如果默认的对齐风格不是自己喜欢的，开发者还可以自定义或提出issues。

#### [KSImageNamed](https://github.com/ksuther/KSImageNamed-Xcode)
> KSImageNamed是一款能够帮助开发者在Xcode中自动补全图片文件名称的插件，其开发者Kent Sutherland来自美国波士顿。KSImageNamed支持NSImage和UIImage，当开发者写到“[UIImage imaged:”时，便会自动将项目中的图片名称提示出来。此外，KSImageNamed还带有预览功能，对于经常使用代码生成图片的开发者可谓是十分便利。

#### [Fuzzy Autocomplete](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin)
> Fuzzy Autocomplete是一款Xcode 5代码自动补全插件，兼容KSImageNamed，其开发者为来自澳大利亚墨尔本的Jack Chen（创始人）和波兰华沙的Leszek Ślażyński（Fuzzy Autocomplete v2.0作者）。Fuzzy Autocomplete通过添加模糊匹配来提高Xcode代码自动补全功能，开发者无需遵循从头匹配原则，只要记得方法中的某个关键词即可进行匹配，极大地提高了工作效率。

#### [BBUDebuggerTuckAway](https://github.com/neonichu/BBUDebuggerTuckAway)
> BBUDebuggerTuckAway是一款支持自动隐藏Debugger的Xcode插件，其开发者为来自德国柏林Contentful GmbH公司的Boris Bügling。使用BBUDebuggerTuckAway，开发者能够实现在编辑代码时，自动隐藏底部的调试栏。

#### [Dash-Plugin-for-Xcode](https://github.com/omz/Dash-Plugin-for-Xcode)
> Dash Xcode plugin是Bogdan Popescu开发的一款集成了Dash文档查看器应用的Xcode插件，允许开发者在使用Option-Click或作用相同的快捷键操作查看当前文本的相关文档时，用Dash代替Xcode的文档查看器。

#### [HOStringSense-for-Xcode](https://github.com/holtwick/HOStringSense-for-Xcode)
> HOStringSense可以说是大段文本利器，对于开发者而言，在输入大段文本时，如果文本中包含了各种换行和特殊字符，那是相当地头疼，但通过HOStringSense，一切的问题都将迎刃而解。HOStringSense由来自德国的Mac和iOS开发者Dirk Holtwick开发，完美支持编辑正则表达式、多行文本、内联HTML等，还提供了极为快速的字符串长度统计反馈。

#### [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode)
> 一款Xcode插件，能让开发者视觉化地使用UIColor (and NSColor)，方便开发者定义颜色。该插件的编辑菜单增加了一些项目来插入颜色或者暂时禁用颜色高亮。

#### [XToDo](https://github.com/trawor/XToDo)
> 一款颇受Brett Terpstra大神喜爱的，出自国内iOS开发者之手的注释辅助插件——XToDo。这款由UniT微博客户端作者TraWor所开发的插件，可以将项目代码中的TODO、FIXME等注释进行收集并列举出来。

#### [XVim](https://github.com/JugglerShu/XVim)
> Xcode的vim插件，可以在Xcode的编辑窗口中开启vim模式。

#### [SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander)
> 帮助你迅速地在switch语句中填充枚举类型的每种可能的取值。

#### [deriveddata-exterminator](https://github.com/kattrali/deriveddata-exterminator)
> 一个清除Xcode缓存目录的插件。

#### [Peckham](https://github.com/markohlebar/Peckham)
> 添加引用文件有时候非常麻烦，如果你需要引入一个pod头文件，Xcode自带的自动补全自然帮不了你，这时候你可以用Peckham插件解决这个问题。Command+Control+P解决所有的引入。

#### [Lin](http://questbe.at/lin/)
> 款可在代码中添加本地化编辑器，用图形化管理项目的本地化，支持最新版本的Xcode6。

#### [Backlight](https://github.com/limejelly/Backlight-for-XCode)
> 有些插件看上去微不足道但是他们却非常有用。Backlight就是这样的插件，它只是把当前正在编辑的行突出显示。

#### [ESJsonFormat-Xcode](https://github.com/EnjoySR/ESJsonFormat-Xcode)
> 将JSON格式化输出为模型的属性。

#### [Auto-Importer-for-Xcode](https://github.com/citrusbyte/Auto-Importer-for-Xcode)
> 快速导入头文件的插件。

####  [Reveal-Plugin-for-Xcode](https://github.com/shjborage/Reveal-Plugin-for-Xcode)
> 自动将Reveal App集成到你的工程中去的Xcode插件。

####  [AutoresizeMask-for-Xcode](https://github.com/garnett/AutoresizeMask-for-Xcode)
> AutoresizeMask-for-Xcode让AutoresizingMask在代码层面拥有和xib一样的可视化的效果,这方便我们用好和用准AutoresizingMask。

#### [SCXcodeMiniMap](https://github.com/stefanceriu/SCXcodeMiniMap)
> SCXcodeMiniMap的灵感应该来源于Sublime Text.在代码编辑页面中,添加整页代码的迷你预览图,方面使用者能够快速拖动定位到关键位置。

#### [RRConstraintsPlugin](https://github.com/RolandasRazma/RRConstraintsPlugin)
> RRConstraintsPlugin是一个在IB中使用自动布局的辅助插件.

#### [injectionforxcode](http://injectionforxcode.com/)
> injectionforxcode是一个神奇的插件,可以实时的修改代码,而不需要重新编译运行到模拟器中.其核心实现技术真是一大亮点.

#### [Alcatraz](http://alcatraz.io/)
> iOS插件管理器。

#### [XcodeCoverage](https://github.com/jonreid/XcodeCoverage)
> XcodeCoverage 包含了一组脚本,提供一个简单的方法对 Xcode 项目的代码覆盖率进行统计并生成 HTML 报告。

#### [XCActionBar](https://github.com/pdcgomes/XCActionBar)
> Alfred应该都不陌生，在Mac中被广泛应用，XCActionBar则号称Xcode中的Alfred插件。

#### [Xcode-Plugin-Template](https://github.com/kattrali/Xcode-Plugin-Template)
> Xcode主题插件，支持Xcode6.0+。

#### [cocoapods-xcode-plugin](https://github.com/kattrali/cocoapods-xcode-plugin)
> cocoapods则不用多介绍了，Xcode中的插件。

#### [ACCodeSnippetRepositoryPlugin](https://github.com/acoomans/ACCodeSnippetRepositoryPlugin)
> 和git仓库无缝同步代码片段的一个Xcode插件。

#### [RTImageAssets](https://github.com/rickytan/RTImageAssets)
> 能够根据@3x图片自动生成@2x, @1x 图片的一个Xcode插件。

### 数据库

#### [sqlitebrowser](https://github.com/sqlitebrowser/sqlitebrowser)
> SQLite可视化工具

### 综合

#### [ios dev tools](http://www.scoop.it/t/ios-dev)
> 一个网站长期更新ios开发工具

#### [SQLite Viewer](http://inloop.github.io/sqlite-viewer/)
> View SQLite file online
