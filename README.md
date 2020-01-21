# 自定义脚手架：react-young5-cli

作者：young5 :baby:

邮箱：yangw5@163.com

react-young5-cli 是一个创建后台管理系统的 react 脚手架工具。

[github 完整源码地址](https://github.com/yangw5/react-young5-cli)：https://github.com/yangw5/react-young5-cli 🔥🔥🔥

## react-youngw-cli 的安装使用

- npm 全局安装 react-youngw-cli

        npm i react-young-cli -g

- 创建项目

        react-young5-cli i

- 初始化并运行项目

        yarn

        yarn start

## 下载克隆项目

    git clone https://github.com/yangw5/react-young5-cli.git

## 项目依赖

- [chalk]()：提供命令颜色控制 👍
- [commander](https://github.com/tj/commander.js/blob/master/Readme_zh-CN.md#commanderjs)：提供了用户命令行输入和参数解析 👍
- [download-git-repo]()：下载并提取 git 仓库，用于下载项目模板 👍
- [inquirer]()：通用的命令行用户界面集合，用于和用户进行交互 👍
- [ora]()：微调节器：图标等的自定义 👍

[相关依赖用法](https://github.com/yangw5/docusaurus/blob/master/docs/react-cli.md)：https://github.com/yangw5/docusaurus/blob/master/docs/react-cli.md

## 代码目录

        + --bin/                            ---命令提示配置文件
        |    --- react-cli.js
        + --commands/                       --- 命令定义文件
        |    --- init.js
        + .gitignore                        ---git提交忽略文件
        + .npmignore                        ---npm提交忽略文件
        + .package.json                     ---项目信息及相关依赖文件
        + .templates.json                   ---git 模板配置
        + .README.md                        ---项目说明文件

## 坑点

1. 需要 npm 账号，推荐去官网进行注册
2. npm 名要唯一

## 结尾

项目中存在的问题和有优化的地方，希望大家多多的指出。
如果有相关的疑惑，可以加入 QQ 群与我联系：

- 254486893

赠人玫瑰，手有余香，希望对大家有所帮助，同时你觉得有所获得的话，那就戳一个 star 吧~~❤️❤️❤️❤️❤️，感谢! :pray: :pray: :pray:
