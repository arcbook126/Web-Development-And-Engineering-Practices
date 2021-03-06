![](http://www.edzynda.com/images/ethereum-road-network.jpg)

# 我的前端之路


我的前端之路系列文章记述了几年来笔者在前端方面的实践点滴。

# 前言

这是一个最好的时代，也是最坏的时代，我们亲身经历着激动人心的变革，也往往会陷入选择的迷茫。随着浏览器版本的革新与硬件性能的提升，Web 前端开发进入了高歌猛进，日新月异的时代，无数的前端开发框架、技术体系争妍斗艳，让开发者们陷入困惑，乃至于无所适从。特别是随着现代 Web 前端框架（Angular、React、Vue.js）的出现，JavaScript、CSS、HTML 等语言特性的提升，工程化、跨平台、大前端等理论概念的提出，Web 前端开发的技术栈、社区也是不断丰富完善。
任何一个编程生态都会经历三个阶段，首先是原始时期，由于需要在语言与基础的 API 上进行扩充，这个阶段会催生大量的辅助工具。第二个阶段，随着做的东西的复杂化，需要更多的组织，会引入大量的设计模式啊，架构模式的概念，这个阶段会催生大量的框架。第三个阶段，随着需求的进一步复杂与团队的扩充，就进入了工程化的阶段，各类分层 MVC，MVP，MVVM 之类，可视化开发，自动化测试，团队协同系统；这个阶段会出现大量的小而美的库。
Web 前端开发可以追溯于 1991 年蒂姆·伯纳斯-李公开提及 HTML 描述，而后 1999 年 W3C 发布 HTML4 标准，这个阶段主要是 B/S 架构，没有所谓的前端开发概念，网页只不过是后端工程师的顺手之作，服务端渲染是主要的数据传递方式。接下来的几年间随着互联网的发展与 REST 等架构标准的提出，前后端分离与富客户端的概念日渐为人认同，我们需要在语言与基础的 API 上进行扩充，这个阶段出现了以 jQuery 为代表的一系列前端辅助工具。 
2009 年以来，智能手机开发普及，移动端大浪潮势不可挡，SPA 单页应用的设计理念也大行其道，相关联的前端模块化、组件化、响应式开发、混合式开发等等技术需求甚为迫切。这个阶段催生了 Angular 1、Ionic 等一系列优秀的框架以及 AMD、CMD、UMD 与RequireJS、SeaJS 等模块标准与加载工具，前端工程师也成为了专门的开发领域，拥有独立于后端的技术体系与架构模式。 
而近两年间随着 Web 应用复杂度的提升、团队人员的扩充、用户对于页面交互友好与性能优化的需求，我们需要更加优秀灵活的开发框架来协助我们更好的完成前端开发。这个阶段涌现出了很多关注点相对集中、设计理念更为优秀的框架，譬如 React、Vue.js、Angular 2 等组件框架允许我们以声明式编程来替代以 DOM 操作为核心的命令式编程，加快了组件的开发速度，并且增强了组件的可复用性与可组合性。而遵循函数式编程的 Redux 与借鉴了响应式编程理念的MobX都是非常不错的状态管理辅助框架，辅助开发者将业务逻辑与视图渲染剥离，更为合理地划分项目结构，更好地贯彻单一职责原则与提升代码的可维护性。在项目构建工具上，以 Grunt、Gulp 为代表的任务运行管理与以 Webpack、Rollup、JSPM 为代表的项目打包工具各领风骚，帮助开发者更好的搭建前端构建流程，自动化地进行预处理、异步加载、Polyfill、压缩等操作。

## 参考

## 版权

![](https://parg.co/bDY) ![](https://parg.co/bDm)

笔者所有文章遵循 [知识共享 署名-非商业性使用-禁止演绎 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh)，欢迎转载，尊重版权。如果觉得本系列对你有所帮助，欢迎给我家布丁买点狗粮（支付宝扫码）~

![](https://github.com/wxyyxc1992/OSS/blob/master/2017/8/1/Buding.jpg?raw=true)


# 目录

- [2015](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/My-Frontend-Road/2015/Index.md) 
    - [2015-我的前端之路](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2015/2015-%E6%88%91%E7%9A%84%E5%89%8D%E7%AB%AF%E4%B9%8B%E8%B7%AF.md): 2015-我的前端之路：数据流驱动的界面 
    - [From-Zero-To-Front-End-Hero](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2015/From-Zero-To-Front-End-Hero.md): 从路人甲到英雄无敌的前端开发指南 
- [2016](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/My-Frontend-Road/2016/Index.md) 
    - [2016-我的前端之路](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2016/2016-%E6%88%91%E7%9A%84%E5%89%8D%E7%AB%AF%E4%B9%8B%E8%B7%AF.md): 2016-我的前端之路：工具化与工程化 
    - [A-Study-Plan-To-Cure-JavaScript-Fatigue](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2016/A-Study-Plan-To-Cure-JavaScript-Fatigue.md): Background 
    - [How-It-Feels-To-Learn-JavaScript-In-2016](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2016/How-It-Feels-To-Learn-JavaScript-In-2016.md):  
    - [The State of Front-End Tooling 2016 - Results](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2016/The%20State%20of%20Front-End%20Tooling%202016%20-%20Results.md): Q1-总体前端开发经验 
- [2017](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/My-Frontend-Road/2017/Index.md) 
    - [2017-Web 进阶路线图](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2017/2017-Web%20%E8%BF%9B%E9%98%B6%E8%B7%AF%E7%BA%BF%E5%9B%BE.md): 前言 
    - [2017-我的前端之路](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2017/2017-%E6%88%91%E7%9A%84%E5%89%8D%E7%AB%AF%E4%B9%8B%E8%B7%AF.md): 2017-我的前端之路：Web 开发基础 
    - [The-Top-Rising-JavaScript-Trends-To-Watch-In-2017](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2017/The-Top-Rising-JavaScript-Trends-To-Watch-In-2017.md): 2017 值得一瞥的 JavaScript 相关技术趋势 
    - [Top JavaScript Frameworks & Topics to Learn in 2017](https://github.com/wxyyxc1992/Web-Development-And-Engineering-Practices/blob/master/My-Frontend-Road/2017/Top%20JavaScript%20Frameworks%20&%20Topics%20to%20Learn%20in%202017.md): 2017 年值得关注的 JavaScript 框架与主题 
