### 1.开发步骤
	安装vue脚手架：
		推荐 3.0版本: npm install -g @vue/cli
		不推荐2.0版本: npm install -g vue-cli
		————注意：全局安装脚手架，只安装一次即可，后面的项目就不用安装了，直接执行第2步
	构建项目
		vue init webpack 项目名
	进入项目文件
		cd 文件名
	启动项目
		npm run dev		
		访问：http://localhost:8081
		修改config->index.js下的autoOpenBrowser: true,自动在浏览器中打开
	打包项目
		开发环境打包:
			npm run build
			访问：http://localhost:8081
		生产环境打包:
			npm install -g serve;	
			serve dist;
			访问：http://localhost:5000
### 2.开发准备
	图片Base64:将图片转为字符串，减少请求次数(webpack会自动转换)
	iconfont字体图标：通过link在index.html页面中引用，需要先把图标加入购物车，添加至我的项目
	
	安装stylus插件:	npm install stylus stylus-loader -S
	配置组件模板：新建vue文件，右上角自定义模板，将写好的模板文件放在此目录，再新建时就有此选项了
	
	引入解决点击0.3s延迟的js文件以及配置 ———— js配置
	引入移动端浏览器样式重置文件 ———— css配置
	引入移动端视口设置 ———— viewport配置
	
### 3.
	拆分页面，分为路由组件和非路由组件
	
	
	
	
	