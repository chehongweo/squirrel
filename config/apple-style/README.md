# Apple Style 配置

这组文件保存 Apple Style 的界面设置、快捷键和 `rime_ice` 方案补丁，不包含词库和用户词频数据。

将这三个 YAML 文件复制到 `~/Library/Rime/` 后，执行：

```bash
/Library/Input\ Methods/Squirrel.app/Contents/MacOS/Squirrel --reload
```

主题由 `squirrel.custom.yaml` 中的 `apple_style` 和 `apple_style_dark` 控制；macOS 浅色、深色外观会自动选择对应主题。
