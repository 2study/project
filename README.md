# 127.0.0.1
## 简介
## 目录介绍
.
├── build                     							# 命令运行后存放的文件目录
│   ├── comm/           	  							# 共用的html文件
│   ├── layout/           	  							# 共用的页头页脚
├── dist                      							# 任务实时刷新
├── mock                  	  							# 假数据文件
├── README.md                 							# 项目说明
├── pages/            		  							# 各种html
│   ├── index.html            							# 首页
│   ├── comm/           	  							# 共用的html文件
│   	├── header.html           	  					# 页头
│   	├── footer.html           	  					# 页脚
│   	├── main.html           	  					# 内容
│   	├── nav.html           	      					# 导航
│   	├── sidebar.html           	  					# 侧边栏
│   ├── ...            		  							# 各种模块的html文件
├── web                       							# 本地静态资源
│   ├── src                   							# 源码目录
│   │   ├── css/              							# css资源
│   │   	 ├── sass/        							# 存放sass文件
│   │   	 	  ├── _index.scss       				# 首页
│   │   	 	  ├── _reset.scss       				# 重置
│   │   	 	  ├── _global.scss      				# 全局
│   │   	 	  ├── _base.scss       				    # 通用性文件
│   │   	 	  ├── _mixin.scss       				# sass封装的函数方法
│   │   	 	  ├── _header.scss      				# 页头
│   │   	 	  ├── _footer.scss      				# 页脚
│   │   	 ...        	  							# 编译后的css文件与sass文件夹同级
│   │   ├── images/           							# 图片资源
│   │   ├── js                							# js
│   │   	 ├── tool/  	  							# 封装的一些组件和插件
│   │   ├── font/             							# 字体库
│   │   ├── svg/              							# svg
│   │   ├── lib/              							# 第三方库
├── task                      							# 任务目录
│   ├── javascript.js         							# javascript压缩 
│   ├── css.js            	  							# css编译压缩 
│   ├── html.js            	  							# html编译 
│   ├── images.js             							# 图片压缩 
│   ├── clean.js              							# 清除dist文件里面的文件
│   ├── sprites.js            							# 雪碧图合并
│   ├── render.js             							# 页面渲染 
│   ├── git.js                							# git自动提交 
│   ├── combo.js              							# 合并请求 
├── index.js            	  							# 执行express 
├── config.json            	  							# 配置各种环境
├── package.json              							# 文件    
└── gulpfile.js      		  							# gulp任务