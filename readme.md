# reactTeach(tic-tac-toe)
### 介绍
参考[react官方中文入门教程](https://doc.react-china.org/tutorial/tutorial.html)，完成一个井字棋游戏，点击[这里](https://codepen.io/gaearon/pen/gWWZgR)查看效果
### 目的
- 熟悉react环境搭建
- 了解 react 当中包含 元素、组件、props、state 在内的一些概念
### 使用
- 安装依赖包
```
npm install
```
- 启动
```
npm start
```
- 构建
```
npm build
```
### 文件目录
```
├─.gitignore		//git忽略文件
├─package-lock.json	//create-react-app生成的package
├─package.json		//可以自己配置的package ?（几乎已不用再进行配置）
├─readme.md
├─src				//源码文件夹
|  ├─index.css
|  └─index.js
└─public
    ├─favicon.ico
    ├─index.html
    └─manifest.json	//app配置文件
```
### 计划及进度
- 基础：
  - 实现了井字棋游戏的基本规则并可以进行游戏（完成）
  - 能够判断一方获胜（完成）
  - 能够存储每一步时的棋局状态（完成）
  - 允许玩家切换至之前的某一步“悔棋”（完成）
- 拓展：
  - 以 “(1, 3)” 坐标的方式记录每一步，而不是格子序号 “6”
  - 在棋步记录列表里加粗显示当前选中的项目
  - 在 Board 组件中用两个循环渲染出 9 个 Square 格子组件
  - 添加一个切换按钮来升序或降序显示棋步记录列表
  - 当一方获胜时，高亮显示连成一线的3颗棋子
### 更新日志
- 2018.02.07
  - 完成基础目标
  - 添加readme文档