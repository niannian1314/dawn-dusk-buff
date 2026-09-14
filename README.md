# 终黎双生 / Dawn-Dusk Buff

新增两个**互斥**的状态效果：

| 效果 | 中文名 | 英文名 | 作用 |
|------|--------|--------|------|
| `zhong_mark` | 终之印记 | Mark of Terminus | 每级提供 **+10% 伤害减免**，满 10 级完全免伤 |
| `li_mark` | 黎之印记 | Mark of Dawn | 每级 **+10% 受到的伤害** |

同时持有两者时，按**等级差**结算净效果（终的减免抵消黎的承伤）。

- modId：`dawn_dusk_buff_mod_1788600495`（MCreator 自动生成的带数字后缀）
- 版本：`1.0.0`
- 环境：**Minecraft 1.20.1–1.21 / Forge 47.4.10+**
- 作者：2046820954@qq.com
- 依赖：仅 Forge + Minecraft，无其他 mod 依赖
- License：**All Rights Reserved**（原 mods.toml 声明）

## 备注

- 原 jar 内 `META-INF/mods.toml` 的 `description` 字段因 MCreator 导出编码问题显示为乱码，本仓库的 `mods.toml` 已改写为正确中文（功能字段保持不变）。
- 两个效果图标（`li_mark.png` / `zhong_mark.png`）为二进制，未通过文本 API 上传。

## 仓库内容说明

本次通过 GitHub API 提交的是文本资源：`mods.toml`、`MANIFEST.MF`、`pack.mcmeta`、中英文语言文件。

以下**二进制文件未包含**（上传通道仅支持文本）：

- `cn/autoforged/dawn_dusk_buff_mod_1788600495/**/*.class`（5 个 .class，效果/事件逻辑）
- `assets/.../textures/mob_effect/*.png`（两个效果图标）

完整可运行的 `dawn_dusk_buff_mod-1.0.0.jar` 请通过 GitHub 网页「Add file → Upload files」拖拽上传，或在 Release 中发布。
