# script标签

为什么将 script 标签放在底部而不是头部?

src和href区别章节。 放在顶部就会阻塞文档的渲染，阻塞页面的解析。

主要是怕 js 白做。 按照 css 的层叠性。 最终作用的样式好了之后，再去做相应的操作。