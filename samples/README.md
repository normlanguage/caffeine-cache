# Caffeine samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) — Create a bounded cache, read a value, then invalidate it. This is a standalone consumer with its own `Module module()` dependency.

From the repository root, run:

```sh
norm run samples/hello.norm
```

[module.norm](../caffeine/cache/module.norm) pins the Java artifact and defines the public API.

Expected output:

```text
Norm
missing
```

API reference: [module.norm](../caffeine/cache/module.norm) lists the exposed `Caffeine` and `Cache`. The [adapter acceptance example](../examples/sample/caffeine/cache/Main.norm) exercises additional binding behavior.
