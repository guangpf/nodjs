#nodejs 安装
##下载进行安装 官方网站 <a href="https://nodejs.org/en/">node官网</a>
##在相应的平台下，下载相应的版本,一个是长期维护版本，一个是下载最新版本
      **学习或实验可以用当前的版本，如果上线项目可以使用长期维护版本。尾数为偶数的版本为长期稳定版本，尾数为奇数的为当前最新版本（实验版本）**
##安装
###windows 系统下的安装  
  - 下载相应的安装包，有两种安装包，一个是node.msi,一个是node.exe ,exe就是一个二进制执行文件，只是用来解析node.js教程想要运行的node命令,必须手动的放到全局环境下，node.msi包含了node.exe，npm 要在命令行选择 add to Path ，将nodejs添加到全局环境下，安装成功后，可以执行 node -v 检测安装的版本，以及是否安装成功
###mac 安装
###linux 安装
### npm 安装
  - npm 包管理工具 node package manage ，<a href="https://www.npmjs.com/">npm官网</a> ,安装成功后 npm -v 可以检测到版本号  和是否安装成功
  - 为了nodejs开发人员的方便,npm给我们提供了一个包管理工具,npm官网  这样方便nodejs开发人员进行模块化的开发,不用担心你自己编写的模块或者别人编写的模块放到什么地方,他们依赖关系等等，我们只需要通过npm就可以对他进行维护
  
# 执行的第一个程序 
## 交互的方式运行nodejs
 1. node 回车 进入到nodejs的编译环境
 2. 在这个环境下，只要你输入符合nodejs语法规范的代码，回车后就会立即得到响应的结果，会对你输入的代码进行回应
## 编译运行nodejs
 1. 创建一个js文件
 2. 在命令行进入js文件所在的目录 通过node node.js 来对js文件进行解析和执行，如果说想在命令行看到输出结果,必须手动进行输出  在 node.js  中 console.log（）输出；


#nodejs  运行环境的配置

## phpstorm编译器  来配置nodejs运行的环境  
     **webstorm编译器  不用进行配置 ，已经把相应的环境配置好了**
  - 打开phpstorm配置项（settings）
  - 打开 plugin 进行cnodejs搜索，搜索成功后，点击install 进行安装,安装成功后,提醒你重启编译器
  - 打开配置项，在framswork下能找到nodejs and npm ，插件已经安装成功
  - 首先 然他们可用,设置作用区间，以及可以提示的语言
   
 
