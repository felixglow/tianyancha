# tianyancha

tianyancha--爬取tianyancha网站公司注册信息
========================
帮女朋友减少点工作量 ^_^


按关键字搜索相关公司信息，爬取详情页公司注册信息、联系方式等

生成csv文件

该网站详情页做了防爬措施，json接口无法直接请求。

目前加了delay, 以及自定义middleware处理user-agent, 代理IP。
