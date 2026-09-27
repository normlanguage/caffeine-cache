# Caffeine

[English](README.md) | [简体中文](README.zh-CN.md)

The adapter declaration and runnable example are in `caffeine/cache`. It pins Caffeine 3.2.4 and publishes as `caffeine:cache:1`. The public API covers common capacity and expiration settings, explicit cache reads and writes, mapping loads, invalidation, cleanup, and statistics.

`CaffeineBindingIntegrationTest` covers standalone NAR consumption, transitive dependency resolution, Norm Duration, callback loading, and cache statistics. The complete API census and reasons for unsupported APIs are in the NAR's `binding/java-api.json`.
