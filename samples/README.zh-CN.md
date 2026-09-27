# Eclipse Collections 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) 过滤 `FastList`，并汇总原始整数集合 `IntArrayList`。示例通过自己的 `Module module()` 声明依赖，是独立的模块消费者。

在仓库根目录运行：

```sh
norm run samples/hello.norm
```

预期输出：筛选后的标签数量 `2`，接着是奇数之和 `8`。[module.norm](../eclipse/collections/module.norm) 是软件包的构建来源，指定 Eclipse Collections 13.0.0 并定义公开 API。
