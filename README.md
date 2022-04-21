<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bug-hou&show_icons=true&count_private=true&hide=prs&theme=default_repocard"/>
</p>

阅读vue3部分源码写了一个simple-vue去除了edge case，对核心代码进行实现

基于date封装一个日期转化和日期时间对比的库

## 技能

*   掌握：JavaScript/TS 和 ES6 以上的语法和 api 使用，了解原型链，闭包，作用域，this 指向，

    promise 等

*   掌握：vue2/3 框架，以及常用插件vuex，pinia，vue-router，scroll-batter，element-plus，echarts，axios，lodash，dayjs，vant-ui等

*   掌握：计算机网络和基本的数据结构

*   了解：nodejs(express,koa)具有一定的服务器开发能力

*   了解：webpack|rollup|vite 打包工具使用和配置，以及常用 loader 和 plugin 使用

*   了解：微信小程序开发

## 项目

### 水电务系统

`Vue2.0` `echarts` `Node.JS` `axios`&nbsp;

（数据可视化开发,2020-08 \~ 2021-05）

&nbsp;负责前端构建

*   经历过2次重构，注重性能优化与体验。

*   采用了ES6/ES7的语法，

*   对axios进行二次封装，统一网络请求出口

*   基于echarts进行封装单独的折线图，饼图，柱状图等

*   对一些耦合度高组件进行抽取，实现多复用

### &nbsp;后台管理系统

`Vue3.0` `echarts` `element-plus` `type-script`&nbsp;

(后台管理系统，用于对商品的增删改查，会对用户权限编辑)

负责前端构建

*   使用了husky确定提交风格

*   使用eslint+prettier确定代码规范

*   对所有外部引用的库分别进行封装，或者统一出口，确保对库的低复用，方便后续对项目进行重建

*   抽离大量的hooks确保代码的复用性

项目难点

*   权限问题不同的人对应不同权限，及有些页面是否可以访问

*   解决方法：对每一个页面都创建对应的router信息，然后登陆成功后，对满足条件的路由进行注册

*   网络请求过多

*   解决办法：懒加载，数据分页展示，简单实现了防抖和节流

