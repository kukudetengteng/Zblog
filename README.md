ZblogForMobile
=======

一个Java编写的Blog系统，专为移动互联网，微信设计。
---------------

### 核心功能
1.	文章/页面发布、分类、统计阅读次数。
2.	提供文章形式的RSS聚合。
3.	提供链接的添加、归类功能。
4.	附件上传添加管理功能。
5.	评论的管理，垃圾信息过滤功能。
6.	文章静态html页面生成。
7.	会员注册登录，后台管理功能。
8.	lucene实现的站内搜索。
9.	防xss、csrf攻击。
10.	支持metaWeblog Api(支持windows live writer等离线博客编写)
11.	WordPress站点xml文件导入功能(支持文章、附件及标签)
12.	文章标签tag功能、私密文章支持、文章归档
13.	文章markdown/富文本编辑支持、快速编辑
14.	响应式布局支持

#### TODO
*	移动端自适应
*	微信登录
*	微信认证

### 技术选型

#### 后端
* Ioc容器 Spring
* Web框架 SpringMVC
* Orm框架 MyBatis
* 安全权限 Shiro
* 搜索工具 Lucene
* 缓存 Ehcache
* 静态化 FreeMarker
* 视图模板 Jsp/Jstl/JspTaglib
* 其它 Jsoup(xss过滤)、fastjson、IKAnalyzer

#### 前端
* jQuery js框架
* Bootstrap 后台界面
* UEditor/EpicEditor 编辑器
* WebUploader 文件上传
* font-wesome/icomoon.io 字体/图标

### 支持浏览器
* 前台 ie6+
* 后台 chrome/firefox/ie9+
  
### 作者博客
* 新作者：腾腾，微信XP-TengTeng
* 原作者：(http://www.zhouhaocheng.cn)
* 原作者项目：https://github.com/dongfangshangren/Zblog

### 感谢
* 感谢“东方上人"的Zblog，ZblogForMobile在Zblog基础上修改
