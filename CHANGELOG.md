# 更新日志

本文件遵循「一版一条」纪律：每个发布版本一个 `## v*` 条目；发布时由
插件 CI 校验当前版本必须有对应条目。

## v0.1.0

- 插件框架期骨架：plugin.json manifest / patches/index.json 补丁通道 /
  CI 清单门禁（validate_plugin.py）全部就绪
- 插件本体按 ROADMAP.md 排期实现（APK 资产自 v0.2 发布流水线起发布）

## v0.1.1

- 框架演练：补丁发布流水线首条记录
- manifest 升版与 changelog 载荷自动维护
- 宿主插件详情页即可增量应用
