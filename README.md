# Studio 精品插件集

* 项目地址：[Github](https://github.com/getActivity/StudioPlugins)、[码云](https://gitee.com/getActivity/StudioPlugins)

* 博客地址：[Studio 精品插件推荐](https://www.jianshu.com/p/54bfd9e4d24c)

#### 使用需知

* 所有插件在 Android Studio 2021.1.1.23（小蜜蜂） 上测试均没有问题，推荐使用此版本

* Android Studio 2021.1.1.23（小蜜蜂） 正式版下载：[Windows 版本](https://r3---sn-j5o76n7l.gvt1.com/edgedl/android/studio/ide-zips/2021.1.1.23/android-studio-2021.1.1.23-windows.zip)，[macOs 版本](https://r1---sn-j5o76n7l.gvt1.com/edgedl/android/studio/install/2021.1.1.23/android-studio-2021.1.1.23-mac.dmg)，[macOs arm 版本](https://r4---sn-j5o7dn7e.gvt1.com/edgedl/android/studio/install/2021.1.1.23/android-studio-2021.1.1.23-mac_arm.dmg)

* 下载好插件，选择 `Settings` -> `Plugins`  -> `Install Plugin from Disk` 进行安装

![](picture/InstallPlugin.jpg)

* 小技巧：如果出现安装不了的情况，并且 Studio 不是这个版本的，可以直接复制插件的名称然后在 Studio 插件在线搜索并下载，Studio 会自动帮你匹配最佳的插件版本。

<details>
<summary><font size="4"> 更新日志（点击展开）</font></summary>

* 2022 年 5 月 15 日：<br>新增 Markdown 插件<br>新增 CodeLocator 插件<br>新增 SequenceDiagram 插件<br>新增 JsonHelper 代替 JsonViewer 插件<br>新增 GsonFormat 代替 GsonFormatPlus 插件<br>更新 RainbowBrackets 插件版本<br>更新 TranslationPlugin 插件版本<br>更新 JsonToKotlinClass 插件版本<br>更新 ChineseLanguagePack 插件版本

* 2021 年 7 月 9 日：[<br>更新彩虹括号插件版本<br>更新 IDEA 中文包插件版本<br>更新 GsonFormatPlus 插件版本<br>更新 JsonToKotlinClass 插件版本](https://github.com/getActivity/StudioPlugins/commit/11a8ecf35572453a32f96dbdc86f118251b43833)

* 2021 年 3 月 28 日：[<br>更新翻译插件版本<br>更新彩虹括号插件版本<br>更新 GsonFormat 插件版本](https://github.com/getActivity/StudioPlugins/commit/3974376360d314bcd0ae6279a2b682610e00bccf)

* 2021 年 3 月 21 日：[<br>新增复制到访达插件<br>更新翻译插件版本<br>移除代码预览小窗口插件<br>添加插件作品 Github 信息](https://github.com/getActivity/StudioPlugins/commit/0207498bf1a5e2f1f645088ffff79c21d03664cb)

* 2020 年 1 月 14 日：[<br>插件适配 Studio 4.1<br>新增 IDEA 中文包插件<br>新增 findViewById 生成插件](https://github.com/getActivity/StudioPlugins/commit/7de069c922d8f93b423ab13490bda6dc6549ce9d)

* 2020 年 8 月 9 日：[<br>更换英文翻译插件<br>新增彩虹括号插件<br>代码预览小窗口插件](https://github.com/getActivity/StudioPlugins/commit/17ff49b9e15337bb79999588651875166e8f5d8a)

* 2020 年 5 月 18 日：[<br>新增远程仓库依赖插件](https://github.com/getActivity/StudioPlugins/commit/f3a21eaa8792c0fd32ab8097077a0b5b90d2b4a4)

* 2020 年 5 月 16 日：[<br>新增远程仓库依赖插件<br>更新 Java 代码约束插件版本]()

* 2020 年 3 月 30 日：[<br>新增 Json 转 Kotlin Bean 插件<br>新增 Json 格式化插件](https://github.com/getActivity/StudioPlugins/commit/0680b8970dd04eeede6ed8f5f4b7799c7a8c1cfb)

* 2020 年 3 月 21 日：[<br>新增一个英文翻译插件](https://github.com/getActivity/StudioPlugins/commit/e14b5c6c5470bce8b43a77f9b89ae19942240f56)

* 2020 年 3 月 14 日：[<br>新增 Java 代码约束插件<br>新增 Drawable 预览插件<br>新增 Json 转 Bean 插件<br>新增 Parcelable 序列化插件](https://github.com/getActivity/StudioPlugins/commit/fd552c014e936cdc6f6044818dd5de983efa89c4)

</details>

#### 插件导航

* [英文翻译插件](#英文翻译插件)

* [Drawable 预览插件](#drawable-预览插件)

* [远程仓库依赖插件](#远程仓库依赖插件)

* [代码定位插件](#代码定位插件)

* [序列图插件](#序列图插件)

* [Java 代码约束插件](#java-代码约束插件)

* [Parcelable 序列化插件](#parcelable-序列化插件)

* [Json 转 Java Bean 插件](#json-转-java-bean-插件)

* [Json 转 Kotlin Bean 插件](#json-转-kotlin-bean-插件)

* [复制到访达插件](#复制到访达插件)

* [彩虹括号插件](#彩虹括号插件)

* [Json 助手插件](#json-助手插件)

* [IDEA 中文包插件](#idea-中文包插件)

* [Markdown 插件](#markdown-插件)

#### 英文翻译插件

* 插件名称：[Translation](https://plugins.jetbrains.com/plugin/8579-translation)

* Github：[TranslationPlugin](https://github.com/YiiGuxing/TranslationPlugin)

* 下载地址：[点我下载插件](plugin/TranslationPlugin-3.3.1-203.zip)

* 插件简介：我们在 Review 代码或者注释时，偶尔会对某个单词或者句子感到陌生，多数人会选择到第三方软件或者网站去翻译，但是这一来二去也是相对比较麻烦，这个时候你只要装上这款插件，即可在 Studio 中直接翻译，这样可以大大提高我们对代码的专注度。

* 插件文档：选中欲翻译的英文单词或者句子，鼠标右击选择 Translate（默认为第一个选项），如果是翻译某个 API 文档，可以直接右击选择 Translate Documentation。在 Studio 窗口右下角可以选择翻译引擎（谷歌、有道、百度），在工具栏上面有翻译的按钮，点击会弹出翻译小窗口。

![](picture/Translation.gif)

#### Drawable 预览插件

* 插件名称：[Android Drawable Preview](https://plugins.jetbrains.com/plugin/10730-android-drawable-preview)

* Github：[Android-drawable-preview-plugin](https://github.com/mistamek/Android-drawable-preview-plugin)

* 下载地址：[点我下载插件](plugin/AndroidDrawablePreview-1.1.5.zip)

* 插件简介：这是一款在 Studio 上预览图片资源缩略图的插件，能帮我们快速定位欲查找图片的位置，除此之外还支持显示 xml 资源的缩略图。

* 插件文档：安装成功后重启，即可通过 drawable 或者 mipmap 文件夹进行预览图片。

![](picture/AndroidDrawablePreview.gif)

#### 远程仓库依赖插件

* 插件名称：[GoogleLibraryVersionQuerier](https://plugins.jetbrains.com/plugin/14251-google-library-version-querier)

* Github：[GoogleLibraryVersionQuerier](https://github.com/wuyr/GoogleLibraryVersionQuerier)

* 下载地址：[点我下载插件](plugin/GoogleLibraryVersionQuerier-3.3.zip)

* 插件简介：这是一款能帮助你快速添加远程依赖库和查询历史版本的插件。

* 插件文档：在 Gradle 中输入想要添加的仓库名称即可联想到对应的依赖库，鼠标右击选择 `Query Available Versions` 可查询这个依赖库的历史版本。

![](picture/GoogleLibraryVersionQuerier.gif)

#### 代码定位插件

* 插件名称：[CodeLocator](https://plugins.jetbrains.com/plugin/17447-codelocator)

* Github：[CodeLocator](https://github.com/bytedance/CodeLocator)

* 下载地址：[点我下载插件](plugin/CodeLocatorPlugin-1.2.3.zip)

* 插件简介：CodeLocator 是一个包含 Android SDK 与 Android Studio 插件的 Android 工具集（目前仅支持Mac），支持在真机调试中进行快速定位代码及 UI 纠正，开发必备利器。

* 插件文档：[集成文档](https://github.com/bytedance/CodeLocator/blob/main/README.md)、[使用文档](https://github.com/bytedance/CodeLocator/blob/main/how_to_use_codelocator_zh.md)

![](picture/CodeLocatorPlugin.gif)

#### 序列图插件

* 插件名称：[SequenceDiagram](https://plugins.jetbrains.com/plugin/8286-sequencediagram)

* Github：[SequencePlugin](https://github.com/Vanco/SequencePlugin)

* 下载地址：[点我下载插件](plugin/SequenceDiagram-2.1.8.zip)

* 插件简介：这是一款能根据代码自动生成 UML 的插件，可以说是阅读源码的神器。

* 插件文档：在方法名右击，然后选择 `Sequence Diagram` 即可查看对应的 UML 图，不仅如此，插件还支持导出到图片，还支持配置 UML 图中的调用链的深度，十分方便。

![](picture/SequenceDiagram.jpg)

#### Java 代码约束插件

* 插件名称：[Alibaba Java Coding Guidelines](https://plugins.jetbrains.com/plugin/10046-alibaba-java-coding-guidelines)

* Github：[p3c](https://github.com/alibaba/p3c)

* 下载地址：[点我下载插件](plugin/AlibabaJavaCodingGuidelines-2.1.1.zip)

* 插件简介：这是阿里巴巴开发的一款代码约束插件，当我们的代码不符合规范时，会有相应的警告提示，能够帮助我们在开发中提升代码质量。

* 插件文档：安装成功后重启，插件在发现预览 Java 类中发现不规范的地方会有黄色的警告。

![](picture/AlibabaJavaCodingGuidelines.gif)

#### Parcelable 序列化插件

* 插件名称：[Android Parcelable code generator](https://plugins.jetbrains.com/plugin/7332-android-parcelable-code-generator)

* Github：[android-parcelable-intellij-plugin](https://github.com/mcharmas/android-parcelable-intellij-plugin)

* 下载地址：[点我下载插件](plugin/AndroidParcelableCodeGenerator-0.8.0.jar)

* 插件简介：在日常开发中，我们不可避免要对 Bean 类序列化，而序列化方式有两种，一种是 Serializable，实现方式比较简单但是比较耗性能，另外一种是 Parcelable，相比 Serializable 性能更好，但是实现过程比较麻烦，这时这款插件发挥的作用就恰到好处了，它能够帮我们节省整个繁琐的实现过程。

* 插件文档：在 Bean 类中右击，选择 `Generate` -> `Parcelable`，然后选择需要序列化的字段即可。

![](picture/AndroidParcelableCodeGenerator.gif)

#### Json 转 Java Bean 插件

* 插件名称：[GsonFormat](https://plugins.jetbrains.com/plugin/7654-gsonformat)

* Github：[GsonFormat](https://github.com/zzz40500/GsonFormat)

* 下载地址：[点我下载插件](plugin/GsonFormat-1.6.0.jar)

* 插件简介：这是一款能够帮助我们将后台返回的 Json 转换成 Java Bean 类中的字段的插件，可极大提升我们的调试接口的效率及准确度。

* 插件文档：在 Bean 类中右击，选择 `Generate` -> `GsonFormat`，输入后台返回的 Json 数据即可转换成 Java Bean。

![](picture/GsonFormat.gif)

#### Json 转 Kotlin Bean 插件

* 插件名称：[JSON To Kotlin Class](https://plugins.jetbrains.com/plugin/9960-json-to-kotlin-class-jsontokotlinclass-)

* Github：[JsonToKotlinClass](https://github.com/wuseal/JsonToKotlinClass)

* 下载地址：[点我下载插件](plugin/JsonToKotlinClass-3.7.3.zip)

* 插件简介：这是一款能够帮助我们将后台返回的 Json 转换成 Kotlin Bean 类中的字段的插件，可极大提升我们的调试接口的效率及准确度。

* 插件文档：在 Bean 类中右击，选择 `Generate` -> `Convert Json Into Kotlin Class`，输入后台返回的 Json 数据即可转换成 Kotlin Bean。

![](picture/JSONToKotlinClass.gif)

#### 复制到访达插件

* 插件名称：[CopyToFinder](https://plugins.jetbrains.com/plugin/13517-copytofinder)

* Github：[CopyToFinder](https://github.com/TimmyOVO/CopyToFinder)

* 下载地址：[点我下载插件](plugin/CopyToFinder-1.7.jar)

* 插件简介：用过 macOs 系统的同学，应该有遇到过一个问题，可以复制 Finder 的文件到 Studio 上，但是 Studio 却无法复制文件到 Finder 上，而这个插件恰好解决了这个痛点，这样的插件你爱了吗？

* 插件文档：使用 **⌘ + C** 并使用 **⌘ + V** 将文件复制到 ide 内部；如果要剪切文件，请使用 **⌘ + ⌥ + V**。

#### 彩虹括号插件

* 插件名称：[RainbowBrackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)

* Github：[intellij-rainbow-brackets](https://github.com/izhangzhihao/intellij-rainbow-brackets)

* 下载地址：[点我下载插件](plugin/RainbowBrackets-6.23.zip)

* 插件简介：这是一款能够增强代码括号的辨识度的插件

* 插件文档：安装后重启即可看到效果

![](picture/RainbowBrackets.png)

#### Json 助手插件

* 插件名称：[JsonHelper](https://plugins.jetbrains.com/plugin/13873-json-helper)

* 下载地址：[点我下载插件](plugin/JsonHelper-1.1.2.zip)

* 插件简介：当日志打印的 Json 没有经过格式化的时候，我们 Review 起来会非常困难，这时可以利用这款插件对 Json 文本进行格式化，相比我们去网页格式化，这种方式极大提高了我们的效率。

* 插件文档：不需要任何快捷键，只需要找到 Studio 窗口最右边，即可找到 `Json Helper` 选项，点击即可。

![](picture/JsonHelper.gif)

#### IDEA 中文包插件

* 插件名称：[Chinese Language Pack Plugins](https://plugins.jetbrains.com/plugin/13710-chinese-simplified-language-pack----)

* 下载地址：[点我下载插件](plugin/ChineseLanguagePackPlugins-211.311.jar)

* 插件简介：IDEA 官方出品的中文汉化包，官方出品的中文汉化包，官方出品的中文汉化包，重要的事情说三遍！

* 插件文档：直接安装重启即可，如果需要换回英文版的，只需要在插件管理中禁用即可。

![](picture/ChineseLanguagePackPlugins.jpg)

#### Markdown 插件

* 插件名称：[Markdown](https://plugins.jetbrains.com/plugin/7793-markdown)

* Github：[Markdown](https://github.com/JetBrains/intellij-community/tree/master/plugins/markdown)

* 下载地址：[点我下载插件](plugin/Markdown-202.6397.21.zip)

* 插件简介：IDEA 官方出品的 Markdown 插件，会自动高亮 md 文档中的语法，用来看 md 文档效果不错

* 插件文档：打开 md 格式的文件即可看到效果

![](picture/Markdown.jpg)

#### 作者的其他开源项目

* 安卓技术中台：[AndroidProject](https://github.com/getActivity/AndroidProject) ![](https://img.shields.io/github/stars/getActivity/AndroidProject.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidProject.svg)

* 安卓技术中台 Kt 版：[AndroidProject-Kotlin](https://github.com/getActivity/AndroidProject-Kotlin) ![](https://img.shields.io/github/stars/getActivity/AndroidProject-Kotlin.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidProject-Kotlin.svg)

* 权限框架：[XXPermissions](https://github.com/getActivity/XXPermissions) ![](https://img.shields.io/github/stars/getActivity/XXPermissions.svg) ![](https://img.shields.io/github/forks/getActivity/XXPermissions.svg)

* 吐司框架：[ToastUtils](https://github.com/getActivity/ToastUtils) ![](https://img.shields.io/github/stars/getActivity/ToastUtils.svg) ![](https://img.shields.io/github/forks/getActivity/ToastUtils.svg)

* 网络框架：[EasyHttp](https://github.com/getActivity/EasyHttp) ![](https://img.shields.io/github/stars/getActivity/EasyHttp.svg) ![](https://img.shields.io/github/forks/getActivity/EasyHttp.svg)

* 标题栏框架：[TitleBar](https://github.com/getActivity/TitleBar) ![](https://img.shields.io/github/stars/getActivity/TitleBar.svg) ![](https://img.shields.io/github/forks/getActivity/TitleBar.svg)

* 悬浮窗框架：[XToast](https://github.com/getActivity/XToast) ![](https://img.shields.io/github/stars/getActivity/XToast.svg) ![](https://img.shields.io/github/forks/getActivity/XToast.svg)

* Shape 框架：[ShapeView](https://github.com/getActivity/ShapeView) ![](https://img.shields.io/github/stars/getActivity/ShapeView.svg) ![](https://img.shields.io/github/forks/getActivity/ShapeView.svg)

* 语种切换框架：[MultiLanguages](https://github.com/getActivity/MultiLanguages) ![](https://img.shields.io/github/stars/getActivity/MultiLanguages.svg) ![](https://img.shields.io/github/forks/getActivity/MultiLanguages.svg)

* Gson 解析容错：[GsonFactory](https://github.com/getActivity/GsonFactory) ![](https://img.shields.io/github/stars/getActivity/GsonFactory.svg) ![](https://img.shields.io/github/forks/getActivity/GsonFactory.svg)

* 日志查看框架：[Logcat](https://github.com/getActivity/Logcat) ![](https://img.shields.io/github/stars/getActivity/Logcat.svg) ![](https://img.shields.io/github/forks/getActivity/Logcat.svg)

* Android 版本适配：[AndroidVersionAdapter](https://github.com/getActivity/AndroidVersionAdapter) ![](https://img.shields.io/github/stars/getActivity/AndroidVersionAdapter.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidVersionAdapter.svg)

* Android 代码规范：[AndroidCodeStandard](https://github.com/getActivity/AndroidCodeStandard) ![](https://img.shields.io/github/stars/getActivity/AndroidCodeStandard.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidCodeStandard.svg)

* Android 开源排行榜：[AndroidGithubBoss](https://github.com/getActivity/AndroidGithubBoss) ![](https://img.shields.io/github/stars/getActivity/AndroidGithubBoss.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidGithubBoss.svg)

* 表情包大集合：[EmojiPackage](https://github.com/getActivity/EmojiPackage) ![](https://img.shields.io/github/stars/getActivity/EmojiPackage.svg) ![](https://img.shields.io/github/forks/getActivity/EmojiPackage.svg)

* 省市区 Json 数据：[ProvinceJson](https://github.com/getActivity/ProvinceJson) ![](https://img.shields.io/github/stars/getActivity/ProvinceJson.svg) ![](https://img.shields.io/github/forks/getActivity/ProvinceJson.svg)

#### 微信公众号：Android轮子哥

![](https://raw.githubusercontent.com/getActivity/Donate/master/picture/official_ccount.png)

#### Android 技术 Q 群：10047167

#### 如果您觉得我的开源库帮你节省了大量的开发时间，请扫描下方的二维码随意打赏，要是能打赏个 10.24 :monkey_face:就太:thumbsup:了。您的支持将鼓励我继续创作:octocat:

![](https://raw.githubusercontent.com/getActivity/Donate/master/picture/pay_ali.png) ![](https://raw.githubusercontent.com/getActivity/Donate/master/picture/pay_wechat.png)

#### [点击查看捐赠列表](https://github.com/getActivity/Donate)

## License

```text
Copyright 2020 Huang JinQun

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```