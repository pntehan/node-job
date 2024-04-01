# job-node

一个用`Vue`全家桶技术栈开发的求职招聘网站

，封装逻辑的能力也是有了很大的提高，不仅如此，对于使用一些优秀的类库也是有了进一步的理解和使用。总之开发此项目收货满满。此外还有一些项目升级的需求和优化我也会持续更新，会持续的维护此项目。欢迎收藏和关注，谢谢！

## Clone project

```bash
git clone git@github.com:pntehan/node-job.git
```

## Project setup

```bash
npm install
```

### Compiles and hot-reloads for development

```bash
npm run dev
```

默认启动 <http://localhost:8080>

### Start server API

```bash
npm  run server      默认监听`http://localhost:3000`
```

> 默认不需要启动，如果需要调试服务器端代码，请配置根目录下的`vue.config.js`文件，修改代理地址如下

```js
module.exports = {
  devServer: {
    proxy: "http://localhost:3000",
  },
};
```

### Compiles and minifies for production

```bash
npm run build
```

## 主要功能

- [x] 首页
- [x] 职位关键字搜索
- [x] 城市职位列表
- [x] 职位分类列表
- [x] 职位详情

- [x] 注册
- [x] 登录
- [x] 退出
- [x] 简历
  - [x] 我的简历
  - [x] 简历上传
  - [x] 简历查看
- [x] 公告信息

- [x] 管理员首页
- [x] 管理员管理求职信息
- [x] 管理员管理岗位信息
- [x] 管理员管理用户信息

## 技术栈

`vue` `vue-router`

`vue-cli` `less`

`axios` `lodash` `es6~7`

`express` `node-fetch` `http-proxy-middleware`
