### 命令工具
```shell
// init
npm install -g hexo-cli
hexo init hexo-blog
cd hexo-blog
npm install

// server
npm start

// deploy && git update hexo branch
npm run build
```

### 目录结构
```
- public // 打包后的文件存放地址
- scaffolds // 模板文件夹
- source // 主要资源文件夹
    - _post 文章资源
    - outlet 不被编译的静态资源地址，比如html文件
    - inject 会被编译的静态资源，内容会被inject到文章中
    - tags 标签文件夹
- theme // 主题配置

```