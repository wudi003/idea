Alibaba Java Coding Guidelines
代码检查
Spring Assistant
spring项目创建

CodeGlance
代码缩放


Codota AI Autocomplete for Java and JavaScript
智能代码提示

GenerateAllSetter
自动调用set方法

RestfulToolkit
根据请求查类

Free Mybatis plugin

maven Helper

SpotBugs


Alibaba Java Coding Guidelines 代码规范提醒
CodeGlance 代码编辑区迷你缩放图，当代码行数过多时可以通过预览图快速定位
Codota 智能补全代码，很好用
Database Navigator 可以在idea连接mysql等主流数据库，进行查询等各种操作
Grep Console 控制台彩色分类显示
Lombok 懂得都懂，必备
Easy Javadoc 自动生成 Javadoc 风格注释
Maven Helper 优化Maven操作
MybatisX 官方推荐的 Mybatis-Plus 插件，简化操作
Smart Tomcat 社区版不提供tomcat插件，需要自己下载
Easy Code 自动生成代码 收费版和破解版可以用一下，社区版好像没法用


字符串工具：String Manipulation
String Manipulation 插件提供了非常丰富字符串工具，例如命名替换（ (camelCase, kebab-lowercase, KEBAB-UPPERCASE, snakecase, SCREAMINGSNAKE_CASE, dot.case, words lowercase, Words Capitalized, PascalCase）等。


时序图生成工具：SequenceDiagram
有的时候，我们需要梳理业务逻辑或者阅读源码。从中，我们需要了解整个调用链路，反向生成 UML 的时序图是强需求。其中，SequenceDiagram 插件是一个非常棒的插件。

JSON转领域对象工具：GsonFormatPlus
在开发过程中，我们可能会遇到 json 格式的字符串转换成实体类参数的场景，这个插件可以根据 JSONObject 格式的字符串，自动生成实体类参数。详细使用文档，参考：https://github.com/zzz40500/GsonFormat

https://plugins.jetbrains.com/plugin/14949-gsonformatplus
那么，如何使用呢？我们可以使用 GsonFommat 的快捷键，默认 option + s (mac), alt + s (win) 通过以下方式修改快捷键。或者点击工具栏的 Generate 来唤起生成工具

快捷键提示工具：Key promoter X
Key Promoter X 是一个快捷键提示插件，如果鼠标操作是能够用快捷键替代，Key Promoter X 会提示可以用什么快捷键替代。


SQL Params Setter



CheckStyle
代码格式检查插件的作用主要是为了规范代码格式比如说项目中一行代码最长是多少、项目中有没有无用的引用等等。非常实用！

一般情况下我们会在项目中配置 CheckStyle，并且自定义规则，然后再配置一个Commit 的 Git 钩子，这样我们在Commit代码的时候就会跑一遍 CheckStyle，看看项目代码的格式有问题不。


SonarLint 是一个免费的IDE扩展，允许您在编写代码时修复错误和漏洞！与拼写检查器一样，SonarLint会动态地突出显示代码问题，并提供明确的修复指导，以便在代码提交之前修复这些问题。在流行的IDEs（Eclipse, IntelliJ, Visual Studio, VS Code）和流行的编程语言，SonarLint 帮助所有开发人员编写更好、更安全的代码！


Rainbow Brackets
如果代码没有被格式化的话，阅读起来很痛苦，就算被格式化了，几千行代码，各种if嵌套，阅读起来连个结尾括号都找不到(如果你说你会折叠，当我没说)，也是很痛苦的，此时这个插件就能忙上很大的忙，能帮你快速定位到代码块中的上下文，突出显示，彩虹括号。


VisualVM Launcher
一般可用于在本地开发进行压力测试，性能测试之类的监控器，其他场景一般不推荐使用此模式启动，还会启动另外一个Visual vm窗口，这个窗口是JDK bin目录下的JvisualVM 





代码自动提示快捷键
IntelliJ IDEA安装后是默认自动提示的，通过快捷键(alt+/)的方式弹出提示需要修改快捷键。（一旦设置快捷键方式，以后再还原也不会默认自动提示了。）

File --> Settings --> Keymap --> 搜索Cyclic Expand Word --> 右键选择“Remove Ctrl+/”

搜索Basic --> 右键选择“Add Keyboard Shortcut” --> 按键alt+/ --> OK











