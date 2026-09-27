# Caffeine 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) —— 创建有容量上限的缓存，读取值后使其失效。这是通过自身的 `Module module()` 声明依赖的独立消费者程序。

在仓库根目录运行：

```sh
norm run samples/hello.norm
```

[module.norm](../caffeine/cache/module.norm) 指定 Java 制品版本并定义公开 API。

预期输出：

```text
Norm
missing
```

API 入口：[module.norm](../caffeine/cache/module.norm) 列出公开的 `Caffeine` 和 `Cache`。`Main.norm` 仍是该适配器自身的集成入口。
