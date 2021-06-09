# d7c_nodejs_gulp

## 介绍

d7c_nodejs_gulp 是一个使用 npm 和 bower 进行包管理，gulp 进行自动化构建的快速 WEB 骨架项目。

## 软件架构

### 应用程序依赖包管理工具 npm

npm 官网地址：[https://www.npmjs.com](https://www.npmjs.com/)，npm 全称 Node Package Manager 是 node 应用程序依赖包的管理工具，包括安装、卸载、更新模块操作，使用 nodejs 开发时一般使用 npm 来管理 nodejs 中的包。

### WEB 应用程序依赖包工具 bower

bower 官网地址：[https://bower.io](https://bower.io/)，是一款用来管理 WEB 应用程序依赖包，包括安装、卸载、更新模块操作。

### 自动化构建工具 gulp

gulp 官网地址：[https://gulpjs.com](https://gulpjs.com/)，中文官网地址：[https://www.gulpjs.com.cn](https://www.gulpjs.com.cn/)，用来机械化的完成重复性工作，将重复性工作抽象成一个个小任务聚合起来自动执行。

## 安装教程（在项目根目录下操作）

### 1. 初始化（给项目添加依赖配置文件）

在项目根目录下打开命令行窗口，输入 npm init <--yes> 和 bower init

### 2. 新建 .bowerrc，指定 bower 管理的依赖包安装位置

### 3. 新建 .editorconfig，规范文本编码格式

### 4. 安装 bootstrap 相关模块（本例采用方式二）

#### 方式一
+ npm install bootstrap@3.4.1 --save
+ npm install jquery --save
+ npm install html5shiv --save
+ npm install respond.js --save

#### 方式二
+ bower install --save bootstrap#3.4.1
+ bower install --save html5shiv
+ bower install --save respondJS

### 5. 安装 gulp 开发依赖模块

npm install --save-dev gulp

### 6. 在项目根目录下创建 gulp 主文件 gulpfile.js

### 7. 安装开发依赖模块
+ less 编译：npm install --save-dev gulp-less
+ 文件合并：npm install --save-dev gulp-concat
+ 压缩 css：npm install --save-dev gulp-cssnano
+ 压缩 JS：npm install --save-dev gulp-uglify
+ ES2015 转码规则：npm install --save-dev babel-cli babel-runtime babel-core babel-preset-env babel-preset-es2015 gulp-babel@7
+ 压缩 HTML：npm install --save-dev gulp-htmlmin
+ 实时同步效果到客户端：npm install --save-dev browser-sync
+ 删除目录：npm install --save-dev del
+ css 清理：npm install --save-dev gulp-clean-css
+ 重命名：npm install --save-dev gulp-rename

### 8. 在 gulpfile.js 创建自动执行任务

### 9. 运行项目 gulp / gulp build

## 使用说明

1. 下载项目并在项目根目录下执行 npm install 和 bower install（或直接在项目根目录下执行 npm run start / npm start / npm run test / npm test 安装并运行项目）
2. 运行项目 gulp / gulp build

## 捐助

如果您觉得我们的开源软件对你有所帮助，请扫下方二维码打赏我们一杯咖啡。
![微信收款码](https://images.gitee.com/uploads/images/2021/0222/174352_b22739f5_1070311.jpeg "微信收款码.jpg")
![微信赞赏码](https://images.gitee.com/uploads/images/2021/0222/174521_67e18b39_1070311.jpeg "微信赞赏码.jpg")
![支付宝收款码](https://images.gitee.com/uploads/images/2021/0222/174540_94a9ac41_1070311.jpeg "支付宝收款码.jpg")

## 参与贡献

1. Fork 本仓库
2. 新建 d7c_nodejs_gulp_xxx 分支
3. 提交代码
4. 新建 Pull Request

## 码云特技

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3. 你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4. [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5. 码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6. 码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)

[//]: (下面这段用于在Markdown编辑器中显示段落缩进)
<!-- 下面这段用于在 Markdown 编辑器中显示段落缩进 -->

<style>p{text-indent:2em}</style>
