---
layout: cv
title: clc
pdf: true
---

# 陈良长 __简历__

<div id="webaddress">
<i class="fi-bookmark" style="margin-left:1em"></i> 前端开发工程师
<i class="fi-social-blogger" style="margin-left:1em"></i>
<a href="http://blog.clcc.dev" style="margin-left:0.5em" target="_blank">博客</a>
<i class="fi-social-github" style="margin-left:1em"></i>
<a href="https://github.com/besfro" style="margin-left:0.5em" target="_blank">个人主页</a>
<i class="fi-telephone" style="margin-left:1em"></i>15220188250
<i class="fi-mail" style="margin-left:1em"></i>
<a href="mailto:121074147@qq.com" style="margin-left:0.5em">121074147@qq.com</a>
</div>

<span class="divline"></span>
<span class="divline"></span>

## 个人简介
我来自广东汕头。电子商务专业，大学时代开始接触网站开发。<br>
2013年开始专注于前端开发至今。
在线版 <a href="https://besfro.github.io/cv" target="_blank">besfro.github.io/cv</a> 

## 个人经历

### __酸桃数据 2018.9 - 至今__
<span class="grap">_直播,短频的大数据分析平台, 服务超过2000家公会_</span>  
我在酸桃工作有旧项目的维护和优化; 新项目搭建，前端业务开发; 还有前端工程化。

&nbsp;  
#### __酸桃数据分析平台__
<span class="grap">_这是一个对短视频和直播进行数据收集、统计、分析的平台。服务于公会。_</span>  
项目采用 Vue + Element UI + Router + Vuex + Webpack4 的技术架构。  
我是前端负责人, 负责常规功能迭代开发、新项目搭建、还有一些重要事项  

项目业务拆分, 由于业务发展，原先整合在一起的短视频和直播的业务需要拆分成2个独立的项目分开运营。  
- 公共组件的抽取  
	除UI库外, 项目组件约80个, 公用组件占50%左右。需要达到共用组件在拆分用的复用, 和便捷引入。将公用组件抽取并作为组件库, 搭建私有NPM管理组件库
- 业务拆分后子域名间实现共享登录
  拆分后业务在不同子域, 需要达到 a.my.com 登录 b.my.com 同步登陆效果。最终使用顶域cookie来存储登陆token实现共享登陆

项目的优化
- 性能优化, 首次访问控制在1～1.5s之间
- 构建效率优化


&nbsp;  
#### __抢推荐位 Chrome 扩展__
这是一个针对dou音运营后台抢推荐位功能的辅助工具。  
热门位置抢位率从5%提升到40%～60% 
- 修改 header x-frame-option 以

&nbsp;  
#### __Switch Host Chrome 扩展__
这是一个host方案快速切换工具。 
- 解决需要在多种环境进行切换的问题
- 解决原先应用级host工具的缓存问题

&nbsp;  
#### __其他__
酸桃数据小程序  
酸桃数据艺人版小程序  
财务系统（vue + bootstrap + Router + webpack4）  
产品手册 (docsify)  
git-flow 优化项目流程

<br/>

### __慧择网 2015.12 - 2018.8__ 
<span class="grap">_互联网保险平台，服务超过3000万用户。我在开放平台事业部（后成立品牌齐欣），参与多个项目前端开发和维护_</span>

<br/>

#### __齐欣AP__
<span class="grap">_一个专注于企业级客户的云端保险平台_</span>  
项目采用 Express + nunjucks + Jquery + insure corejs（内部库） + requireJs + glup 的技术架构。
我负责项目功能迭代开发和业务功能优化
- 优化团单投保业务的效率和容错
- 解决保单查询的一些安全性问题
- 处理保单的数据泄漏问题

<br/>

#### __齐欣CPS__
<span class="grap">_一个提供给B端客户用的CPS门店。_</span>  
项目采用 Express + nunjucks + Jquery + backbone + insure corejs（内部库）+ requireJs + glup 的技术架构。
我负责新项目的开发和后期优化
- MVC框架首次在保险业务的应用
- 产品接口缓存，使用redis缓存产品接口。提升了访问速度, 减少了基础层接口压力。

<br/>

#### __其他__
- 车险项目的移动适配方案, 使用flexable做移动端适配
- verdaccio搭建私有NPM
- gulp构建优化, 静态资源版本控制，解决了发布和CND问题

<span class="divline">-</span>

### __网聚天下科技有限公司 2014.1 - 2015.8__ 

<br/>

#### __云端APP项目__
<span class="grap">_基于hybrid的APP项目，包括购物商城和官网。_</span>

- UI框架appframework应用
- webView于native通信
- CSS动画库（Animate.css）

<span class="divline">-</span>

### __伟驰天下科技有限公司 2011.7 - 2013.12__ 
<span class="grap">_邮件营销公司_</span>  
负责平台UI设计、网站建设、SEO

<span class="divline">-</span>

## 个人作品

#### <i class="fi-link"></i> <a href="https://github.com/besfro/switch-hosts" target="_blank">Switch Hosts</a> 
#### <i class="fi-link"></i> <a href="https://cps.qixin18.com/index" target="_blank">慧择网</a> <span class="deta">_慧择网_</span>
#### <i class="fi-link"></i> <a href="https://www.huize.com/" target="_blank">慧择网</a> <span class="deta">_慧择网_</span>
#### <i class="fi-link"></i> <a href="http://m.huize.com/" target="_blank">慧择网H5</a> <span class="deta">_慧择网H5_</span>
#### <i class="fi-link"></i> <a href="https://cps.qixin18.com/index" target="_blank">齐欣CPS</a> <span class="deta">_齐欣 PC 端的分销项目_</span>
#### <i class="fi-link"></i> <a href="https://www.qixin18.com/" target="_blank">齐欣AP</a>  <span class="deta">_齐欣AP-服务B端多人投保项目_</span>
#### <i class="fi-link"></i> <a href="https://cps.qixin18.com/m/index" target="_blank">齐欣CPS-H5</a> <span class="deta">_齐欣移动端的分销项目_</span>
#### <i class="fi-link"></i> <a href="http://ow.wuyoucloud.com" target="_blank">直播公会</a> <span class="deta">_酸桃数据分析平台_</span>
#### <i class="fi-link"></i> <a href="http://jiusdzsy.s.wsjqq.com/mobile/" target="_blank">微信商城</a>  <span class="deta">_微信购物商城_</span>
#### <i class="fi-link"></i> <a href="http://www.wsjqq.com/m/" target="_blank">微商街</a> <span class="deta">_微信商家导航_</span>
#### <i class="fi-link"></i> <a href="https://github.com/besfro" target="_blank">更多请关注github</a> 

## 技能清单

以下均为我熟练使用的技能
- 移动前端 HTML5/CSS3/响应式
- 编程语言 javascript/node
- 框架/库 vue/backbone/underscore/Jquery/zpeto/Bootstrap
- UI库 Element ui/Antd Vue
- 模块化 requirejs/seajs
- 工程化 webpack/rollup/babel/gulp/grunt/sass
- 开发工具 vscode/sublime/webstorm
- 版本管理/环境 svn/git
- 调试工具 Web Developer/Firebug/Fiddler
- 安全 XSS/CSRF
- 服务端 nginx/express

## 教育经历

- 东北财经大学(专升本) <span class="deta">`2013 - 2016`</span><br>
- 广东科学技术职业学院(专科) <span class="deta">`2008 - 2011`</span><br>

## <i></i>
-  感谢您花时间阅读我的简历，期待能有机会和您共事。

<!-- ### Footer

Last updated: May 2013 -->
