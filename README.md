# 个人信息

- 李燚/男/1991
- 本科/哈尔滨师范大学计算机系
- 手机/微信：17777785210
- Email：js@liyi.im

---

# 技能

- 前端框架：`React-native` / `React` / `HTML5` / `echarts` / `Less`
- 前端工具：`Gulp` / `jQuery` / `chrome开发者工具` / `webpack`
- 版本管理：`Git`
- 掌握技能: `nodejs`/`html` / `css` / `prototype` / `linux` / `jquery`

---

# 工作经历

## 去哪网（2018年06月 ~ 2023年06月）

### node 版QMQ开发

**描述：** 在一些场景下 node 服务需要接入 QMQ 的消息，需要针对 node 开发 QMQ 的中间件  
**职责：** 根据现有 Java 版本功能进行功能迁移，满足基本需求，慢慢迭代  
**结果：** 已在业务线上使用。  
**工具：** node
> 开发 QMQ 的协议
> 开发中碰到很多问题，例如不了解 java 代码，不了解 java 中 buffer 操作和 node 中 buffer 的对应。因为 qmq 的协议是有非常严格的按照字节位置要求的。
> 解决拆包粘包的问题。由于 tcp 链接接收和发送的都是流文件，会导致一些消息在两次接收的返回中

### yapi 数据库迁移

**描述：** 公司对mongo数据库的支持已经停止维护。需要把 yapi 的数据同步到 mysql
**职责：** 负责数据库的同步。同步后的查表代码修改。mysql链接库的选型
**结果：** 会有一部分的数据兼容问题。每次发现后及时修复
**工具：** sequelize node mongo

### QRN单元测试

**描述：** QRN升级回归需要工作量很大，人工测试会有疏漏
**职责：** 
1. 接入官方RN测试case
2. 根据我司现有的QRN组件进行单元测试

**结果：** 经历过一次 RN 升级后得出结论。单元测试可以在一定程度上节约测试时间。整体提效。
**工具：** jest react-native node

### 微信转译工具

**描述：** 微信原生代码转换为 nanachi 代码
**职责：** 以目录为处理单元（json js wxss wxml），主要负责 js json 文件的转换。通过浏览大部分的业务代码，熟悉业务的写法，利用babel完成代码的转换工作。
**结果：** 转化效率为80%左右。剩下部分需要开发人员手动修改。已上线
**工具：** babel node
> nanachi：去哪网多端统一框架。react 写法。与市面 taro 类似。
> 转译：wxml -> jsx, js -> react 中实例方法和生命周期等

### 小程序端自动化测试

**描述：** 为了简化业务回归测试的流程，针对我司内部的多端统一的小程序实现自动化测试
**职责：** 开发server端，以及调用手机进行测试，产出测试报告。主要负责脚本管理（上传，下载，删除），链接手机进行测试和测试终端管理
**工具：** eggjs typescript airtest node
> 难点：每次小程序发布后，运行在手机端时，小程序的xpath都会不同。层级也会变得不一样。最后只能通过图片识别方式进行代码测试。

## 其他

- yapi 安全漏洞修复
- QRN：打包脚本和工具开发支持。转场动画开发
- 微信小程序活动开发（原生写法）
- h5活动页开发（react）
- nanachi 项目的 babel6到babel7的升级。整体编译时间缩短10% 
- 日常维护 yapi，ykit，qpbuilder（node 相关）
- davinci，BI系统。维护，UI改版，新增功能（web 相关）

## 海南易建科技 （ 2016年06月 ~ 2018年06月 ）

### 项目: 大中台前端架构搭建

**描述：** 配合大中台后台架构和设计进行整个前端搭建及平台前端的完善，使用react+webpack构建的单页面应用，项目采用了react、react-router、mobx以及ES6语法，采用组件化思想搭建整个项目，封装一些高度复用的组件，使代码简洁化，优化整体的使用流程和体验。
**职责：** 主要负责整体的前端架构和体验的优化并且参与实施具体的前端开发，配合后端的对接联调，解决浏览器的兼容问题。
**架构：**

> 使用react框架，以及react-router(管理路由)，mobx(管理数据)构建单页面应用。
使用react+webpack构建项目环境。
使用阿里矢量图标库。

### 项目: 兜兜国际版APP开发

**描述：** 根据公司需要开发公司国际版本协同软件，采用新技术进行优化app功能和体验
**职责：** 负责前端的架构和开发,与后端对接联调，解决iOS和Android适配问题。培训和推广react技术
**架构：**
> 使用react-native，mobx(数据管理)和react-native-navigation(路由)构建应用
使用webpack打包压缩代码
项目中解决Modal组件关闭后Alert弹出卡死问题


## 美菜网 （ 2015年7月 ~ 2016年05月 ）

### 项目：零售定价

**描述：** 对传统的前端系统采用`react`重构，完成前后端完全分离，并且配合公司的大前端部门调研统一的前端技术。
**职责：** 调研前后端分离技术angular和react。在这个项目中，重构了之前的前端，按照之前的页面布局，逻辑，验证前后端分离技术的迁移工作。
**架构：** 

> 使用 `React`+`Redux`+`webpack` 开发前端页面。`React`负责页面的绘制，`Redux`负责数据的管理，`webpack`压缩代码，打包上传。

### 项目：售价管理

用echarts制作图表，根据后端提供的数据动态显示，并且显示一定时间段内的变化情况等等。

### 项目：其他

E+店长，自动定价，竞价管理等项目中负责开发页面和前端逻辑以及数据的展示。
主要是使用HTML标记、div+css+jQuery+bootstrap等前端WEB技术进行网站的开发与制造。

## 北京好递软件有限公司 （ 2014年5月 ~ 2015年6月 ）

### 项目：物流系统

负责前端功能和与后台交互，处理后端返回数据。对返回数据进行处理，根据后端返回数据构建H5页面。负责需求中的一些前端验证的js的编写和一些逻辑的处理，根据需求制作页面。

### 项目：下单系统

开发手机端页面H5,功能交互,用jQuery mobile进行开发

---

> 了解一点shell编程知识和chrome extension
熟悉JavaScript，了解ECMAScript基础内容，熟练jQuery
了解JavaScript的作用域链,prototype原型机制,JavaScript的继承
熟练使用Mac、Linux等常规终端命令

# 致谢

> 感谢您花时间阅读我的简历，期待能有机会和您共事。


