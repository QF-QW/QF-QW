# 网站初衷:

>你们好,作为我第一个不断完善的网站,真的是辛苦又繁杂,本身个人比较喜欢追求样式美感,但是自己的美感又差,本网站创建到现在进行过两次样式的大改

![wallhaven-gpzve7](imgData/wallhaven-gpzve7-16662477255944.png)

> 本来是想模仿[小楼夜听雨QAQ - 博客园 (cnblogs.com)](https://www.cnblogs.com/phdeblog/)这位的页面的,但是很无奈,某些页面自己跟着模仿的时候可能是开始审美疲劳了,越看越难看

![image-20221020144154117](imgData/image-20221020144154117.png)

> 当然我其实我知道这个我博客模板的github有需要的朋友可以去看看
>
> github:[BNDong/Cnblogs-Theme-SimpleMemory at v1.3.3 (github.com)](https://github.com/BNDong/Cnblogs-Theme-SimpleMemory/tree/v1.3.3)

![image-20221020144605263](imgData/image-20221020144605263.png)

> ​	再再回归正题-----很多人说可以用一些已经有的博客系统没必要自己写,但是吧,自己的博客就好比自己的一个私人空间(出于某些原因,我的微信人员太杂了)
>
> ​	有的时候一些日常的东西也会分享在博客里面,技术分享也是,正因为是自己的一个小天地,那么我就希望这个小天地能越来越好,自己去维护自己去完善,一个属于自己的博客,所以我不打算使用已有的博客系统,其实算是个人的问题吧

# 网站难题:

![83935269_p0](imgData/83935269_p0.jpg)

> 嘛~作为一个菜鸡,这个网站做了我大概一个月吧,不过中途有去学习Linux以及一些其他的,遇到的问题基本上都是一些适配问题.我列举一下吧
>
> 1. Element Plus与Vue3的问题
> 2. editor.md 与 Vue适配问题【创建以及目录显示】
> 3. 后端的话swagger 以及 springsecurity 的配置
>
> 这么一说貌似问题也不大【写到这里又去忙一些事情了，麻烦，哎，哪天要是微信能安静点就好了】

**Element Plus与Vue3:**

> 关于这个我想杀人，Element-ui在Vue3不支持，而Element Plus的Vue3官方文档支持又只有基于vit构建的项目，没有webpack的，导致icon图标只能使用直接导入
>
> 直接导入会导致webstore热加载巨慢。。。。外加那时候去图书馆，带的我的移动显示器，因为HDMI的传输速率太慢，页面一卡一卡的我一直以为我的Vue的内存占用太高了，快气死。。。。。。
>
> 在最后从一篇博客找到了动态加载icon图标，但是是webpack支持的博客，终于解决了问题



**editor.md 与 Vue适配问题【创建以及目录显示】：**

> Vue3禁止script标签，导致editor.md的编写出现问题，好死不死我又不想直接写到index文件里面，想要npm导包
>
> 好家伙editor.md有一个配置和webpack打包冲突，直接寄，我得修改editor.md源码才能用es6导入
>
> 之后还是放下尊严放index里面了
>
> 后面就是TOC目录问题，markdown转html的外部TOC是不能形成折叠目录的只能直接显示，哎之后还是删除了吧有点大丑
>
> ![image-20221020161540878](imgData/image-20221020161540878.png)

**后端的话swagger 以及 springsecurity 的配置**：

[SpringForAll/spring-boot-starter-swagger](https://github.com/SpringForAll/spring-boot-starter-swagger)

> 这位大佬封装的swagger真的是好东西，简化很多，但是要是能把/swagger-ui.html 变成了 /swagger.ui/的事情说出来就好了
>
> 关于 springsecurity ，暂时只看了一下session的实现，token的实现后面再看看吧

# 关于我：

![wallhaven-rdvp8m_3840x1600](imgData/wallhaven-rdvp8m_3840x1600.png)

> 名字：QW-BA
>
> 年龄：**
>
> 兴趣爱好：程序、以及插画
>
> 简述简述：
>
> > 关于我，我平时比较喜欢写代码，但是因为在学校很多的事情所以一直给打乱计划，有的人说事情不多不难，但是主要是心累啊，事情不多但是做下来是心情疲惫而不是什么身体疲惫
> >
> > 





感谢的大佬:

[很漂亮的一个背景控件——ribbons.js - 没有星星的夏季 - 博客园 (cnblogs.com)](https://www.cnblogs.com/shanfeng1000/p/12382643.html)

[ishwy/ribbon.js: ribbon.js: 一条简单的Js就能让你生产随机的彩色的缎带. (github.com)](https://github.com/ishwy/ribbon.js)

中途发现的尤雨溪的介绍网站[Evan You](https://evanyou.me/)

泡沫：

[BluesQian (cnblogs.com)](https://www.cnblogs.com/QianBoy/p/8366290.html)

