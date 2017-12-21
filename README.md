# PDUI

PDUI是一套基于WeUI以微信原生视觉体验为基础的样式、组件库，另开发更具便捷，令用户的使用感知更加统一。

## DESCRIPTION
研究了WeUI、ZanUI、Wepy、MinUI 四款小程序组件框架的源码。其中WeUI和ZanUI的编写方式其实不是小程序的自定义组件，而是模块化的编写方式，估计很早就弄好了一直没有更新自定义组件的编写模式。Wepy是腾讯出的小程序开发框架，没有组件只是让我们开发小程序的时候更接近ES6及类似Vue这样的单文件页面及组件开发。MinUI其实就是自己写了一套和Wepy差不多的框架，然后加上自己乱七八糟的组件。在我们组件工程化上，不打算使用Wepy及MinUI的框架模式，虽然他们有接近原生还有我们熟悉的ES6写法和极高质量的工程后配置思想，但是要求他人使用的时候也要使用这种框架及模式。MinUI有提供转原生的接口，但是必须要用它的CIL工具，无疑中又要用户安装及按照其依赖的方式来开发。决定使用和WeUI一样的工程开发配置，希望开发出来的组件，别人可以自己引用甚至单个拷贝走也能用这样，方便其他人阅读及使用。总结一下就是，把WeUI的模块化改成组件化这样，再添加我们自己的UI规范及常用组件。组件结构、总类也按照WeUI的来。PDUI，是一套基于WeUI以微信原生视觉体验为基础的样式、组件库，另开发更具便捷，令用户的使用感知更加统一。