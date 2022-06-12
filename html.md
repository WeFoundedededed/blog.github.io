---
title: 页面、网页
typora-root-url: ../
typora-copy-images-to: uploads
---
# **HTML**

- 超文本标记语言
- 呈现给用户看的界面，网页，应用，小程序等等

### 认识html

- 打开浏览器，右键点击<font color=red size=1>查看网页源代码</font>

  ![图片](/uploads/1652274341978.png)

  能看到页面上有很多的代码，这就是我们的html代码作为页面的支撑，底层

### html的结构

- 我们的网页是由两个部分组成的，分别是`head`部分和`body`部分：

  ```html
  <!DOCTYPE html>//网页的开头
  <html lang="en">//页面标签html，lang是语言，en代表英语，zh-CN代表中文

  <head>//头部标签注意是在html标签里面
      <meta charset="UTF-8">
      <title>Document</title>
  </head>

  <body>
      <div></div>
  </body>

  </html>
  ```