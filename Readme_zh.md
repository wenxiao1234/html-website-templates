# SimpleTodo
# 项目简介
<!--覃美静编写-->
Slides 是一个静态网站构建工具，它通过提供预设计的模板和强大的内置模块，简化了网站创建过程。它非常适合希望快速搭建网站但缺乏专业开发技能的用户。无论是个人博客、商业网站还是作品集展示，Slides 都能帮助用户轻松实现他们的目标。本项目是slides的四个免费的静态网页模板，小组成员着重对四个模板的功能进行分析。

## ✨ 项目特点
<!--覃美静编写-->
以下是Slides项目的特点：
1.基于HTML、CSS和JavaScript构建
- 代码易于理解和修改：项目使用HTML、CSS和JavaScript构建，这些是网页开发的基础技术，代码结构清晰，易于理解和修改，方便开发者根据需求进行定制。
- 与其他Web技术兼容性好：HTML与CSS和JavaScript紧密结合，CSS用于控制页面的视觉呈现，JavaScript为页面注入交互性，三者结合使得开发者能够创建功能强大且视觉吸引力高的网站。
- 可扩展性强：HTML具有良好的可扩展性，随着Web技术的演进，HTML也不断更新，引入了新的标签和属性，以支持更丰富的多媒体内容和交互功能。

2.响应式设计
- 适配多种设备：项目采用了响应式设计，能够适配不同尺寸的设备，包括手机、平板和桌面电脑，确保在各种设备上都能提供良好的用户体验。
- 跨平台性：HTML是跨平台的，同一个HTML文档可以在不同的设备和浏览器上无缝运行，无论使用的是桌面电脑、平板还是手机，HTML文档都能够被渲染并保持相似的视觉效果。

3.动态效果与交互性强
- 丰富的动态效果：利用CSS和JavaScript，项目实现了动态效果，如滑动、淡入淡出等，增强了页面的互动性和视觉吸引力。
- 集成多种交互功能：项目集成了聊天、讨论、邮件收集等功能，提供了丰富的交互性，有助于增强用户参与度和提升销售能力。

4.内置模块丰富
- 多种功能模块：项目包含了多种强大的内置模块，如排版、背景音乐、弹出窗口、用户界面元素等，方便用户进行设置和定制。
- 动画截图功能：提供了动画截图功能，用户可以通过下载模板来查看动画效果，增加了项目的吸引力。

5.SEO优化
- 搜索引擎优化：项目进行了搜索引擎优化，通过使用合适的标题标签、描述性和相关性的meta标签，以及为图片提供文本描述等，提高了在搜索引擎中的可见性，有助于提升网站的排名。

6.多页支持与流行服务集成
- 支持多页网站：支持创建包含多个页面的网站，满足更复杂的需求。
- 集成流行服务：项目集成了流行的服务，如社交媒体分享按钮等，增强了网站的功能性和社交互动性。

7.易于使用与免费模板
- 直观的用户界面：项目提供了直观的用户界面，无需复杂的编程知识即可构建网站。
- 免费模板：项目提供了免费的静态HTML网站模板，用户可以用于个人或商业项目，但不能转售。

8.丰富的文档和教程
- 详细的文档支持：项目提供了详细的文档和教程，帮助用户理解和使用项目。

这些特点使得Slides成为一个功能丰富、易于使用且具有吸引力的网站构建工具，特别适合希望快速上线网站的用户。

## 🚀 快速开始
<!--覃美静编写-->
### 克隆项目

1.打开命令行提示符（Windows 可以用cmd/Terminal/Powershell，Mac 直接用终端）
先在D盘创建新文件
cd D:\github

2.输入命令，复制地址，克隆到自己的仓库：
git clone https://github.com/wenxiao1234/html-website-templates.git

### 安装依赖
slides
根据项目需求，使用合适的 IDE（如 Visual Studio Code 或 IntelliJ IDEA）打开项目并安装依赖项。
如果项目使用 npm，可以运行：npm install

