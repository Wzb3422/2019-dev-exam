# 2019 研发组最终考核

## 写在前面

现在是你最期待的**最终考核**。不必紧张，不必兴奋，只不过是一次实践所学技术的机会。认真阅读下面的要求，静下心来，或许你会事半功倍。

## 考核安排与要求

### 考核时间

2019年11月10日 13:00 - 17:00

### 考核要求

1. 在 4hrs 的时间内，**尽可能**的完成下面的需求。
2. 不允许与任何人交流。除此之外，**一切**查阅资料的途径都是允许的。
3. 注意你的代码风格与命名规范，优雅的代码人见人爱。

> 命名请使用英文命名，不要使用拼音或者没有语义的字母与数字。
>
> 推荐考核过程中关闭社交软件，或许它也会打扰到你。

## 考核内容

### 需求一 「登录页面」

描述：编写一个**登录页面**。使用云家园账号密码登录成功后，将个人信息显示出来。

要求：

+ **尽可能地**实现页面的样式
+ 个人信息显示方式**尽量**还原（示例视频中是弹框与灰色遮罩）
+ 不能使用 `Ant Design`。除此之外，你可以使用**任何**第三方库/模块
+ 个人信息只需要显示示例视频中的项（姓名、学号、性别、地址、手机号）

加分项：

+ 登陆密码错误处理与提示
+ 模块化思想
+ 页面的细节样式与动画
+ 良好的代码风格与命名规范

会使用到的接口：

+ https://os.ncuos.com/api/user/token
+ https://os.ncuos.com/api/user/profile/basic

> 通过接口获取到 token 之后，凭此 token 请求个人资料接口获取。
> 
> 具体如何使用请自己想办法调试[云家园](https://ncuos.com)登陆页面。

附件：

> + 示例视频与界面截图：[点击下载](http://assets.wzbspace.top/Archive.zip)

### 需求二 「爬取博客并展示」

描述：爬取[该站点](https://blog.snowstar.org)的数据，并显示在页面上。

要求：

+ 爬取所有文章的`标题` `时间` `作者` `概要`，并做相应的存储
+ 能够在页面上展示你所爬取的内容
+ 在页面上能够进行文章搜索
+ 不限编程语言/框架/数据库

提示:

+ **推荐**使用数据库进行数据存储
+ 站点的分页功能，请做好相应的处理
+ 仿写网页源代码无效
+ 有使用数据库需求的，可以使用 `PyMysql` 或 `SQLAlchemy`

加分项：

+ 良好的代码风格
+ 使用数据库并有良好的设计
+ 性能调优
+ 模块化编程

## 提交方式

将需求一、二分别上传到 GitHub 的**两**个仓库上，
**使用命令行的方式**，将代码上传到自己到 GitHub 上，完成后将 GitHub 仓库地址填到**在线收集表**中。

> 在线收集表：[点击进入](https://docs.qq.com/form/fill/DYVd1WndRYU1kbXhG?_w_tencentdocx_form=1)

## 写在最后

尽力而为，放松心态。怀才之人，终将相遇。
