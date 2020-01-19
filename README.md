# SimpleWebpackHTMLEntrypoint
一个 webpack 插件，为多入口应用定制

发布在 npm 官方平台：

https://www.npmjs.com/package/simple-webpack-html-entrypoint

```js
module.exports = {
    entry: {
        index: './src/example/index.ts',
        page2: './src/example/page2.ts',
        page3: './src/example/page3.ts'
    },
    plugins: [
      new SimpleWebpackHTMLEntrypoint()
    ]
}
```

=> 

 + index.html
 + page2.html
 + page3.html
