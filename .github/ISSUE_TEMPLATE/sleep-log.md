---
name: 💤 Sleep Check-in
about: 创建一个睡眠打卡记录 issue
title: '[Sleep Log] '
labels: ''
assignees: ''
---

## 💤 睡眠打卡记录

使用以下命令记录你的睡眠：

- `/sleep` - 记录当前时间为入睡时间
- `/wake` - 记录当前时间为起床时间
- `/sleep YYYY-MM-DD HH:MM backfill` - 补记/修正（仅最近7天，且只能改更晚）
- `/wake YYYY-MM-DD HH:MM backfill` - 补记/修正（仅最近7天，且只能改更晚）
- `/rebuild` - 从事件日志重建表格（当你手动改坏表格或怀疑显示不对时使用）

> 注意：表格是“展示层”，请不要手动编辑表格内容。
> 任何手动修改都会在下一次命令触发或 `/rebuild` 时被覆盖（以机器人事件日志为准）。

---

<!-- SLEEP_LOG_ENABLED -->

<!-- SLEEP_LOG_TABLE_START -->

| Date | Sleep (UTC+8) | Wake (UTC+8) | Duration | Source |
|---|---|---|---|---|

<!-- SLEEP_LOG_TABLE_END -->

---

### 📝 备注（可选）

<!-- 可以在这里写一些关于睡眠质量、梦境等的笔记 -->
