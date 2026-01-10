# Changelog

本项目的所有重要更改都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)，
版本号遵循 [语义化版本](https://semver.org/lang/zh-CN/)。

## [1.0.1] - 2026-01-10

### Changed

- 添加调试信息输出（Cookie 解析数量、页面标题、按钮状态）
- 优化已签到状态检测逻辑
- 按钮禁用时尝试 JavaScript 强制点击
- 失败时保存截图用于调试

### Fixed

- 修复已签到时按钮禁用导致的超时错误

## [1.0.0] - 2026-01-10

### Added

- 初始版本发布
- 支持每天三次自动签到（北京时间 8:00、12:00、20:00）
- 使用 Playwright 模拟浏览器操作
- 通过 Cookie 认证登录状态
- 支持手动触发签到（workflow_dispatch）
