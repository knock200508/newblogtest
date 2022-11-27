# newblogtest

## 安装hexo

这里使用npm安装hexo

```shell
npm install -g hexo-cli
```

## 初始化博客

```shell
hexo init blog
cd blog
npm install
```

这里的blog用来存放博客文件
执行完成之后运行`hexo server`，访问IP:4000就能看见你的博客了

## 修改配置文件

创建完成后，目录结构如下
.
├── _config.yml
├── package.json
├── scaffolds
├── source
|   ├── _drafts
|   └── _posts
└── themes

网站的配置文件是`_config.yml`，你可以在里面设置网站的大部分信息。
主要的参数：

|   参数   | 描述                                                  |
| :---------: | :------------------------------------------------------ |
|   title   | 网站标题                                              |
| subtitle | 网站副标题                                            |
|  author  | 网站作者                                              |
|    url    | 网址，必须已http/https开头                            |
| permalink | [具体参考这里](https://hexo.io/zh-cn/docs/permalinks) |

其他的参数也可以参考这里[点我](https://hexo.io/zh-cn/docs/configuration)

## 新建文章

使用`hexo new 'Hello world'`可以在*sources/_posts*生成一个Hello-world.md的文件，在这个文件里就能写文章了。
