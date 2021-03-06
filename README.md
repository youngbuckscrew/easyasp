##EasyASP v3.0

作者 : coldstone (coldstone[at]qq.com)   
官网 : <http://www.easyasp.cn>   
GIT : <https://git.coding.net/coldstone/easyasp.git>   

> git 镜像：   
> GitHub : <https://github.com/coldstone/easyasp.git>   
> osChina : <http://git.oschina.net/coldstone/easyasp>   

Licenses : EasyASP 遵循 [Apache licenses v2](http://zh.wikipedia.org/zh-cn/Apache%E8%AE%B8%E5%8F%AF%E8%AF%81) 版权协议   
   
EasyASP 是一个简单方便的用来快速开发ASP程序的类库。EasyASP 包含完善的全参数化查询多数据库操作、Json数据生成与解析、无组件压缩解压、各种字符串及日期处理函数、动态数组处理、文件系统处理、远程文件及XML文档处理、内存缓存和文件缓存处理、模板引擎等等丰富的功能。而为了解决ASP调试不方便的问题，EasyASP 推出了独创的控制台调试功能以及丰富的异常信息显示，能让你开发 ASP 程序时最大程度的从错误调试的纷繁中解放出来。EasyASP 目前提供下载的是VBScript版本。
   
###EasyASP 的部分功能特点
* [ASP] 大量丰富的字符串处理、正则处理、日期时间、数值格式化及其它通用函数。
* [ASP] 实现高性能的字符串构造类 StringBuilder 。
* [ASP] 强大的表单验证功能，采用链式操作，内置超过30种验证规则，可灵活验证各种类型数据，支持多种方式自定义。
* [ASP] 简单快捷的 Cookies 和 Application 读写。
* [ASP] 支持伪静态（伪Rewrite），且对已开发的程序无影响。
* [ASP] 实现ASP文件的动态载入，并支持无限级的ASP原生include。
* [ASP] 实现高效的对称加密解密，可自定义密钥，且加密后字符串全部为可打印字符。
* [ASP] 独创的插件系统，内置md5、汉字转拼音、翻译、分词等插件，并有丰富的第三方插件提供下载。
* [JSON] 原生 VBScript 实现高效率的 Json 数据解析与生成。
* [JSON] 记录集、集合、N维数组、Easp List 对象和几乎所有ASP内置对象都能直接输出为 Json 格式数据。
* [数据库] 默认支持 Access / MS SQL Server / MySQL Server 数据库，并可以扩展至支持其他任何符合工业标准的数据库。
* [数据库] 能方便的实现一个或多个数据库的读、增、删、改等控制操作，可嵌套标签式的参数操作易用到令人发指。
* [数据库] 提供高效的批量插入、删除、更新，并带有事务处理支持。
* [数据库] 数据库查询使用全参数化，EasyASP 的优秀设计让你大部分情况下不用考虑数据字段的类型，也完全避免了SQL注入的风险。
* [数据库] 简捷的存储过程调用方式，可以很方便的操作输入参数、输出参数、返回一个或多个记录集、返回值、受影响的行数。
* [数据库] 自带简单高效的分页功能，拥有功能丰富的可完全自定义风格配置及调用，内置 `bootstrap` 分页样式。
* [数据库] 自动判断数据库类型及版本号，并能根据数据库的不同类型不同版本自动优化SQL查询语句。
* [数据库] 记录集可以很方便的转换为Json格式数据。
* [控制台] 独创的控制台支持任意 ASP 变量的调试与跟踪。
* [控制台] 控制台支持 SQL 语句及执行时间实时监控。
* [控制台] 控制台支持设置 token 阻止未授权的访问。
* [压缩解压] 纯ASP(VBScript)世面上唯一支持中文文件名的无组件压缩解压。
* [远程文件] 支持自动识别远程文件编码，支持按标签或按正则表达式截取片段，支持批量保存远程图片至本地服务器。
* [远程文件] 能方便的实现 Ajax 跨域代理。
* [超级数组] 支持动态数组及Hash表，支持数组排序、筛选、循环处理及数组间运算。
* [模板引擎] 支持自定义模板标签，支持模板文件无限级include，标签支持无限级循环区块。
* [XML] 支持本地及远程 XML 文档解析，实现仿 jQuery 选择器，节点操作无压力。
* [XML] 提供调用 WebService 的示例。
* [缓存] 支持内存缓存和文件缓存，支持直接缓存记录集。
* [上传] 获授权内建艾恩无组件上传(`MoLibUpload`)——ASP上传界终结者。
* [工具] 提供专用伪静态规则测试工具。
* [工具] 提供 Dreamweaver / EverEdit / EditPlus 等编辑器的代码高亮及代码智能提示插件。
* [工具] 拥有高人气的文档社区，并有大量优秀的文档编辑提供丰富的带示例的API文档支持。
* ……

###交流与反馈
* Bug 提交或功能建议请到 [Coding 讨论区](https://coding.net/u/coldstone/p/easyasp/topic/all) 或官网论坛 [EasyASP问题反馈](http://bbs.easyasp.cn/forum-issue-1.html) 板块。
* EaspASP 官方交流QQ群：`26435555`， 加群验证请输入 `easyasp`，无验证信息不加。