# ConstraintLayout
实验二约束布局的两种实现
具体代码见master分支

在ConstrainLayout1中实现了任务一
将输入行和整个父容器相约束，其他组件与输入行约束，实现一个计算器界面
效果如下：
<img width="527" alt="5d1afb6d7029e223a550a0ffc4cb08a" src="https://github.com/user-attachments/assets/9e993f1c-4f00-4fcf-bd02-bab8ea131259">
<img width="334" alt="48760fd20a954e8d17989982c954b32" src="https://github.com/user-attachments/assets/519828ea-31f9-4c8d-9e75-fd933301746a">

在ConstraintLayout2中实现了任务二
使用数个布局将这个屏幕划分
顶部的fullscreen_header和底部的fullscreen_end用于填充屏幕，避免组件被模拟机的水滴屏遮挡
首行使用了表格布局实现各个imageview和textview的排列
之后两行使用约束布局，各自用居中的双箭头和星系图片和整个父容器约束
最后一行布置一个按钮
效果如下：
<img width="461" alt="ef7730f29edb263618f24456c6a9bf0" src="https://github.com/user-attachments/assets/2c3b32cd-9f89-48eb-be26-07772a69a353">
<img width="323" alt="fbfebfe8e7670f29a57e8d299d7804a" src="https://github.com/user-attachments/assets/68a6378e-c78f-41d4-a0b9-7cb8ccb6d3c2">
