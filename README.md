# hexang-landingpage 息壤平台落地页（首页）

## 使用方法

直接将根目录下的网页前端相关文件和`/css`、`/js`、`/images`几个文件夹部署即可。

## 开发指南

### 目录结构

        ├── README.md
        ├── bootstrap
        │   └── scss
        │       ├── mixins
        │       └── utilities
        ├── css
        ├── images
        ├── js
        │   ├── bootstrap.min.js
        │   ├── jquery-3.3.1.min.js
        │   ├── main.js
        │   └── popper.min.js
        ├── scss
        │   └── hexang.scss
        ├── webfonts
        ├── favicon.ico
        └── index.html

### 使用 SCSS 拓展 Bootstrap 的样式

1. 编译方法：根目录下运行

        sass --watch scss:css

2. 样式书写：在 `./scss/` 目录下的 `hexang.scss` 中覆盖 Bootstrap 中相关类的样式，直接在顶部 `import` 所需要的 Bootstrap 样式文件

## License

This project is licensed under the MIT License.