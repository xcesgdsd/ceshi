准备搭建工作
    1.创建文件夹
        项目文件夹          shoping
        图片文件夹          images
        样式文件夹          css
        产品类图片文件夹    upload
        字体文件夹          fonts
        脚本文件夹          js

    2.创建如下文件
        首页                index.html
        css初始化样式文件    base.css
        css公共样式文件夹    commom.css

    3.模块化开发
        · 有些样式和结构在很多页面都会出现，比如页面头部和底部，大部分页面都有。
        此时，可以把这些结构和样式单独作为一个模块，然后重复使用
        · 这里最典型的应用就是 common.css 公共样式。写好一个样式，
        其余的页面用到这些相同的样式
        · 模块化开发具有重复使用、修改方便等优点
        commom.css 公共样式里面包含版心宽度、清除浮动、页面颜色等公共样式。

    4.网站favicon图标
        1。制作图标
            将png文件转换成ico文件，借助第三方网站即可。例如：比特虫：www.bitbug.net
        2.图标放在根目录下
        3.html页面引入图标，放在html<head>之间
            <link rel="shortcut icon" href=" /favicon.ico" />
    
    5.网站TDK三大标签SEO优化
        SEO译为搜索引擎优化，利用搜索引擎规则提高有关搜索引擎自然排名的方式。
        SEO目的是对网站进行深度优化。
        三大标签：title、description、keyword
        1.title网站标题
            title具有不可替代性。是搜索引擎的最佳判断点
            建议：网站名（产品名）-网站介绍  （不超过30字）
        
        2.description网站说明
            简要说明网站主要做什么

        3.keywords关键字
            页面关键字，搜索引擎关注点之一


首页制作
    常见模块化类名
        快捷导航栏          shortcut
        头部                header
        标志                logo
        购物车              shopcar
        搜索                serach
        热点词              hotwrods
        导航                nav
        导航左侧            dropdown
        导航右侧            navitems
        页面底部            footer
        页面底部服务模块    mod_service
        页面底部帮助模块    mod_help
        页面底部版权模块    mod_copyright
        