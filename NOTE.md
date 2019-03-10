### package.json 依赖
- babel-runtime 对 ES6 语法转义
- faskclick 解决移动端点击 300ms 延迟问题
- babel-polyfill 补丁，对 ES6 API 转义

### jsonp 原理
- 发送的不是 ajax 请求，而是动态创建 script 标签，因为 script 标签是没有同源策略限制，是可以跨域的
- 创建的 script 标签的 src 指向请求的真实服务端地址，地址后面带有 callback

### vue 知识点
- keep-alive 主要用于保留组件状态或避免重新渲染

### request header
- Host
- Referer 请求来源