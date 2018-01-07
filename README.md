## 微信 跳一跳 小游戏辅助程序

---

### 功能
1. 程序生成时打包了`adb.exe`。
2. 可以自动识别小人的坐标，以及目标位置。
3. 可以手动控制跳，或是自动跳。


### 帮助：

1. USB数据线连接安卓手机，并打开安卓手机的 USB 调试模式（打开方式请自动百度）。

2. 手动模式：右键 单击小人底部（即 起跳位置），左键单击目标位置。

3. 自动识别模式：
> 1. 如果直接点击 跳 按钮，则会根据自动识别出来的位置跳。
> 2. 如果识别不准确，可手动调整小人位置及目标位置，操作方法参考第2条。

4. 自动跳：该模式下自动识别、自动跳，不需要人工参与。
> 1. 如果设置了跳跃次数，那么分多局游戏，每局游戏开始前，会自动计算一个随机数（n），每一局会比上一局多跳 n 次。
> 2. 如果识别错误，或中间掉下，都会自动开始新的一局游戏，直到跳跃次数达到设置的值。
> 3. 基本上，跳50次，能达到500分左右。
