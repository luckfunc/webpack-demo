## webpack使用观察者模式
- 优点：当输入`npm run watch`webpack使用观察者模式，当文件发生变化时，webpack会自动重新编译。 
- 缺点：需要手动刷新浏览器。

## 使用webpack-dev-server
`webpack-dev-server` 提供了一个能够实时重新加载的基本的 web server。安装依赖如下：
```bash
npm install --save-dev webpack-dev-server
```
package.json中添加如下配置：
`"start": "webpack serve --open"`
