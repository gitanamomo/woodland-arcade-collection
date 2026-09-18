# STRUCTURE

- `index.html`: 完整单页游戏，包含 HTML、CSS、Canvas 2D 绘制、状态机与 WebAudio 音效。
- 状态：`idle`、`show`、`input`、`won`。
- 核心数据：`fireflies` 光点实体、`seq` 当前序列、`input` 玩家输入、`level` 层数。
- 渲染：响应式 Canvas，绘制背景渐变、星点、远景植被、萤火虫光晕、波纹与粒子。
- 持久化：`localStorage.fireflyBest` 保存本地最佳得分。
