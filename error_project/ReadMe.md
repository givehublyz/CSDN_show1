1.先运行命令：npm install，把express的相关的包下载下来。
2.运行命令:node ./app.js命令运行项目，就可以了

生成这个项目的一些步骤：
前言：这个项目是react+webpack+express的一个项目。tips:如果你不知道怎么构建react多入口html项目，可以参考:https://juejin.im/post/5bc41ae0f265da0af161674e。
1.react的项目在根目录运行:npm run build打包后生成index.html,login.html,index.bundle.js,login.bundle.js和一些字体、图片资源文件（为了演示方便，我把字体、图片等删除了，因而你可以会在控制台看到找不到字体、图片的报错）
2.新建文件夹show,把index.html,login.html,index.bundle.js,login.bundle.js这四个文件放到文件夹show中，把app.js文件复制过来(你可以直接复制我的app.js)并且针对本项目做一些修改。
3.show目录下运行命令:npm init，生成package.json文件
4.安装一些express中要使用的包:show目录下运行
npm install express --save
npm install body-parser --save
npm install express-session --save
npm install ejs --save

5.现在项目已经完成了，直接再show目录下运行命令:node ./app.js就可以运行了。
