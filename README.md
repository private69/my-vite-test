# my-vite-test
> 什么是vite？Vite，一个基于浏览器原生 ES imports 的开发服务器。利用浏览器去解析 imports，在服务器端按需编译返回，完全跳过了打包这个概念，服务器随起随用。同时不仅有 Vue 文件支持，还搞定了热更新，而且热更新的速度不会随着模块增多而变慢。针对生产环境则可以把同一份代码用 rollup 打。虽然现在还比较粗糙，但这个方向我觉得是有潜力的，做得好可以彻底解决改一行代码等半天热更新的问题。

### 1、基本使用

- 安装

  > npm	i	create-vite-app	-g
  >
  > yarn	add	create-vite-app	-g

- 创建项目

  > create-vite-app	"项目名称"

- 运行项目

  > npm	run	dev
  >
  > npm	run	build

### 2、