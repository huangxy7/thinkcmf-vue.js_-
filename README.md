＃简介
项目基于thinkcmf作为后端，vue.js作为前段的文件管理系统。可上传文件下载文件分公共文件与私有文件，在线预览文件，文件管理等

vue/ 文件夹是vue开发网站的源码，vue/build文件夹下是配置域名跨域问题等配置文件，vue/src主要开发文件，vue/src/components/下是开发的组件

main.js => 项目入口文件

App.vue => 项目最原始的根组件

router => 项目所有路由存放处

components => 项目用到的组件

assets => 项目用到的图片类的资源

运行方法：
开发
下载文件夹 cd vue 
npm install 
npm run dev

前端部署
npm run build

生成 dist文件夹 把里面的东西放在服务器上即可



php/属于后台开发源码，由thimkcmf进行二次开发

后端部署：
下载代码把服务器浏览器打开php/public/index.php 安装 完成即可
