# vue-script-ast

---

<!-- 在工作项目中发现,新增一个页面需要新建的文件很多,而且每个都需要导入和导出,所以做了一个自动创建页面的小工具,具体工具代码在 'scripts' 文件夹中,使用之前可以先进行阅读,代码写的很简单,没有任何模式,新手也可以轻松阅读,也可以作为学习 ast 的基本使用; -->

使用方法: 1.git clone https://github.com/gmkgmk/vue-template.git

2.npm install

3.使用命令 node ./scripts/core.js 或者 npm run g

4.输入相应的文件模块,文件名 列(order,list)

5.自动生成文件和 model,router 信息,

6.通过路由访问http://localhost:8080/#/layout/order/list

效果图如下:

### 项目原有结构

![项目原有结构](https://github.com/gmkgmk/ast-build-template/blob/master/README-image/1.jpg)

### 输入信息并确认,自动生成页面

![输入信息并确认](https://github.com/gmkgmk/ast-build-template/blob/master/README-image/2.jpg)

### 修改后文件结构

![生成文件](https://github.com/gmkgmk/ast-build-template/blob/master/README-image/3.jpg)

### 连接 model,server,页面

![实现效果](https://github.com/gmkgmk/ast-build-template/blob/master/README-image/4.jpg)
