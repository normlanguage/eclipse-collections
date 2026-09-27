# Eclipse Collections

[English](README.md) | [简体中文](README.zh-CN.md)

The adapter declaration and runnable example are in `eclipse/collections`. It pins Eclipse Collections 13.0.0 and the matching API artifact, and defines its package coordinates in [module.norm](eclipse/collections/module.norm). The public API covers `FastList`, `UnifiedSet`, `UnifiedMap`, `FastListMultimap`, `IntArrayList`, and common filtering, transformation, grouping, and primitive integer collection operations.

`EclipseCollectionsBindingIntegrationTest` covers standalone NAR consumption, the transitive API dependency, inherited public methods, and object and primitive callbacks. The complete API census and reasons for unsupported APIs are in the NAR's `binding/java-api.json`.

[Samples](samples/README.md) include a standalone consumer that filters object and primitive collections.
