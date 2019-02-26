原规范：http://one-design.baidu-int.com/design/basic/navigation

# 原则（新增）

在广义上，任何告知用户他在哪里，他能去什么地方以及如何到达那里的方式，都可以称之为导航。当设计者使用导航或者自定义一些导航结构时，请注意：

 - 尽可能提供标识、上下文线索，避免用户迷路；

- 保持导航样式和行为一致或者减少导航数量，降低用户学习成本；

- 尽可能减少页面间的跳转（例如：一个常见任务需要多个页面跳转时，请减少至一到两次），让用户移动距离保持简短。

> 参考 [Ant Design - 导航](https://ant.design/docs/spec/navigation-cn)

# 分类（优化）

## 按导航方向

### 横向/竖向导航

- 横向导航把超链接连成一行，信息内容层级比较简单明了，适用在浏览性强的门户性质以及比较前台化的应用

- 竖向导航较横向的导航更灵活，易于向下扩展， 且允许的标签长度较长。类目数量不限，可配合滚动条使用，适合信息层级多、操作切换频率高的管理性质的应用

- 横向/竖向导航都在相同层次结构的页面之间导航

> 参考 [Material Design - lateral navigation](https://material.io/design/navigation/understanding-navigation.html#lateral-navigation)

> 参考 [Ant Design - 顶部导航菜单](https://ant.design/docs/spec/navigation-cn#%E9%A1%B6%E9%83%A8%E5%AF%BC%E8%88%AA%E8%8F%9C%E5%8D%95)

> 参考 [Ant Design - 侧边导航菜单](https://ant.design/docs/spec/navigation-cn#%E4%BE%A7%E8%BE%B9%E5%AF%BC%E8%88%AA%E8%8F%9C%E5%8D%95)

### 前进导航

- 在应用程序的层次结构中向下以访问更深层次的内容，从父页面（更高级别的层次结构）到子页面（更低级别）

- 根据引导有顺序地完成一系列操作，例如结账过程

- 直接从应用程序中的一个页面到任何其他页面，例如从主页面到应用程序层次结构深处的页面

> 参考 [Material Design - forward navigation](https://material.io/design/navigation/understanding-navigation.html#forward-navigation)

### 后退导航

- 查看浏览历史记录，如Web浏览器上的“后退”按钮

- 返回上一个页面直到到达主页面，如APP中“返回”操作

> 参考 [Material Design - reverse navigation](https://material.io/design/navigation/understanding-navigation.html#reverse-navigation)

# 导航组件（新增）

- 面包屑（Breadcrumb）

- 标签页（Tabs）

- 步骤条（Steps）

- 分页器（Pagination）

> 参考 [Ant Design - 导航](https://ant.design/docs/spec/navigation-cn)

# 导航过渡

通过在导航中加入一些过渡工作来引号用户，帮助用户定位自己，了解不同页面之间的关联

- 父子页面过渡

- 兄弟页面过渡

> 参考 [Material Design - navigation transitions](https://material.io/design/navigation/navigation-transitions.html#)