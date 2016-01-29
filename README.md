# yeoman-web

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.15.1.

## Build & development

环境准备：

* node > 0.10.20
* bower > 1.3.8
* npm > 2.8
* grunt >= 0.1.13


类似

```
root@mini ~$ node -v && bower -v && npm -v && grunt --version
v0.10.28
1.4.1
2.9.1
grunt-cli v0.1.13
```

* node安装：百度上有很多（安装完成后npm也被集成进去了）
* bower安装：```npm install -g bower```
* grunt安装： ```cd <your dir> && npm install -g grunt && npm install -g grunt-cli ``` 

```bower install && npm install```


> 开发环境：运行 `grunt serve` 即可运行并预览工程, 默认 http://localhost:9100 并修改Gruntfile.js为localhost 修改 script/tool/const.js 为 127.0.0.1
>
> 生产环境: 运行 ```grunt build ``` 后会生成 一个 dist 目录，然后 ``` nohup grunt serve:dist >> jannaRun.log 2>&1 & ```
>
> 检查进程  ``` ps -ef | grep grunt ```


---

## IDEA 导入工程

File -> Open -> Choose Dir

安装 angularJs 插件
Preference -> Plugins -> Browse repository -> 选择 angularJs

---

## 说明

整个项目是利用 Yeoman 创建工程骨架，并利用 angularJs 作为MVC 框架，bower管理静态资源，npm 管理node.js包，
工程运行在node环境上


