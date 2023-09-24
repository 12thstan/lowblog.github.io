# Lowblog源码

## **基于 框架 [Hexo](https://hexo.io/zh-cn/) | 主题 [Butterfly](https://github.com/jerryc127/hexo-theme-butterfly)**

### **本地启动：**
```
hexo clean && hexo g && gulp && hexo s
```

### **远程部署：**
```
hexo clean && hexo g && gulp && hexo d
```

---

### **需知：**
**解压后必需在博客目录下安装以下内容：**
```
npm install
```
---

如果在本地启动报错，需要安装以下内容：
```
npm install --global gulp-cli
npm install gulp --save
npm install gulp-htmlclean --save-dev
npm install gulp-html-minifier-terser --save-dev
npm install gulp-clean-css --save-dev
npm install gulp-terser --save-dev

npm install hexo-tag-aplayer --save

npm install hexo-butterfly-clock --save

npm install hexo-butterfly-footer-beautify --save

npm install hexo-generator-search --save

npm install hexo-butterfly-wowjs --save

```

安装后出现如果出现以下内容，

> *" run `npm audit fix` to fix them, or `npm audit` for details "*

需要安装：
```
npm audit fix
npm audit fix --force
npm audit
```

---

### 补充：
### **主题版本为 [3.0.1](https://codeload.github.com/jerryc127/hexo-theme-butterfly/zip/refs/tags/3.0.1) | Node.js为 [12.12.0](https://nodejs.org/download/release/v12.12.0/)** 

---
