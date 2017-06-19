# BigPipe
## 链接地址
http://fex.baidu.com/yog2/docs/advance/pagelet.html#BigPipe

### BigPipe前端性能优化
```
Facebook 的 BigPipe 技术，是通过将站点分解为多个 pagelet 小块，每个pagelet 获取数据与渲染均是独立的，
当传统的后端模板渲染模式受限于后端响应速度最慢的接口时，BigPipe 模式可以实现 pagelet 的数据一旦返回，
就可以无阻塞的在浏览器端进行渲染，以此来实现大型复杂页面的性能加速。
```

### Quickling 实现局部刷新
```
除了 BigPipe 模式外，我们还可以将 pagelet 用于 Quickling 模式。所谓 Quickling 模式是将 widget 整体通过 Ajax 请求返回。
也就是将传统的 Ajax 请求数据，前端模板渲染数据的模式变化为 Ajax 请求渲染好的页面以及 widget 执行的必要代码和样式。
这两种方式并非互相取代的关系，而是应该根据使用场景灵活判断。
```