### 启动项目
1.把克隆好的项目在Visual Studio Code中打开，可以清晰地查看文档结构和相应代码
2.如需看具体网页效果，可直接双击index.html（此网页模板由slides生成，需借助此外网网站资源，国内访问需使用加速器）
3.在浏览器中打开生成的文件，查看项目效果
项目将在浏览器中运行:
`file:///D:/github/html-website-templates/Animated%20Landing%20Page%20Website%20Template/index.html`
`file:///D:/github/html-website-templates/Horizontal%20Scroll%20One%20Page%20Template%20Website/index.html`
`file:///D:/github/html-website-templates/One%20Page%20Portfolio%20Website%20Template/index.html`


## 📦 项目结构  

<!--李贵成编写-->
```
Animated Landing Page Website Template/  #动画登陆页面网站模板
├── assets/               # 图片资源
│   ├── img/              # 图片库
│       ├── background/    # 背景图片库
│           ├── img-09.jpg
│           ├── img-14.jpg
│           ├── img-15.jpg
│           ├── img-85.jpg
│           ├── img-89.jpg
│           └── img-95.jpg
│       ├── appstore.jpg    # 苹果软件商店图片
│       ├── googleplay.jpg  # 谷歌应用商店图片
│       ├── image-100.png
│       ├── image-89-1.jpg
│       └── image-89-2.jpg
│   ├── svg/                # 指向性图标库
│       ├── icons.svg       #底片
│       ├── play.svg        #播放按钮
│       ├── video-icon-dark.svg     #黑底播放图标
│       └── video-icon.svg          #白底播放图标    
├── css/
│   ├── slides.css        # 确保网页的正常功能和显示效果。 
│   ├── slides.min.css    # 采用嵌套结构，定义网页元素样式。
│   └── swiper.min.css    # Swiper轮播组件，定义相关样式，支持不同效果与不同设备的适配
├── js/                   # 脚本文件夹
│   ├── plugins.js        # 前端开发插件集合，用于增强网页交互性和改善用户体验
│   ├── slides.js         # 幻灯片展示脚本，用于创建动态、响应式的网页幻灯片展示
│   ├── slides.min.js     # 网页幻灯片展示库
│   ├── soundcloud.min.js   # 背景音乐播放脚本
│   └── swiper.min.js     # 丰富幻灯片展示的插件脚本              
├── manual/               # 提供详细说明和指导的文档
│   └── manual.url        # 快速访问对应的网页，不用手动输入网址
├── scss/                 # 基于 CSS 的预处理器文件
│   ├── colors.scss       # 定义各种颜色
│   ├── dialog.scss       # 对话框
│   ├── flex.scss         # 网页工具
│   ├── framework.scss    # 框架
│   ├── grid.scss         # 网格
│   ├── layout.scss       # 布局
│   ├── mixins.scss       # 开发者工具集
│   ├── plumber.scss      # 排版工具
│   ├── reset.scss        # 重置
│   ├── slides.scss       # 幻灯片
│   ├── typography.scss   # 排版
│   ├── useful-classes.scss     # 网页设计的各种功能
│   └── variables.scss    # 变量 
│                
├── _first-steps.url       # 首页网页链接快捷方式
├── _open-generator.url    # app快捷方式
├── ajax-email.php         # 验证邮箱
├── index.html             # 主界面
└── readme first.txt       # 声明其创建来源为指定的网页
```
```
Horizontal Scroll One Page Template Website/  # 水平滚动单页模板网站
├── assets/             # 图片资源
│   ├── img/              # 图片库
│       ├── background/    # 背景图片库
│           ├── img-26.jpg
│           ├── img-27.jpg
│           ├── img-34.jpg
│           ├── img-60.jpg
│           ├── img-83.jpg
│           ├── img-91.jpg
│           └── img-95.jpg 
│       ├── appstore.jpg
│       ├── gallery-60-1.jpg
│       ├── gallery-60-2.jpg
│       ├── gallery-60-3.jpg
│       ├── googleplay.jpg
│       ├── icon-1.png
│       ├── icon-2.png
│       ├── iphones-34.png
│       ├── watch-26-1.png
│       └── watch-26-2.png
│   ├── svg/                         # 图标库
│       ├── icons.svg                # 底片
│       ├── video-icon-dark.svg      # 黑底播放图标
│       └── video-icon.svg           # 白底播放图标   
├── css/
│   ├── slides.css        # 统一网页风格，布局和交互效果。 
│   ├── slides.min.css    # 样式表,提供一套完整的幻灯片展示解决方案
├── js/                 # 各类脚本文件夹
│   ├── plugins.js        # 前端开发插件集合，用于增强网页交互性和改善用户体验
│   ├── slides.js         # 幻灯片展示脚本，用于创建动态、响应式的网页幻灯片展示
│   ├── slides.min.js     # 网页幻灯片展示库
│   └── swiper.min.js     # 丰富幻灯片展示的插件脚本
├── manual/               # 提供详细说明和指导的文档
│   └── manual.url        # 快速访问对应的网页，不用手动输入网址
├── scss/                 # 基于 CSS 的预处理器文件
│   ├── colors.scss       # 定义各种颜色
│   ├── dialog.scss       # 对话框
│   ├── flex.scss         # 网页工具
│   ├── framework.scss    # 框架
│   ├── grid.scss         # 网格
│   ├── layout.scss       # 布局
│   ├── mixins.scss       # 开发者工具集
│   ├── plumber.scss      # 排版工具
│   ├── reset.scss        # 重置
│   ├── slides.scss       # 幻灯片
│   ├── typography.scss   # 排版
│   ├── useful-classes.scss     # 网页设计的各种功能
│   └── variables.scss    # 变量 
│                
├── _first-steps.url       # 首页网页链接快捷方式
├── _open-generator.url    # app快捷方式
├── ajax-email.php         # 验证邮箱
├── index.html             # 主界面
└── readme first.txt       # 声明其创建来源为指定的网页
```
<!--蔡昀甫编写-->
```
Landing Page Website for App/
├── assets/                      # 静态资源
│   ├── img/                      # 图片资源
│   └── svg/                      # SVG 图标
│       ├── icons.svg             # 图标 SVG 文件
│       ├── video-icon-dark.svg   # 暗色视频图标 SVG 文件
│       └── video-icon.svg        # 视频图标 SVG 文件
├── css/                         # CSS 文件夹
│   ├── slides.css               # 幻灯片样式文件
│   └── slides.min.css           # 压缩后的幻灯片样式文件
├── js/                          # JavaScript 文件夹
│   ├── plugins.js               # 插件脚本文件，包含一些基础插件和工具函数（图片缓存、事件监听、鼠标滚轮事件处理等），提供网站的交互功能
│   ├── slides.js                # 幻灯片脚本文件，实现幻灯片的切换、动画效果、响应式布局等功能，控制幻灯片的显示逻辑和用户交互
│   ├── slides.min.js            # 压缩后的幻灯片文件，与 slides.js 功能相同
│   └── swiper.min.js            # Swiper 插件压缩后的脚本文件，用于实现轮播图功能，提供触摸滑动、自动播放
└── manual/                      # 手动文档文件夹
    └── manual.url               # 手动文档链接文件，可能包含指向外部文档或内部文档的链接

# One Page Portfolio Website Template/
├── assets/                      # 静态资源文件夹
│   ├── img/                      # 图片资源文件夹
│   │   ├── demo.jpg               # 示例图片文件
│   │   └── demo2.jpg               # 示例图片文件
│   ├── svg/                      # SVG 图标文件夹
│   │   ├── icons.svg             # 图标 SVG 文件
│   │   ├── play.svg              # 播放图标 SVG 文件
│   │   ├── video-icon-dark.svg   # 暗色视频图标 SVG 文件
│   │   └── video-icon.svg        # 视频图标 SVG 文件
├── css/                         # CSS 文件夹
│   ├── slides.css               # 幻灯片样式文件
│   └── slides.min.css           # 压缩后的幻灯片样式文件
│   └── swiper.min.css           # Swiper 插件压缩后的样式文件
├── js/                          # JavaScript 文件夹
│   ├── plugins.js               # 包含所需插件的脚本文件
│   ├── slides.js                # 幻灯片脚本文件
│   └── slides.min.js            # 压缩后的幻灯片脚本文件
│   ├── soundcloud.min.js           #音乐播放器插件压缩后的脚本文件
│   └── swiper.min.js            # 插件压缩后的脚本文件
├── manual/                      # 手动文档文件夹
    ├── manual.url               # 手动文档链接文件
├── _first-steps.url             # 初步步骤链接文件
├── _open-generator.url          # 打开生成器链接文件
├── ajax-email.php               # 处理 AJAX 请求的 PHP 文件
├── index.html                   # 主 HTML 文件
├── readme first.txt             # 项目说明文件
```


