# Eclipse Collections

[English](README.md) | [简体中文](README.zh-CN.md)

适配声明与可运行示例位于 `eclipse/collections`，固定 Eclipse Collections 13.0.0 与对应 API artifact，发布坐标见 [module.norm](eclipse/collections/module.norm)。公开面覆盖 `FastList`、`UnifiedSet`、`UnifiedMap`、`FastListMultimap`、`IntArrayList` 及常用筛选、变换、分组和原生整数集合操作。

独立 NAR 消费、传递 API 依赖、继承公开方法、对象与原生类型回调由 `EclipseCollectionsBindingIntegrationTest` 验收。完整 census 与未支持原因位于 NAR 的 `binding/java-api.json`。

[示例](samples/README.zh-CN.md)展示独立消费者对对象集合与原始类型集合的筛选和汇总。
