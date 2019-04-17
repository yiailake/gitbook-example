# gitbook-example

## gitbook安装

先安装nodejs，然后使用npm命令安装gitbook
```
npm install gitbook-cli -g
```

## 书籍目录结构
新建书籍， 其目录结构如下：
```
$ tree book/
book/
├── README.md
└── SUMMARY.md

0 directories, 2 files
```
`README.md`和`SUMMARY.md`是两个必须文件，`README.md`是对书籍的简单介绍，
`SUMMARY.md`是书籍的目录结构

## 基本使用
1.使用`gitbook init`初始化书籍目录  
2.使用`gitbook serve`编译并在浏览器里预览书籍  

## 高级使用
在书籍顶层目录中添加`book.json`启用个性化配置，如添加主题插件：
```
{
    "plugins": ["theme-comscore"]
}
```

This is a book powered by [gitbook](https://github.com/GitbookIO/gitbook).