## 📮 项目主要功能说明与截图
<!--文晓编写-->
一、Animated Landing Page Website Template 
这是一个动画登录页面网站模板，由6个页面组成，侧边栏可以选择要切换到页面。页面布局美观合理。
第一个页面是登录页面，填写好表单可以开始使用，中间有视频教程
![项目界面截图](images/wx/pic0_1.png)
第二、三个页面属于介绍页面，引导人使用其项目
![项目界面截图](images/wx/pic0_2.png)
![项目界面截图](images/wx/pic0_3.png)
第四个页面用来介绍产品，图和视频都能点击查看详情
![项目界面截图](images/wx/pic0_4.png)
第五、六个页面是引导用户试用

二、Horizontal Scroll One Page Template Website
这是一个水平滚动单页网站网站，此网页由7个滚动页面构成，当鼠标下滑时可以向右滚动切换页面。整体界面切换比较流畅，页面切换衔接舒适。
第一个页面点击手表时可使图片聚焦在页面中心
![项目界面截图](images/wx/pic_1.png)
![项目界面截图](images/wx/pic_2.png)
第二个页面点击视频课播放
![项目界面截图](images/wx/pic_3.png)
第三、四个页面点击手表图片可切换不同样式的手表图片
![项目界面截图](images/wx/pic_4.png)
![项目界面截图](images/wx/pic_5.png)
第五个页面点击“购买”会跳转到第一个页面
![项目界面截图](images/wx/pic_6.png)
第六、七个页面是引导用户试用

