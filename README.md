```
  _                  ___ _             _   __   __            ___ _           
 | |   ___ __ _ _ _ / __| |___ _  _ __| |__\ \ / /  _ ___ ___| _ ) |___  __ _ 
 | |__/ -_) _` | ' \ (__| / _ \ || / _` |___\ V / || / -_)___| _ \ / _ \/ _` |
 |____\___\__,_|_||_\___|_\___/\_,_\__,_|    \_/ \_,_\___|   |___/_\___/\__, |
                                                                        |___/                         
```


# LeanCloud-Vue-Blog

[![License MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](myGithub)&nbsp;
[![platform](https://img.shields.io/badge/platform-LeanCloud-lightgray.svg?style=flat)][myGithub]&nbsp;
[![platform](https://img.shields.io/badge/build-passing-green.svg?style=flat)][myGithub]&nbsp;


## Introduction


一个前后端完全分离的单页应用  [线上地址点此查看](http://royalmjz.leanapp.cn)

采用了"将就"写的 vue.js+LeanCloud（node.js） 的开发样板 [github地址点此查看](https://github.com/jiangjiu/vue-leancloud-boilerplate)


## Usage

### 开发

```bash
git clone git@github.com/RoyalMjz/LeanCloud-Vue-Blog.git
$ cd LeanCloud-Vue-Blog
$ npm install

// 启动服务器端, 默认地址 http://localhost:3000
$ lean up

// 另开一个 terminal
$ cd FE
$ npm install
// 启动前端项目，默认地址 http://localhost:8080
$ npm run dev
```

### 构建部署

```bash
// 在FE目录下  构建前端文件至 /public 文件夹
$ npm run build

// 根目录下 leancloud命令行部署 / 通过 github 部署
$ lean deploy / lean deploy -g

```

具体部署可参考[LeanCloud云引擎 Node.js 部署](https://leancloud.cn/docs/leanengine_webhosting_guide-node.html#部署)


## 技术栈
### 前端
- [Vue.js](https://github.com/vuejs/vue)
- [vuex 状态管理](https://github.com/vuejs/vuex)
- [vue-router 路由](https://github.com/vuejs/vue-router)
- [vue-resource xhr请求](https://github.com/vuejs/vue-resource)
- [marked 语法解析](https://github.com/chjj/marked)
- [prismjs 代码高亮](http://prismjs.com/)
- [fastclick 解决移动端延迟问题](https://github.com/ftlabs/fastclick)


### 后端
- [node.js 服务端](https://github.com/nodejs/node)
- [express 框架](https://github.com/expressjs/express)
- [LeanCloud 数据存储](https://leancloud.cn/)


## LICENSE

LeanCloud-Vue-Blog is licensed under the MIT Open Source license. For more information, please see the [LICENSE](https://raw.githubusercontent.com/RoyalMjz/LeanCloud-Vue-Blog/master/LICENSE) file in this repository.



[myGithub]: https://github.com/RoyalMjz/LeanCloud-Vue-Blog
