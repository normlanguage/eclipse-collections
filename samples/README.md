# Eclipse Collections samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) filters a `FastList` and aggregates a primitive `IntArrayList`. It is a standalone consumer with its own `Module module()` dependency.

From the repository root, run:

```sh
norm run samples/hello.norm
```

Expected output: `2` selected labels, then an odd-number sum of `8`. The package is built from [module.norm](../eclipse/collections/module.norm), which pins Eclipse Collections 13.0.0 and defines the exposed API.