三.Landing Page Website for App
 这是为移动应用（App）专门设计的着陆页网站。此网页由7个滚动页面构成， 整体界面自适应屏幕大小，界面用户友好性强。
 1.第一个页面有个手机图片，单击可切换图片
![项目界面截图](images/wx/pic2_1.png)
 2.第二个页面有7张图片，单击可查看大图，下方三个模块默认跳转到第一页
![项目界面截图](images/wx/pic2_2.png)
 3.第三个页面是介绍页，单击手机图片可查看大图
 ![项目界面截图](images/wx/pic2_3.png)
 4.其余页面为引导用户试用

四.One Page Portfolio Website Template
这是一个专门设计用于展示个人或公司作品、技能、服务和联系方式等信息的网站模板。整体页面布局合理，图文并茂，介绍详略得当，界面美观。
1.第一个页面以标题和文字为主。
![项目界面截图](images/wx/pic3_1.png)
2.第二个页面和第三个模板一样分为7个图片，单击可查看大图
3.第三个页面是视频、图片与文本结合，布局美观大气
![项目界面截图](images/wx/pic3_2.png)
4.第四个页面是更详细的图文介绍页面，配图美观，单击图片默认跳转第一页
![项目界面截图](images/wx/pic3_3.png)
5.第五张网页有部分文本，有着工作室的联系方式。
![项目界面截图](images/wx/pic3_4.png)

