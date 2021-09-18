# webstack-assets

[webstack](https://github.com/WebStackPage/WebStackPage.github.io) CSS, JS 文件的 **CDN 解决方案**。

这个 repo 里的 CSS, JS 文件是从 https://github.com/WebStackPage/WebStackPage.github.io 复制而来。

### 如何使用

替换 HTML 文件里的 CSS 路径和 JS 路径。注意，logo 和其他图片的路径不要修改。

```
../assets/
=>
https://cdn.jsdelivr.net/gh/pzwd-net/webstack-assets@main/
```

### 为什么要这么做？

- 通过 CDN 可以使 CSS, JS 加载的更快，而且可以减少服务器的网络开销。
- 集中管理 CSS，JS 文件，可以更容易的让其他开发者参与贡献代码，并且可以减少合并代码的麻烦
- 通过前端构建工具，优化代码（TODO）

### 如何参与贡献？

和其他开源项目一样，fork repository, 修改代码，测试，提交 PR。

开发时，把 repository clone 到你的 webstack 目录内，把 assets 路径替换成

```
https://cdn.jsdelivr.net/gh/pzwd-net/webstack-assets@main/
=>
../webstack-assets/
```

或者

```
../assets/
=>
../webstack-assets/
```

### 如何定制化样式和功能？

- fork repository
- 定制化
- 修改 `cdn.jsdelivr.net` 的路径为你的用户名

```
https://cdn.jsdelivr.net/gh/你的用户名/webstack-assets@main/
```

### 如何提出问题和建议？

https://github.com/pzwd-net/webstack-assets/issues
