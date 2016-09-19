#### #Update 2016-09-16
修改美化 scroll 插件为 nicescroll -> 不需要引用额外的样式文件，减少HTTP请求次数

#### #Update 2016-09-09
更新部分 stylesheets 和 scripts，添加对应的版本号

#### #Update 2016-09-08
jquery-weui 紧急更新到 0.8.2 所有使用 0.8.1 替换，严重BUG

#### #Update 2016-08-25
删除所有的debug版本，调试请删除 ___.min___ 即可

###目前所有资源列表

- bootstrap 3.3.7 > 3.3.6 > 3.3.5
- bootstrap-hover-dropdown 2.0.1
- bootstrap-treeview 1.2.0
- ckeditor 4.5.10
- clipboard 1.5.12
- countUp 1.7.1
- datatables 1.10.12
- fine-uploader 5.11.7 > jquery-fine-uploader 5.10.0
- font-awesome 4.6.3
- highCharts 4.2.5
- hover 2.0.2
- jquery 3.1.0 > 3.0.0 - 2.2.4 - 1.12.4 > 1.9.1
- jquery-bigcolorpicker 2.5.1
- jquery-form 3.51
- jquery-ui 1.12.0 > 1.11.4
- jquery-upload-file 4.0.10
- jquery-validation 1.15.0
- jquery-weui 0.8.1 > 0.8.0 > 0.7.2
- jquery.dataTables 1.10.12
- jquery.mCustomScrollbar 3.1.5
- layer 2.4 > 2.3
- normalize 4.2.0
- slick 1.6.0
- swiper 3.3.1
- underscore 1.8.3
- web-storage-cache 1.0.1
- zepto 1.2.0 > 1.1.6
- zTree 3.5.24
 
#### #Update 2016-08-22

###### bootstrap
更新至 3.3.7

###### ckeditor
非常棒的一个富文本编辑器插件

###### ~~hover~~
~~大家不常使用，暂时从列表中移除（资源文件存在）~~

###### jQuery
更新至: 3.1.0

###### jquery.dataTables
强大的 Table 插件，满足日常，并具有很强的扩展性。它具有多个样式的支持。

###### mCustomScrollbar
小巧、强大的美化滚动条插件

###### bigcolorpicker
较为简单的拾色器插件，满足大部分日常需求

###### jquery-form
扩展 jquery 对 form 的扩展操作，更好的使用 Ajax 提交表单。

###### jQuery-UI 
更新至: 1.12.0 新项目使用最新，就项目不必升级。

###### upload-file
非常好用的 Upload 插件，API 比较齐全，满足日常需求和扩展，适合新手使用。

###### jquery-weui
更新至 0.8.1，具有较大更新，推荐新项目使用该版本。

###### layer
更新至 2.4

###### ~~slick~~
~~因为 Swiper 比较强大。所以删除该插件的提供。~~

###### zepto
更新至 1.2.0

###### zTree
zTree 是一个依靠 jQuery 实现的多功能 “树插件”。优异的性能、灵活的配置、多种功能的组合，是开源免费的软件（MIT 许可证）。
- jquery.ztree.all.min.js 全部功能代码，all.js = core + excheck + exedit ( 不包括 exhide )
- jquery.ztree.core.min.js 核心代码
- jquery.ztree.excheck.min.js 选择功能代码
- jquery.ztree.exedit.min.js 编辑功能代码
- jquery.ztree.exhide.min.js 隐藏功能代码
- zTreeStyle.css 默认风格
- metroStyle.css Bootstrap风格

#### #Update 2016-06-29
名称后面有 ![jQuery logo](https://github.com/chang0022/hotCDN/blob/master/style/jquery.png) 代表依赖jQuery

index.html 页面使用 artTemplateJs 模板引擎。

resource.json 数据源，页面更新通过对此文件的增删改

###### clipboard
不用Flash实现剪贴板功能的轻量级 JavaScript 类库

###### countUp
无依赖的、轻量级的 JavaScript 类库，可以用来快速创建以一种更有趣的动画方式显示数值数据

###### font-awesome
一套绝佳的图标字体库和CSS框架

###### highCharts
功能强大、开源、美观、图表丰富、兼容绝大多数浏览器的纯js图表库，商业收费，破解水印

###### hover
一套基于CSS3的hover 效果 UI，应用于链接，按钮，logo，SVG，图片等

###### jquery-validation
强大的表单验证插件。
- additional-methods.js 扩展功能
- localization/ 本地化

###### slick
强大的轮播插件 官网自称 > the last carousel you'll ever need
- slick-theme.css 样式文件，如需要自定制，就不需要引用

###### swiper
另有一款强大的轮播插件，纯javascript打造的滑动特效插件，面向手机、平板电脑等移动终端，免费、稳定、使用简单、功能强大，是架构移动终端网站的重要选择
- swiper.jquery.js jQuery版本
- swiper.jquery.umd.js 移动端版本

#### #Create 2016-06-23
    └── library // 类库或插件名称
        └── version // 版本号
            ├── library.js  // 源码
            ├── library.min.js // 压缩版本，生产环境使用
	        ├── library.min.map // 用于压缩版本，提供代码调试定位
        	├── library.css // Stylesheet，多见于第三方插件
        	├── library.min.css // 压缩版本，生产环境使用
        	└── others //其他资源文件夹， 如字体文件或图片文件等

###### jQuery
- Version: 1.9.1 适用于需要兼容较低IE浏览器项目
- Version: 1.12.4 最新 1.x.x 版本，兼容 >= IE8
- Version: 2.2.4 最新 2.x.x 版本, 不兼容低版本IE
- Version: 3.0.0 最新 jQuery，更好，更强大。兼容 >= IE11，有对应 jQuery Compat 3.0 版本，兼容 >= IE8

###### jQuery-UI
提供更多原生jQuery交互效果，如拖拽，tab页等
- jquery-ui.structure.css 仅仅拥有结构样式，此版本不引用 images/ 资源

###### underscore
Underscore 是一个 JavaScript 工具库,它提供了一整套函数式编程的实用功能,但是没有扩展任何 JavaScript 内置对象

###### zepto
移动端的js库，轻量级，可与独立插件开发。

###### layer
Web 弹层组件
- layer.js 直接引用，插件自动引入对应的 Stylesheet 文件
- seajs或者requirejs加载layer，需要初始化的配置

###### bootstrap
使用需要引入 Stylesheet 和 JavaScript，依赖 jquery

###### jquery-weui
基于WeUI，微信官方团队针对微信提供的一个H5 UI库，并提供了jQuery/Zepto版本的API实现
- Stylesheet 需要先引用 weui.css，再引用jquery-weui.css
