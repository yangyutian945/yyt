# element-ui-admin

单页面后台管理


## 技术栈

* vue
* vue-resource
* vue-router
* element-ui
* 基于路由配置的导航菜单
* 基于路由配置的面包屑
* 按路由异步加载

## 使用方法
(https://github.com/appbone/webpack-driven-web#使用方法)

## 目录说明

```
element-ui-admin/
├── src/
|   |── home/  -- 首页
|   |── event/ -- 活动页
|   |── user/  -- 账户页
|   └── lib/
|       └── app/
|           |── navbar/            -- 顶部导航组件
|           |── router-nav/        -- 基于路由配置的导航菜单组件
|           |── main-content/      -- 主要内容组件
|           |── router-breadcrumb/ -- 基于路由配置的面包屑组件
|           |── notfound/          -- 未找到路由时显示的组件
|           |── app.vue            -- 页面布局组件
|           └── routes.js          -- 路由配置
├── dist/
├── config/
|── package.json
└── webpack.config.js
```

