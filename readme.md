### gulp html自动打包配置
#### 使用方法
1.安装npm，执行 ``` npm install ```

2.打开gulpfile.js根据注释信息修改

3. 在原始html内将需要压缩合并的 css引用 的首行和末行分别加入
```html
<!-- build:css styles/main.css --> 
<!-- endbuild -->
```

4.在原始html内将需要压缩合并的 js引用 的首行和末行分别加入
```html
<!-- build:js js/main.min.js -->
<!-- endbuild -->
``` 

5. 执行 ``` gulp ``` 命令打包