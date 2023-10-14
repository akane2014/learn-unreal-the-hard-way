# 练习三：建立一个空白项目

以上两个项目只是上手前的准备工作，从这个练习开始，你要开始动手开工了。

1、创建空白项目

再次运行UE5，来到**项目创建页面**：

<figure><img src=".gitbook/assets/image (8) (1).png" alt=""><figcaption><p><strong>项目创建页面</strong></p></figcaption></figure>

这次选择**Blank（空白）**项目，然后点击**Create（创建）**按钮。

所产生的空白项目会包含一个名为Untitled的关卡，里面是一个默认的地形场景：

<figure><img src=".gitbook/assets/image (15).png" alt=""><figcaption><p>空白模板所生成Untitled关卡</p></figcaption></figure>

2、通过大纲窗口删除默认的地形

上图中用红色框出的部分叫做**Outliner（大纲）**窗口。我们可以通过这个窗口来查看和管理关卡里所包含的内容。收起**大纲窗口**中的文件夹，可以看到关卡结构如下：

![](<.gitbook/assets/image (12).png>)

出于保持关卡内容简洁的目的，我会删除场景中的Landscape（地形）。删除通过右键点击，然后选择Edit->Delete来完成。值得注意的是需要先删除Landscape节点下的子节点，然后删除Landscape节点。

3、通过主工具栏添加一个方形平台

在UE5编辑器上方的一排按钮被称为**主工具栏**（红色框出部分）：

<figure><img src=".gitbook/assets/image (16).png" alt=""><figcaption><p>主工具栏</p></figcaption></figure>

在上个练习里用到的Play按钮就在主工具栏上。现在我们要用的是另一个常用的Create（创建）按钮（图中带有绿色加号的按钮）。

![](<.gitbook/assets/image (14).png>)

然后选择Shape->Cube，点击后会在场景中添加一个正方体。

<figure><img src=".gitbook/assets/image (4) (1) (1) (1).png" alt=""><figcaption><p>关卡中的正方体</p></figcaption></figure>

4、通过细节面板修改正方体的位置和大小

**Details（细节）面板**位于右侧大纲窗口的下方，它显示了所选中的物体的各项参数，例如在Transform下的Position（位置）和Scale（缩放）。把Position后的三个数值（对应XYZ坐标）改成0，同时把Scale后的前两个数值（对应XY方向上的缩放）改成20，我们就得到了一个场景中的平台。

<figure><img src=".gitbook/assets/image (5) (1) (1).png" alt=""><figcaption><p>场景中的平台</p></figcaption></figure>

小技巧：如果物体离得太远或是不在视线范围内，你可以先在大纲窗口中选中该物体（名字是Cube），然后按“f”键，它会将主视窗移动到这个物体面前，以便你刚好能看清整个物体。

这个时候如果你点击Play按钮，你会出现在平台的中央。但和上一个练习的第三视角动作游戏不同的是，你可以在这个场景中任意的漂浮移动。

5、保存关卡

这个20米x20米的平台是目前关卡里唯一的实体内容，下面我们来保存这个关卡。主工具栏的第一个有着磁盘形象的按钮就是保存按钮。点击后系统会提示为尚未命名的关卡命名：

<figure><img src=".gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>保存未命名关卡</p></figcaption></figure>

左侧显示的是当前的保存目录，下方输入关卡的名字，例如MyFirstLevel。然后点击**Save保存**即可。
