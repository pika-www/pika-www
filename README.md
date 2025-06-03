项目技术栈
vue3 + vue-router4 + pinia + typescript + ant-design-vue + axios

开发环境
本地确保安装 yarn
npm install yarn -g

安装依赖
yarn

启动
yarn start

构建
yarn build:master

项目结构

├── src
│   ├── api --- 放置请求函数
│   ├── assets --- 放置一些图片、样式等静态文件
│   ├── components --- 全局通用组件编写
│   ├── interface --- 接口定义
│   ├── json  --- 静态数据
│   ├── router --- 路由文件
│   ├── stores --- 状态管理文件
│   ├── utils --- 放置工具方法
│   ├── views --- 页面组件编写
└── index.html --- vite 打包入口文件
