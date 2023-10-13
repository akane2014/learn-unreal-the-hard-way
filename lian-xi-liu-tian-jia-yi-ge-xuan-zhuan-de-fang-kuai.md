# 练习六：添加一个旋转的方块

在许多射击游戏里，都能看到那些放在宝箱里或者悬浮在半空中的枪械，就像这样：

<figure><img src=".gitbook/assets/UnrealEditor_L3jnq3EzEs.gif" alt=""><figcaption><p>游戏中可拾取的枪械</p></figcaption></figure>

我们也可以做到，只是要先从简单的开始，例如一个在空中旋转的方块：

<figure><img src=".gitbook/assets/UnrealEditor_tckjKDuBG3.gif" alt=""><figcaption><p>旋转的方块</p></figcaption></figure>

你只需要创建一个StaticMeshActor（静态网格物体），并用蓝图控制它的旋转即可。但在开始前，还是需要简单的介绍一下什么是Actor。

## Actor是什么？

官方文档里对Actor的定义是：所有可以放入关卡的对象都是 Actor。例如我们在练习三里添加的方形平台就是一个Actor：

<figure><img src=".gitbook/assets/image (4) (1) (1).png" alt=""><figcaption><p>练习三加入的Cube</p></figcaption></figure>

在大纲窗口中就可以看到关卡中每个物品的Type（类别）。具体来说，这个Cube的类别叫做StaticMeshActor，它是Actor的一个子类，是指所有包含静态网格模型的对象。

{% hint style="info" %}
如果你还不熟悉C++的**父类、子类**的概念，可以用生物学的分类来帮助理解。例如犬科是一种动物类别，而狗、狼、豺和狐狸都是它的子类。而狗又有它自己的子类，例如哈士奇、金毛、吉娃娃等。父类描述了所有子类的共性，而子类则包含更具体的特性。
{% endhint %}

{% hint style="info" %}
如果你熟悉Unity引擎，Unity中的GameObject和虚幻引擎中的Actor是非常相似的概念。
{% endhint %}

## 添加一个旋转的方块

