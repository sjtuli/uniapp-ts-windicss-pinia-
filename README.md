# uniapp(Vue3)-ts-vite-windicss 快速开发模板
利用`uniapp` + `windicss` + `ts` + `vite` 搭建的一套基础模板

1. windicss以及flex布局的css工具拓展
2. miniprogram-ci集成，实现通过GitHub Actions自动执行脚本构建打包上传
3. 基本的列表和表单demo
4. 统一的request api请求处理，枚举与正则校验


>背景：windicss真的爽，不接受反驳

### 安装：
命令行执行` yarn `或者`npm i`，安装所需依赖


### 启动

#### h5
```bash
yarn dev:h5
```
#### 小程序
```bash
yarn dev:mp-weixin
```
然后打开微信开发者工具选择`/dist/dev/mp-weixin`文件夹

### Build
```bash
yarn build:mp-weixin
```
然后打开微信开发者工具选择`/dist/build/mp-weixin`文件夹

### 预览（h5 build 的时候，会出现样式丢失问题，因而与图片不符）
[live demo](http://uniapp-template.demo.qqoc.co/#/)

### 项目地址
[github](https://github.com/sjtuli/uniapp-ts-windicss-pinia)

### 已知问题
h5 build 的时候，会出现样式丢失问题（不会吧，真的有人用uniapp开发h5）。
如下
[live demo](http://uniapp-template.demo.qqoc.co/#/)

### 感谢
dcasia/mini-program-tailwind 超好用的windicss转译插件
🔗 链接：[github](https://github.com/dcasia/mini-program-tailwind)
tobe-fe-dalao/fast-vue3  本项目大量借鉴了该项目
🔗 链接：[github](https://github.com/tobe-fe-dalao/fast-vue3)