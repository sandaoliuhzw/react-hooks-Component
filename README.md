# 做这个项目的目的

首先是了解基本的react项目架构，具备搭建react工程的能力\
主要目的是通过 react hooks 从零封装一些列基础组件，使自己充分掌握 hooks 抽象编程能力，同时在一些列基础组件封装中，巩固dom操作，事件处理，样式等相关前端基础
## 项目架构

使用 Create React App 搭建，并执行了eject\
设置 项目端口为 8086\
添加 eslint 插件，配置全局路径，配置less全局变量\
添加 react router 配置，左侧菜单完成页面跳转\

### 已封装的hooks组件

### 1：左侧菜单
当前路由菜单高亮，根目录'/'首页高亮

### 2：下拉搜索选择器
获焦：右侧三角形旋转，下拉框缓动出来\
失焦：右侧三角形旋转回去，下拉框缓动收起\
搜索输入结束后才开始筛选下拉框内容\
输入框内容变化时，进行下拉框内容筛选\
无搜索结果，显示无匹配项\

