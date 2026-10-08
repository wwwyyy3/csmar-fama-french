# csmar-fama-french（Claude Code Skill）

CSMAR 数据采集与 Fama-French 三因子（MKT/SMB/VMG）构建工作流 skill：6 类数据下载清单（库路径/表名/字段/文件名）、下载后检查清单、预处理约定（EP/BM 时滞匹配、无风险利率前向填充、月末 2×3 分组）与常见问题。

## 安装

将本目录放到：

- 项目级：`<项目>/.claude/skills/csmar-fama-french/`
- 用户级（全局）：`C:\Users\<你>\.claude\skills\csmar-fama-french\`

## 触发

- 自动：任务中出现「CSMAR / 因子 / Fama-French / 下载数据 / Mretwd / 市值 / PE / SMB / VMG / 无风险利率」等关键词时自动加载
- 手动：`/csmar-fama-french`
