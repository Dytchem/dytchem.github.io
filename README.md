# Dytchem's GitHub Web
[dytchem.github.io](https://dytchem.github.io/)



## 趣味迷宫 - 学校Web程序设计选修课大作业
- [Normal Edition](https://dytchem.github.io/maze.html)
- [Hard Edition](https://dytchem.github.io/maze(hard).html)

![场景图](index.files/image001.png)

玩法：
1. 你是蓝色方块，可按W、S、A、D键在迷宫里进行上、下、左、右移动
2. 你的目标是到达黄色地标，这会使你的Score加1
3. 红色方块为敌人，碰到它会使你的Health减1，同时敌人也会消失
4. 绿色方块为友人，碰到它会使你的Health加1，同时友人会瞬移走
5. 敌人5s生成1个，上限400个；友人20s生成1个，上限10个；Health不能超过场上的友人数量+1
6. 你可以按空格键以Score减1的代价发出十字冲击波，它能消灭命中的敌人并同时得到友人的效果
7. 当你的Health为0时，游戏结束，你仍然可以继续游玩，但Health会为红色——刷新网页以重新游戏
8. 在游戏中去争取尽可能大的Score吧

注意：
所有的相关参量都可以通过HTML源码修改，若需游戏平衡性调整可自行进行修改，它们主要集中在JavaScript的常量区



## more...