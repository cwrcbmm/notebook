# 三水箱仿真实验系统课程设计

## 最小知识集合


- 数学基础
	- 微分差分方程
- MatLab
	- Simulink

>  使用 Simulink 把模拟的

- Scada
	- Wincc
		- [官方wincc 7.2入门教程](https://cache.industry.siemens.com/dl/files/596/73505596/att_77660/v1/GettingStarted_en-US.pdf)
	- MCGS
		- 工程项目系统分析
		- 工程立项搭建框架
		- 设计菜单基本体系
		- 制作动画显示画面
		- 编写控制流程程序
		- 完善菜单按钮功能
		- 编写程序调试工程

## 简介
### 数学模型

![](http://d.pr/i/1al7D+)

**图像说明**

工作状态

- 泵：
	- 泵<sup>1</sup>，泵<sup>2</sup>供水
	- 泵<sup>3</sup>停用
	- 调整泵<sup>1</sup>，泵<sup>2</sup>转速，使得液位 h<sup>1</sup>,h<sup>2</sup>处于**给定值**
- 连通阀：CV<sup>1</sup>,CV<sup>2</sup>,CV<sup>3</sup>开启
- 泄露阀：LV<sup>1</sup>,LV<sup>2</sup>,LV<sup>3</sup>关闭