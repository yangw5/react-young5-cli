# 自定义脚手架：react-youngw-cli

作者：young5

邮箱：yangw5@163.com

## react-youngw-cli 的安装使用

- npm 全局安装 react-youngw-cli

        npm i react-young-cli -g

- 创建项目

        react-young5-cli i

- 初始化并运行项目

        yarn

        yarn start

## 下载克隆项目

    git clone

## 项目依赖

- "chalk"：提供命令颜色控制
- "commander"：提供了用户命令行输入和参数解析
- "download-git-repo"：下载并提取 git 仓库，用于下载项目模板
- "inquirer"：通用的命令行用户界面集合，用于和用户进行交互
- "ora"：微调节器：图标等的自定义

## 代码目录

        + --bin/                     --命令提示配置文件
        |    --- react-cli.js
        + --commands/                -- 命令定义文件
        |   --- init.js
        + .gitignore                 ---git提交忽略文件
        + .npmignore                 ---npm提交忽略文件
        + .package.json              ---项目 j 依赖
        + .templates.json            ---git 模板配置
        + .README.md                 ---项目说明文件
