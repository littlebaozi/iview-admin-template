<p align="center">
    <a href="https://www.iviewui.com">
        <img width="200" src="https://file.iviewui.com/logo-new.svg">
    </a>
</p>

[![](https://img.shields.io/github/release/iview/iview-admin.svg)](https://github.com/iview/iview-admin/releases)
[![](https://img.shields.io/travis/iview/iview-admin.svg?style=flat-square)](https://travis-ci.org/iview/iview-admin)
[![vue](https://img.shields.io/badge/vue-2.5.17-brightgreen.svg?style=flat-square)](https://github.com/vuejs/vue)
[![iview ui](https://img.shields.io/badge/iview-3.2.2-brightgreen.svg?style=flat-square)](https://github.com/iview/iview)
[![npm](https://img.shields.io/npm/l/express.svg)]()

## Introduction

iView Admin is a front-end management background integration solution. It based on [Vue.js](https://github.com/vuejs/vue) and use the UI Toolkit [iView](https://github.com/iview/iview).

- [Document](https://lison16.github.io/iview-admin-doc/)
- [Preview](https://admin.iviewui.com/)
- [Base template recommends using](https://github.com/iview/iview-admin/tree/template)

![image](https://file.iviewui.com/admin-dist/admin-preview.png)



## Getting started
```bush
// 安装依赖
npm install
// or
yarn

// 开发版本
npm run dev
```

* mock开发
```bush
npm run mock
```

* 预发布 测试用
```bush
npm run stage
```

* 发布版本
```bush
npm run build
```

## 开发环境配置 
* 修改API地址
修改各个`.env`文件中的`VUE_APP_API`

* 修改标题后缀
修改各个`.env`文件中的`VUE_APP_MODE`


## License
[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2016-present, TalkingData
