<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bug-hou&show_icons=true&count_private=true&hide=prs&theme=default_repocard"/>
</p>

# WEB前端


侯向毅/男/2001-10

计算机/软件工程

2023年毕业

github:https://github.com/bug-hou

邮箱:2510596084@qq.com

电话:18783477145

## 介绍

于2019年开始接触前端，喜欢编码，有Geek精神，对代码有洁癖，喜欢接触前沿技术，爱折腾。

[阅读vue3部分源码写了一个simple-vue去除了edge case，对核心代码进行实现](https://github.com/bug-hou/simple-vue)

[根据element-plus和naiveui的组件库封装了一个基于vue3组件库，目前已经有30+个组件](https://github.com/bug-hou/monkey-ui)

[基于xhr和promise实现的一个类似于axios的网络请求库，目前只对xhr做了集成，后续会支持微信小程序](https://github.com/bug-hou/nets)

[基于date封装一个日期转化和日期时间对比的库](https://github.com/bug-hou/moodJs)

## 技能

* 掌握：JavaScript/TS(包含ES+) 对JS的闭包，GC，作用域等有自己的认知和看法

* 掌握：vue2/3 框架，以及常用插件vuex，pinia，vue-router，scroll-batter，element-plus，echarts，axios，lodash，dayjs，vant-ui等

* 掌握：计算机网络和基本的数据结构

* 了解：nodejs(express,koa)具有一定的服务器开发能力

* 了解：webpack|rollup|vite 打包工具使用和配置，以及常用 loader 和 plugin 使用

* 了解：原生微信小程序开发

## 实习

:::left

### 腾讯云计算公司(西安)

:::
:::right

### 2022-07-06~2022-09-13

:::
`前端开发` `腾讯云相关项目维护`

* 对腾讯云产品下的音视频控制台业务的维护，并且进行商业化改造,对之前代码进行优化如将产品查询从O(n)的时间复杂程度降到O(1)，对本产品的购买页和附加产品包进行sdk封装，以便于其他产品方便引入我们的购买页，对一些网络请求函数进行柯里化的更改，方便实现参数的复用

* 阅读腾讯云下音视频的部分核心代码，切实的感受到封装对开发重要性，和代码严谨性，并且要考虑很多未知风险，还要对代码进行各种优化，包括平常的测试和发布都要经过审核和灰度等
* 对团队合作和git的使用有了新的认识

## 项目

### 水电务系统

`Vue2.0` `echarts` `Node.JS` `axios`&nbsp;

（数据可视化开发,2020-08 \~ 2021-05）

&nbsp;负责前端构建

* 经历过2次重构，注重性能优化与体验。

* 采用了ES6/ES7的语法，

* 对axios进行二次封装，统一网络请求出口

* 基于echarts进行封装单独的折线图，饼图，柱状图等

* 对一些耦合度高组件进行抽取，实现多复用

### &nbsp;[后台管理系统](https://github.com/bug-hou/vue3admin)

`Vue3.0` `echarts` `element-plus` `type-script`&nbsp;

(后台管理系统，用于对商品的增删改查，会对用户权限编辑)

负责前端构建

* 使用了husky确定提交风格

* 使用eslint+prettier确定代码规范

* 对所有外部引用的库分别进行封装，或者统一出口，确保对库的低复用，方便后续对项目进行重建

* 抽离大量的hooks确保代码的复用性

项目难点

* 权限问题不同的人对应不同权限，及有些页面是否可以访问

* 解决方法：对每一个页面都创建对应的router信息，然后登陆成功后，对满足条件的路由进行注册

* 网络请求过多

* 解决办法：懒加载，数据分页展示，简单实现了防抖和节流，虚拟滚动
