# SurvivalIsland

已经使用Unity5.3.0发布了WebPlayer版本的游戏！ **[亲自体验游戏请点击这里！](http://www.iclojure.com/unity3d/build.html)**需要安装Unity的WebPlayer浏览器插件！推荐使用[Firefox](https://www.mozilla.org/en-GB/firefox/new/)浏览器运行

****

本项目是[unity3xGameDevelopmentEssentials（《Unity 3.x Game Development Essentials》 example for Unity 5.3.0）](https://github.com/whg333/unity3xGameDevelopmentEssentials)的后续僵尸版本。

在前作的基础上添加了阴暗系风格的天空盒、末日系风格的僵尸以及一把反恐精英的M16突击步枪。。。这些元素构成了具有末日僵尸风格的“逃离小岛”游戏！这也是前作ToDoList里最后计划的任务，无论如何总算有模有样了吧！

## 添加的功能
* 玩家（Player）生命值以及得分等GUI
* 玩家摄像头显示前置M16突击步枪以及子弹GUI
* 僵尸动画各个状态机之间的条件转化
* 僵尸攻击（Attack）动画令玩家掉血良好的用户体验
* 根据小岛地形为僵尸生成的A星寻路代理对象
* 僵尸生成器的预制编写，便于设置僵尸出生点
* 玩家鼠标左键开枪射击碰撞检测以及子弹碰撞后的粒子动画显示
* 子摄像头俯视整个小岛作为地图显示
* 为玩家和僵尸设置颜色球形标记在地图上显示
* 其他一些光线细节优化调整

## 截图一览
主菜单提供“阳光版”（前作版本）以及“僵尸版”的游戏选择
![p0](./images/0.png)

由白色淡入后进入“僵尸版”游戏场景，右上角显示了小岛微型地图以及玩家（绿色）和僵尸（红色）的位置
![p1](./images/1.png)

小岛地形为僵尸生成的A星寻路代理对象，浅蓝色即为A星寻路时可以行走的区域范围
![p2](./images/2.png)

看看这里的僵尸——其实是中了尸毒体型变巨大后的女护士。。。
![p3](./images/3.png)

![p4](./images/4.png)

僵尸出生点生成的一大波僵尸正在来袭。。。
![p5](./images/5.png)

在击杀6个僵尸后获得了600分！
![p6](./images/6.png)

在日光照耀下行走于山坡地形的僵尸
![p7](./images/7.png)

这个光线投影映射出了小屋子上的卫星接收器以及背后走来的僵尸背影
![p8](./images/8.png)

开枪击中僵尸的溅血粒子效果
![p9](./images/9.png)

躲在小屋子里面在窗口“爆头”僵尸。。。
![p10](./images/10.png)

点燃火把后的胜利场景与前作版本（“阳光版”）一样
![p11](./images/11.png)

被僵尸挠死后游戏结束！可以点击“再来一次”按钮重新加载“僵尸版”场景再玩一遍！
![p12](./images/12.png)

## ToDoList
好吧，其实还有很多地方可以慢慢细化并完善的！

1. 玩家受到僵尸攻击时画面fade闪红一下，配合玩家的受伤喊叫声效比较好
2. 为僵尸头顶添加矩形血条显示血量
3. M16突击步枪开枪时没有子弹射出的效果。。。而且准心也没有。。。这个是玩过CS的反馈的，确实需要改进
4. 基于状态机的动画效果如何快速切换，例如僵尸生命值为0后立即死亡
5. M16突击步枪的获得、子弹的获得以及地图雷达的获得都可以更富有游戏性，例如隐藏在某些富有挑战性的地方
6. 僵尸的模型源自书籍[《Unity3D手机游戏开发》](http://book.douban.com/subject/25704613/)，最好能找一下炫酷吊炸天的僵尸模型替换一下，最好有多个僵尸模型，做出多个僵尸，然后提供不同的机动性以及攻击性来丰富游戏的可玩性！没错，目标就是像[《求生之路》](http://baike.baidu.com/link?url=qY-K1ei8rc_I1DjIueba2E3UNVPcBotiQlAyytyMYTcQ80Ew_t4B9WiM_yJazswhub_L_R6yZNe7IG_b56yChPDSd3WEeoldaQuNBWCGQZC)的僵尸般多样化！

## Update
**2016.2.17** 添加背景音效以及玩家和僵尸动作音效