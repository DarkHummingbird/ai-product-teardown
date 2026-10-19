# AI 产品拆解 Skill

用于深度分析 AI 产品、创作平台与 Agent：从真实任务和用户体验进入，展开商业、用户流程、技术、模型、资产与壁垒分析，交付独立的产品拆解文档。

## 能做什么

- 支持网页、手机 App、桌面客户端、插件和用户提供的材料。
- 通过真实操作、截图及公开资料形成分析；没有实测的效果不冒充实测。
- 展开上下文、Agent 职责、工具和人机分工，不虚构多 Agent 架构。
- 用具体型号、用途、参数与费用表分析模型；证据充分才评分。
- 输出 Markdown、HTML，或在具备访问权限的环境中生成飞书文档。
- 提供四层框架 SVG 模板，重要架构图导出图片并嵌入文档。

## 安装到 Codex

将仓库克隆到个人技能目录；目标目录已存在时应先检查已有修改，再更新。

```sh
git clone https://github.com/DarkHummingbird/ai-product-teardown.git ~/.codex/skills/ai-product-teardown
```

如果设置了自定义 `CODEX_HOME`，使用其 `skills/ai-product-teardown` 目录。安装后在新会话中调用。

## 使用示例

```text
使用 $ai-product-teardown 拆解这个 AI 产品：<产品名或官网链接>。
按完整深度输出 Markdown，包含体验截图、模型分类表、用户流程图和整体框架图。
```

```text
只依据我提供的产品材料分析，不额外联网。输出独立产品文档，
核实记录留在内部，不在成稿展示证据标签或待核实清单。
```

默认章节为：拆解思路、产品介绍、场景体验、产品定位、分层产品拆解、整体框架。可根据目标产品或用户要求调整。

## 文件说明

| 文件 | 用途 |
| --- | --- |
| [SKILL.md](SKILL.md) | 技能入口与工作规则 |
| [references/analysis-framework.md](references/analysis-framework.md) | 五层分析与效果评价 |
| [references/agent-analysis.md](references/agent-analysis.md) | Agent、上下文与工具深拆 |
| [references/evidence-verification.md](references/evidence-verification.md) | 内部核实与二次验证 |
| [references/report-delivery.md](references/report-delivery.md) | 章节、表格、截图及交付规则 |
| [references/diagram-template.md](references/diagram-template.md) | 图形布局与内容替换说明 |
| [assets/four-layer-framework.svg](assets/four-layer-framework.svg) | 可编辑四层框架样例 |

框架底稿包含 LibTV 样例文字，使用时必须替换，不能作为其他产品的事实。浏览器、联网和文档写入能力取决于运行环境；付费生成、授权、发布等操作仍遵循实际用户授权。

## 方法来源

本技能将分析方法整理为可复用流程，参考 [W3D1 · AI 产品拆解](https://w3d1.vercel.app/) 及 [OiiOii Multi Agent 产品拆解案例](https://qiif643fw66.feishu.cn/wiki/FURJwrpJ0i3efOkPauKcRxbTnVh)。参考内容的权利归原作者；仓库不包含其文档截图、全文或用户研究记录。

## 许可

本仓库原创技能指令与模板以 [MIT License](LICENSE) 开源。第三方产品、模型名称及外部参考资料不因本许可而改变其权利归属。
