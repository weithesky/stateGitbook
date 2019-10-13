### vuepress

[官网](https://www.vuepress.cn/)



### 常用目录结构

```shell
.
├─ docs
│  ├─ README.md
│  └─ .vuepress
|	  └─ components
|	  	└─ 组件vue文件
|	  └─ theme
|	  	└─ 主题vue文件
|	  └─ styles
|	  	└─ 样式文件
|	  └─ public
|	  	└─ 静态资源
│     └─ config.js
└─ package.json
```

> - `docs/.vuepress`: 用于存放全局的配置、组件、静态资源等。
> - `docs/.vuepress/components`: 该目录中的 Vue 组件将会被自动注册为全局组件。
> - `docs/.vuepress/theme`: 用于存放本地主题。
> - `docs/.vuepress/styles`: 用于存放样式相关的文件。
> - `docs/.vuepress/styles/index.styl`: 将会被自动应用的全局样式文件，会生成在最终的 CSS 文件结尾，具有比默认样式更高的优先级。
> - `docs/.vuepress/styles/palette.styl`: 用于重写默认颜色常量，或者设置新的 stylus 颜色常量。
> - `docs/.vuepress/public`: 静态资源目录。
> - `docs/.vuepress/templates`: 存储 HTML 模板文件。
> - `docs/.vuepress/templates/dev.html`: 用于开发环境的 HTML 模板文件。
> - `docs/.vuepress/templates/ssr.html`: 构建时基于 Vue SSR 的 HTML 模板文件。
> - `docs/.vuepress/config.js`: 配置文件的入口文件，也可以是 `YML` 或 `toml`。
> - `docs/.vuepress/enhanceApp.js`: 客户端应用的增强。

### 特点

- 扩展性强，可以使用.vue组件
- 中文社区，支持性强
- 相比**gitbook**更轻巧和自定义化