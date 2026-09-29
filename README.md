# manus-skills

个人 agent 技能库，按 `SKILL.md` 约定组织，可直接导入 Manus。

共 84 个技能，全部是纯指令型（只含 `SKILL.md` 与随附参考资料），不依赖本机环境、密钥或本地服务。

## 导入到 Manus

1. 打开 Manus，左侧菜单进入 **Skills**，点击 **+ Add**，选择 **Import from GitHub**。
2. 粘贴某个技能的**子目录**链接，例如：
   `https://github.com/liujieranjerry-lgtm/manus-skills/tree/main/skills/luopan`
3. 点击 **Import**。导入后在任意任务里输入 `/` 即可调用。

完整清单见 [CATALOG.md](CATALOG.md)。

## 使用提示

- Manus 会在启动时加载每个技能的元数据（约 100 tokens），导入数量过多会持续占用上下文，建议只导入当前用得上的。
- 本库只收录指令型技能。依赖本机钥匙串、本地 MCP 服务、本机登录态的脚本型技能不在范围内，需要时应在 Manus 内用它的内置工具重写。

## 版权

本库为个人使用的技能集合，其中包含来自第三方开源项目的技能。各技能版权与许可归其作者所有，详见 [ATTRIBUTION.md](ATTRIBUTION.md)。
