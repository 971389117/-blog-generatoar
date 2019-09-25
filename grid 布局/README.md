# Grid 布局之道

参考的这篇文章:[CSS Grid 布局全攻略](https://juejin.im/post/5d2d7a67f265da1bb5652b91#heading-9)

父
 定框架:
  grid-template-rows
  grid-template-columns
 看间隔
 看对齐
  内 items
  外 content

## 隐式网格

当我们在网格定义的区域外放置子元素时，或因子元素数量过多而需要更多的网格线时，布局算法就会自动生成隐式网格。默认情况下这些隐式网格的大小也会随着内容尺寸不同而变化
