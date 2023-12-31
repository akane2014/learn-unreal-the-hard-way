# 练习二：运行第三人称游戏模板

这依然是一个轻松愉快的练习，目的是为了体验虚幻引擎如何为你快速的搭建一个基本游戏框架。你要做的是用虚幻引擎提供的游戏模板创建一个第三人称动作游戏。

以下是运行UE5后所看到的**项目创建页面**，我在下图中标出了这个页面的四个功能区。

<figure><img src=".gitbook/assets/image (2) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>项目创建页面的四个功能区</p></figcaption></figure>

1、项目类型选择

对于游戏开发来说，这里只会用到**RECENT PROJECTS（最近的项目）**和**GAMES（游戏）**这两个类别。如果你以前曾经创建过UE5的项目，那么它们会出现在**最近的项目**中。如果这是你第一次运行UE5，选择**GAMES**。

2、游戏类型选择

这里包含引擎官方所附带的游戏模板。一般认为虚幻引擎最擅长的领域是第一人称射击游戏，但Epic也在有意扩展引擎在不同游戏类型上的应用，例如图中可以看到所包含的顶视角游戏。

3、BLUEPRINT和C++的选择

**BLUEPRINT（蓝图）**是虚幻引擎所提供的可视化编程工具，能够让没有编程基础的开发者通过放置节点和连线来实现游戏功能。初学者从BLUEPRINT上手是一个很好的选择。而且无论你在这里选择的是BLUEPRINT还是C++，你都可以在需要的时候同时使用两者，所以不用但心这是一个二选一的难题。另外下面去掉默认勾选的Starter Content（初始内容）可以减少项目所需的空间，但无关紧要。

4、Project Location项目的存放路径和Project Name项目名称

建议根据你的磁盘空间规划一下项目路径以及为项目选择一个便于记忆的名字。不然很可能一段时间以后，你以后会看着一堆叫做MyProject1、MyProject2的目录，不记得哪个是你想找的项目。

确认上述四个功能区的选项后，点击Create（创建）。稍作等待，就会来到UE5的主工作窗口：

<figure><img src=".gitbook/assets/image (3) (1) (1) (1) (1).png" alt=""><figcaption><p>UE5的主工作窗口</p></figcaption></figure>

先不必被各式各样的面板和数据困扰，点击上方绿色的三角形Play按钮，就可以进入游玩模式。进入游玩模式后点击中间的游戏场景窗口，这个窗口会捕捉并隐藏你的鼠标用于人物视角控制，这时你就可以操控你的人物在这个小小的测试场地跑跑跳跳了。进入游玩模式后，也随时都可以按Esc键退出游玩模式。

## 额外挑战

如果你有兴趣，也可以从头再来试试看用其他的游戏类型模板来创建项目。我相信如果你是对游戏开发感兴趣的人，你一定会为此感到兴奋——竟然可以这么快就做出不同的游戏来了！
