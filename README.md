# chatgpt
awesome-chatgpt-zh
# [ChatGPT学习](https://chybeta.github.io/2017/08/19/Web-Security-Learning/)



项目地址：https://github.com/CHYbeta/Web-Security-Learning

知识星球【漏洞攻防】：https://t.zsxq.com/mm2zBeq

## 目录

#### 目录：

- 目录
- 网络安全
  - sql注册
    - [MySql](https://github.com/CHYbeta/Web-Security-Learning#mysql)
    - [微软数据库](https://github.com/CHYbeta/Web-Security-Learning#mssql)
    - [数据库](https://github.com/CHYbeta/Web-Security-Learning#postgresql)
    - [数据库](https://github.com/CHYbeta/Web-Security-Learning#mongodb)
    - [技巧](https://github.com/CHYbeta/Web-Security-Learning#技巧)
    - [工具](https://github.com/CHYbeta/Web-Security-Learning#工具)
  - [跨站脚本](https://github.com/CHYbeta/Web-Security-Learning#xss)
  - [CSRF](https://github.com/CHYbeta/Web-Security-Learning#csrf)
  - [其他前端安全](https://github.com/CHYbeta/Web-Security-Learning#其他前端安全)
  - [SSRF](https://github.com/CHYbeta/Web-Security-Learning#ssrf)
  - [XXE](https://github.com/CHYbeta/Web-Security-Learning#xxe)
  - [JSONP注册](https://github.com/CHYbeta/Web-Security-Learning#jsonp注入)
  - [SSTI](https://github.com/CHYbeta/Web-Security-Learning#ssti)
  - [代号执行 / 命令执行](https://github.com/CHYbeta/Web-Security-Learning#代码执行--命令执行)
  - [文件包含](https://github.com/CHYbeta/Web-Security-Learning#文件包含)
  - [文件上传 / 解析漏洞](https://github.com/CHYbeta/Web-Security-Learning#文件上传--解析漏洞)
  - [总编辑漏洞](https://github.com/CHYbeta/Web-Security-Learning#逻辑漏洞)
  - 未授权访问/信息泄露
    - [雷迪斯](https://github.com/CHYbeta/Web-Security-Learning#redis)
  - [RPO（相对路径覆盖）](https://github.com/CHYbeta/Web-Security-Learning#rporelative-path-overwrite)
  - [网页缓存](https://github.com/CHYbeta/Web-Security-Learning#web-cache)
  - PHP相关
    - [弱类型](https://github.com/CHYbeta/Web-Security-Learning#弱类型)
    - [随机数问题](https://github.com/CHYbeta/Web-Security-Learning#随机数问题)
    - [假协议](https://github.com/CHYbeta/Web-Security-Learning#伪协议)
    - [序列化](https://github.com/CHYbeta/Web-Security-Learning#序列化)
    - [php邮件头注入](https://github.com/CHYbeta/Web-Security-Learning#php-mail-header-injection)
    - [其他](https://github.com/CHYbeta/Web-Security-Learning#其他)
    - [php代码审核](https://github.com/CHYbeta/Web-Security-Learning#php代码审计)
  - java-Web
    - [反序列](https://github.com/CHYbeta/Web-Security-Learning#反序列)
    - [结构2](https://github.com/CHYbeta/Web-Security-Learning#struct2)
    - [java-Web代码审查](https://github.com/CHYbeta/Web-Security-Learning#java-web代码审计)
    - [其他](https://github.com/CHYbeta/Web-Security-Learning#其他-1)
  - [python-Web](https://github.com/CHYbeta/Web-Security-Learning#python-web)
  - [节点js](https://github.com/CHYbeta/Web-Security-Learning#node-js)
  - [WAF相关](https://github.com/CHYbeta/Web-Security-Learning#waf相关)
- 尿透测试
  - [课程](https://github.com/CHYbeta/Web-Security-Learning#course)
  - [信息收集](https://github.com/CHYbeta/Web-Security-Learning#信息收集)
  - [汗透](https://github.com/CHYbeta/Web-Security-Learning#渗透)
  - [渗透实战](https://github.com/CHYbeta/Web-Security-Learning#渗透实战)
  - [提权](https://github.com/CHYbeta/Web-Security-Learning#提权)
  - [透透技巧](https://github.com/CHYbeta/Web-Security-Learning#渗透技巧)
  - [运维](https://github.com/CHYbeta/Web-Security-Learning#运维)
  - [DDOS攻击](https://github.com/CHYbeta/Web-Security-Learning#ddos)
- 周大福
  - [技巧总结](https://github.com/CHYbeta/Web-Security-Learning#技巧总结)
- [杂](https://github.com/CHYbeta/Web-Security-Learning#杂)

[ChatGPT创作](https://github.com/OpenMindClub/awesome-chatgpt#general)

### ChatGPT

| 名称                                                         | 简述                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [AirOps ](https://www.airops.com/)                           | AI工具编写 SQL、文档等的速度提高10倍。                       |
| [Writesonic](https://writesonic.com/)                        | 人工智能写作辅助工具，以 10 倍的速度为您的博客、广告、电子邮件和网站创建 SEO 优化且无抄袭的内容。 |
| [Copy](https://www.copy.ai/)                                 | 使用 AI 编写更好的营销文案和内容。                           |
| [Character.AI](https://beta.character.ai/)                   | AI人工交互。                                                 |
| [Fireflies](https://fireflies.ai/)                           | 该工具可插入 Zoom、Teams 或 Webex 等流行的视频会议工具，并自动执行做笔记和创建转录的过程 |
| [JJasper](https://www.jasper.ai/)                            | AI文案写作工具                                               |
| [Outpla](https://outplayhq.com/)                             | 一款功能强大的销售互动软件了。在 Outplay 中获得您在整个销售周期中所需的所有工具的强大功能——适用于新时代团队的一体化销售堆栈。 |
| [cowriter](https://cowriter.org/login)                       | AI辅助写作                                                   |
| [grammarly](https://www.grammarly.com/a?utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&matchtype=b&placement=&network=g&utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&target=&targetid=kwd-298492197778&adgroup=121005009251&device=c&matchtype=b&placement=&network=g&extension=&clickid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclsrc=aw.ds) | 使用 Grammarly 的新人工智能桌面应用程序撰写大胆、清晰、无错误的文章。 |

### 机器学习/人工智能

### ChatGPT绘画

| 名称                                                         | 简述                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [midjourney ](https://www.midjourney.com/home/?callbackUrl=%2Fapp%2F)&&[midjourney 教程](https://www.uisdc.com/midjourney) | AI绘画神器                                                   |
| [Writesonic](https://writesonic.com/)                        | 人工智能写作辅助工具，以 10 倍的速度为您的博客、广告、电子邮件和网站创建 SEO 优化且无抄袭的内容。 |
| [PhotoRoom](https://www.photoroom.com/)                      | 擦除任何背景、对象。                                         |
| [Character.AI](https://beta.character.ai/)                   | AI人工交互。                                                 |
| [printidea](https://printidea.art/)                          | 只需一句话，让你的文字变成画作。                             |
| [JJasper](https://www.jasper.ai/)                            | 一款提供照片修复、抠图、画质增强的在线工具                   |
| [Outpla](https://outplayhq.com/)                             | 人工智能合成创意工具                                         |
| [cowriter](https://cowriter.org/login)                       | 生成各种各样的设计元素,包括logo、插画、图片壁纸等            |
| [grammarly](https://www.grammarly.com/a?utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&matchtype=b&placement=&network=g&utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&target=&targetid=kwd-298492197778&adgroup=121005009251&device=c&matchtype=b&placement=&network=g&extension=&clickid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclsrc=aw.ds) | 二次元ai绘画                                                 |
| [getimg](https://getimg.ai/)                                 | 关键词生成图片的AI工具                                       |
| [dreamlike](https://dreamlike.art/)                          | AI图像生成                                                   |
| [文心一格](https://yige.baidu.com/)                          | AI艺术和创意辅助平台                                         |
| [Phygital+](https://phygital.plus/)                          | AI图像生成                                                   |
| [Beautiful.ai](https://www.beautiful.ai/)                    | AI生成PPT                                                    |
|                                                              |                                                              |

### 机器学习/人工智能

### ChatGPT绘画

| 名称                                                         | 简述                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [midjourney ](https://www.midjourney.com/home/?callbackUrl=%2Fapp%2F)&&[midjourney 教程](https://www.uisdc.com/midjourney) | AI绘画神器                                                   |
| [Writesonic](https://writesonic.com/)                        | 人工智能写作辅助工具，以 10 倍的速度为您的博客、广告、电子邮件和网站创建 SEO 优化且无抄袭的内容。 |
| [PhotoRoom](https://www.photoroom.com/)                      | 擦除任何背景、对象。                                         |
| [Character.AI](https://beta.character.ai/)                   | AI人工交互。                                                 |
| [printidea](https://printidea.art/)                          | 只需一句话，让你的文字变成画作。                             |
| [JJasper](https://www.jasper.ai/)                            | 一款提供照片修复、抠图、画质增强的在线工具                   |
| [Outpla](https://outplayhq.com/)                             | 人工智能合成创意工具                                         |
| [cowriter](https://cowriter.org/login)                       | 生成各种各样的设计元素,包括logo、插画、图片壁纸等            |
| [grammarly](https://www.grammarly.com/a?utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&matchtype=b&placement=&network=g&utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&target=&targetid=kwd-298492197778&adgroup=121005009251&device=c&matchtype=b&placement=&network=g&extension=&clickid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclsrc=aw.ds) | 二次元ai绘画                                                 |
| [getimg](https://getimg.ai/)                                 | 关键词生成图片的AI工具                                       |
| [dreamlike](https://dreamlike.art/)                          | AI图像生成                                                   |
| [文心一格](https://yige.baidu.com/)                          | AI艺术和创意辅助平台                                         |
| [Phygital+](https://phygital.plus/)                          | AI图像生成                                                   |
| [Beautiful.ai](https://www.beautiful.ai/)                    | AI生成PPT                                                    |
|                                                              |                                                              |

### 机器学习/人工智能

### ChatGPT绘画

| 名称                                                         | 简述                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [midjourney ](https://www.midjourney.com/home/?callbackUrl=%2Fapp%2F)&&[midjourney 教程](https://www.uisdc.com/midjourney) | AI绘画神器                                                   |
| [Writesonic](https://writesonic.com/)                        | 人工智能写作辅助工具，以 10 倍的速度为您的博客、广告、电子邮件和网站创建 SEO 优化且无抄袭的内容。 |
| [PhotoRoom](https://www.photoroom.com/)                      | 擦除任何背景、对象。                                         |
| [Character.AI](https://beta.character.ai/)                   | AI人工交互。                                                 |
| [printidea](https://printidea.art/)                          | 只需一句话，让你的文字变成画作。                             |
| [JJasper](https://www.jasper.ai/)                            | 一款提供照片修复、抠图、画质增强的在线工具                   |
| [Outpla](https://outplayhq.com/)                             | 人工智能合成创意工具                                         |
| [cowriter](https://cowriter.org/login)                       | 生成各种各样的设计元素,包括logo、插画、图片壁纸等            |
| [grammarly](https://www.grammarly.com/a?utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&matchtype=b&placement=&network=g&utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&target=&targetid=kwd-298492197778&adgroup=121005009251&device=c&matchtype=b&placement=&network=g&extension=&clickid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclsrc=aw.ds) | 二次元ai绘画                                                 |
| [getimg](https://getimg.ai/)                                 | 关键词生成图片的AI工具                                       |
| [dreamlike](https://dreamlike.art/)                          | AI图像生成                                                   |
| [文心一格](https://yige.baidu.com/)                          | AI艺术和创意辅助平台                                         |
| [Phygital+](https://phygital.plus/)                          | AI图像生成                                                   |
| [Beautiful.ai](https://www.beautiful.ai/)                    | AI生成PPT                                                    |
|                                                              |                                                              |

### 机器学习/人工智能

### ChatGPT绘画

| 名称                                                         | 简述                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [midjourney ](https://www.midjourney.com/home/?callbackUrl=%2Fapp%2F)&&[midjourney 教程](https://www.uisdc.com/midjourney) | AI绘画神器                                                   |
| [Writesonic](https://writesonic.com/)                        | 人工智能写作辅助工具，以 10 倍的速度为您的博客、广告、电子邮件和网站创建 SEO 优化且无抄袭的内容。 |
| [PhotoRoom](https://www.photoroom.com/)                      | 擦除任何背景、对象。                                         |
| [Character.AI](https://beta.character.ai/)                   | AI人工交互。                                                 |
| [printidea](https://printidea.art/)                          | 只需一句话，让你的文字变成画作。                             |
| [JJasper](https://www.jasper.ai/)                            | 一款提供照片修复、抠图、画质增强的在线工具                   |
| [Outpla](https://outplayhq.com/)                             | 人工智能合成创意工具                                         |
| [cowriter](https://cowriter.org/login)                       | 生成各种各样的设计元素,包括logo、插画、图片壁纸等            |
| [grammarly](https://www.grammarly.com/a?utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&matchtype=b&placement=&network=g&utm_source=google&utm_medium=cpc&utm_campaign=11862360197&utm_content=487950050355&utm_term=writing%20assistant&target=&targetid=kwd-298492197778&adgroup=121005009251&device=c&matchtype=b&placement=&network=g&extension=&clickid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclid=EAIaIQobChMI0rj9isO-_gIVqphmAh1lKAozEAAYASAAEgKwDvD_BwE&gclsrc=aw.ds) | 二次元ai绘画                                                 |
| [getimg](https://getimg.ai/)                                 | 关键词生成图片的AI工具                                       |
| [dreamlike](https://dreamlike.art/)                          | AI图像生成                                                   |
| [文心一格](https://yige.baidu.com/)                          | AI艺术和创意辅助平台                                         |
| [Phygital+](https://phygital.plus/)                          | AI图像生成                                                   |
| [Beautiful.ai](https://www.beautiful.ai/)                    | AI生成PPT                                                    |
|                                                              |                                                              |

### 机器学习/人工智能



- [ChatGPT创作](https://github.com/OpenMindClub/awesome-chatgpt#general)

- [ChatGPT](#ChatGPT)

- [Table of Contents](#ChatGPT)
