# build
这样修改的原因
1. 希望实现封装命令的效果,
npm run build 是一个通用的命令
不管此项目用的是什么打包工作，如何编译，用户不需要关心，
只需要执行npm run build就可以了

2. 不同的项目使用不同的webpack版本
不同的项目不互相冲突