<!--韦荣华编写-->
核心功能：
plugins.js的功能有：
1.实现了一个兼容不同浏览器的鼠标滚轮事件处理插件，通过扩展 jQuery 的方法，方便开发者在项目中使用统一的鼠标滚轮事件处理逻辑。
2.实现了一个功能丰富的触摸事件处理插件，支持滑动、捏合、点击、双击、长按等多种触摸事件，同时兼容不同设备和浏览器，为开发者提供了便捷的触摸交互解决方案。
3.实现了一个功能丰富的社交分享插件，允许开发者在网页上方便地添加多种社交平台的分享按钮，显示分享计数，跟踪分享行为，并提供了打开分享弹窗等功能。
4.实现了图片点击缩放功能，支持键盘快捷键在新窗口打开图片，还处理了滚动、键盘、点击和触摸等事件以控制缩放状态。同时，代码使用了遮罩层和动画效果提升用户体验。
5.组合了多个实用的 JavaScript 模块，为前端开发提供了事件管理、尺寸计算、元素选择、布局管理等功能，Masonry 模块能方便地实现瀑布流布局。每个模块都遵循模块化设计原则，支持多种模块加载方式，便于集成到不同项目中。
6.实现了一个事件发射器 EvEmitter 和一个图片加载检测工具 imagesLoaded。EvEmitter 提供了事件的绑定、触发和移除功能，imagesLoaded 则基于 EvEmitter 实现了图片加载状态的检测，支持检测图片和背景图片的加载情况，并提供了相应的事件回调。
7.实现了一个功能强大的 jQuery 表单插件，支持多种表单提交方式，包括使用 FormData 对象和 iframe 方式，兼容不同浏览器，还提供了表单数据处理、表单重置、字段清空等辅助功能。
8.detectZoom 工具通过多种方法检测浏览器的缩放级别和设备像素与 CSS 像素的比例，根据不同的浏览器环境选择合适的检测方法，为开发者提供了统一的接口来获取这些信息。

slides.js的功能有：
1.用于初始化页面状态、监听事件、根据页面类名配置参数，以及处理页面加载和滑动相关的逻辑。
2.主要实现了幻灯片切换相关的功能，包括显示指定幻灯片、改变幻灯片、点击事件处理以及图片缩放相关操作。
3.主要处理页面滚动和触摸移动事件，根据不同的页面模式（滚动模式或幻灯片模式）执行不同的滚动逻辑，还会在特定条件下切换幻灯片，并在滚动时隐藏下拉菜单。
4.实现了两个核心功能：一是根据页面滚动位置判断 .slide 元素的状态并更新相关样式和触发事件；二是在特定条件下对带有 ae- 类的元素执行滚动动画。
5.实现了三个功能：移动端和桌面端的滑动手势处理、响应式面板布局调整以及滚动时隐藏面板。
6.主要实现了键盘事件处理、导航点和提示框生成、页面内导航链接处理以及导航更新功能。
7.实现了侧边栏的显示、隐藏功能，以及相关的交互逻辑。
8.实现了弹出窗口（popup）的显示、隐藏功能，以及相关的交互逻辑。
9.实现了元素高度自适应和窗口大小变化检测的功能。
10.实现了一个滑块（slider）组件的交互逻辑，包含自动播放、点击切换、控制器操作以及前后切换按钮功能。
11.实现了下拉菜单（dropdown）的显示、隐藏功能，以及社交分享功能。
12.实现了对话框（dialog）的显示、隐藏功能，以及 AJAX 表单提交的相关逻辑。
13.实现了音频播放控制功能，以及设备、浏览器和操作系统的检测功能。

slides.min.js的功能有：
1.主要用于检测用户设备、浏览器、操作系统等信息，并且依据检测结果给 HTML 元素添加对应的 CSS 类，方便后续进行样式定制。

soundcloud.min.js的功能有：
1.实现了一个 SoundCloud 播放器相关的功能，主要分为两部分：第一部分是 window.soundcloud 对象的定义，用于处理 SoundCloud 小部件事件；第二部分是基于 jQuery 实现的播放器 UI 和交互逻辑。
2.实现了一个基于 SoundCloud 的音乐播放器，使用 jQuery 库来操作 DOM 和处理事件。

swiper.min.js的功能有：
1.代码是 Swiper 库的核心实现，Swiper 是一个强大的移动端触摸滑动插件，用于创建轮播图、滑块等交互效果。
2.使用了 Swiper 库来创建两个不同的轮播滑块实例，分别赋值给 window.swiper98 和 window.swiper99。Swiper 是一个流行的移动端触摸滑动插件，可用于创建轮播图、滑块等交互效果。

