# vue-scroll
一个vue的滚动基础组件

组件很简单， 提供了很多接口，使用前需要引入一个库 better-scroll
NPM

better-scroll 托管在 Npm 上，执行如下命令安装：

npm install better-scroll --save
接下来就可以在代码中引入了，webpack 等构建工具都支持从 node_modules 里引入代码：

import BScroll from 'better-scroll'
如果是 ES5 的语法，如下：

var BScroll = require('better-scroll')

安装完成后 就能使用这个基础组件了

这个组件包含两部分 一个是.warpper这么一个外容器 ，当你把组件引入到你的代码是，可以向组件里添加代码
添加的内容会替换到slot插槽中 然后再组件外部分别传入不同的props就可以滚动了 ，组件能监听不同的事件，方便进行交互操作。
