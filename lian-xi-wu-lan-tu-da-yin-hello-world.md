# 练习五：蓝图打印Hello world!

虽然我真的很想让你早点开始做有趣的游戏内容，但为了多一点点机会再熟悉下虚幻引擎的界面以及蓝图的基本操作，我们还是像学习所有新的编程语言一样，从“Hello world！”开始吧。

蓝图是一种可视化编程语言。在用虚幻引擎开发游戏时，各个方面都会用到它。例如编写游戏中某种物品的行为、角色动画的控制或者用户界面的内容。但最容易理解的蓝图叫做关卡蓝图（Level Blueprint），它通过主工具栏上的蓝图按钮添加，点击按钮后选择Open Level Blueprint（打开关卡蓝图）。

<figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption><p>打开关卡蓝图</p></figcaption></figure>

选择Open Level Blueprint后打开的就是蓝图编辑器：

<figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption><p>编辑器中的关卡蓝图</p></figcaption></figure>

在编辑器的中央就是编写蓝图脚本的主要工作区了，选择不同的功能节点和按关系连接节点就是可视化编程的工作内容。就像你的桌面、炒菜的厨房或者机箱里的布线一样，保持工作区整洁是提高工作效率的重要因素。搜索关键词Blueprint hell，你就能够体会到杂乱的蓝图脚本所带来的绝望：

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption><p>Blueprint Hell</p></figcaption></figure>

但好在关卡蓝图只有两个默认的事件节点，Event BeginPlay和Event Tick：

1. Event BeginPlay：在关卡刚开始运行时所发生的事件，只会触发一次
2. Event Tick：在关卡运行的每一帧所发生的事件

如果我们想在关卡开始运行的时候打印出“Hello World!”，那就在Event BeginPlay节点后连接一个Print String节点：

![](<.gitbook/assets/image (10).png>)
