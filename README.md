# nodejs-npm

#### 介绍
	+ 使用 npm 来管理应用程序依赖包；
	npm 官网地址：[npmjs.com](https://www.npmjs.com/)；
    npm 全称 Node Package Manager 是 node 应用程序依赖包的管理工具，包括安装、卸载、更新模块操作；
    使用 nodejs 开发时一般使用 npm 来管理 nodejs 中的包。
    + 使用 bower 来管理 WEB 应用程序依赖包，包括安装、卸载、更新模块操作；
    bower 官网地址：[bower.io](https://bower.io/)。
    + gulp 用来机械化的完成重复性工作，将重复性工作抽象成一个个小任务聚合起来自动执行；
    gulp 官网地址：[gulpjs.com](https://gulpjs.com/)；
    中文官网地址：[gulpjs.com.cn](https://www.gulpjs.com.cn/)。


#### 软件架构
	使用 npm 来管理应用程序依赖包模板项目。


#### 安装教程（都在项目所在目录下操作）

1.  初始化（给项目添加依赖配置文件）
	+ 在项目根目录下打开命令行窗口，输入 npm init <--yes> 和 bower init
2.  新建 .bowerrc，指定 bower 管理的依赖包安装位置
3.  新建 .editorconfig，规范文本编码格式
4.  安装 bootstrap 相关模块
	##### 方式一
	+ npm install bootstrap@3.4.1 --save
	+ npm install jquery --save
	+ npm install html5shiv --save
	+ npm install respond.js --save
	##### 方式二
	+ bower install --save bootstrap#3.4.1
	+ bower install --save html5shiv
	+ bower install --save respondJS
    ##### 本例采用方式二
5.  安装 gulp 开发依赖模块
	+ npm install --save-dev gulp
6.  在项目根目录下创建 gulp 主文件 gulpfile.js
7.  安装开发依赖模块
	+ less 编译：npm install gulp-less --save-dev
	+ 文件合并：npm install --save-dev gulp-concat
	+ 压缩 css：npm install gulp-cssnano --save-dev
	+ 压缩 JS：npm install --save-dev gulp-uglify
	+ 压缩 HTML：npm install --save-dev gulp-htmlmin
	+ 实时同步效果到客户端：npm install --save-dev browser-sync
	+ 删除目录：npm install --save-dev del
	+ css 清理：npm install gulp-clean-css --save-dev
	+ 重命名：npm install gulp-rename --save-dev
8.  在 gulpfile.js 创建自动执行任务
9.  运行项目 gulp / gulp build


#### 使用说明

1.  下载项目并在项目根目录下执行 npm install 和 bower install（或直接在项目根目录下执行 npm run start / npm start / npm run test / npm test 安装并运行项目）
2.  运行项目 gulp / gulp build


#### 参与贡献

1.  创建本仓库
2.  初始化项目


#### 码云特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5.  码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
