## 贪吃蛇小游戏
<p align="center">
    <img src="http://ok7n02kz6.bkt.clouddn.com/FrmfKq7wYl2Ymp-RosTZ-O1Vrh7c.png" alt="clock effect-pic">
</p>

### 实现功能：
- “能吃到果实”并且长度会增加
- 计分
- “碰壁”后，或“蛇身”重叠时游戏自动结束

### 实现过程
- 通过动态绘制div，形成与坐标之间的映射
- 创建“蛇”这个对象：其中包括其身体坐标(数组，其中含有所有的身体坐标)以及方向
- 处理用户输入，判断上下左右键的输入,相应的移动方向
- 检测是否吃到水果(“水果”坐标与“蛇头坐标”一致)
- 检测蛇的死亡，有两种情况：“蛇身”重叠，“蛇头”冲出墙壁
