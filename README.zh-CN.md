# Caffeine

[English](README.md) | [简体中文](README.zh-CN.md)

适配声明与可运行示例位于 `caffeine/cache`，固定 Caffeine 3.2.4，发布坐标见 [module.norm](caffeine/cache/module.norm)。公开面覆盖常用容量与过期配置、显式缓存读写、映射加载、失效、清理和统计。

独立 NAR 消费、传递依赖解析、Norm Duration、回调加载和缓存统计由 `CaffeineBindingIntegrationTest` 验收。完整 census 与未支持原因位于 NAR 的 `binding/java-api.json`。

[可运行示例](samples/README.zh-CN.md) 展示如何作为外部 Norm 依赖使用本库。

[许可证](LICENSE)
