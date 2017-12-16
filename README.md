## 常用命令
- 新建项目：vue init webpack my-project
- 
- http://localhost:8080/#/
## vue-cli中配置sass
1. 安装对应依赖node模块：

    npm install node-sass --save-dev

    npm install sass-loader --save-dev
2. 打开webpack.base.config.js在loaders里面加上
```
{
    test: /\.scss$/,
    loaders: ["style", "css", "sass"]
}
```
3. 在用scss的地方写上

    <style lang="scss" scoped="" type="text/css"></style>
    
    
## 开发项目流程

```
graph LR
A-->B
B-->C
```


    
