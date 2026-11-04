# GitHub 调研与综合取舍

调研日期：2026-11-03。阅读各仓库 main 分支 SKILL.md；分支内容后续可能变化。以下为概念提炼，非逐段复制，也未执行来源仓库代码。

| 来源 | 类型与亮点 | 综合时的取舍 |
|---|---|---|
| [blader/humanizer](https://github.com/blader/humanizer/blob/main/SKILL.md) | 写作去模式化，关注重复结构和夸大 | 引入事实对照，避免把英文标点偏好变成中文禁令 |
| [dmmdea/humanize-presentations](https://github.com/dmmdea/humanize-presentations/blob/main/SKILL.md) | 直接针对已有 PPT，区分页面与备注、考虑有意设计 | 作为 PPT 专项判断的重要参考；不照搬固定字数和符号删除规则 |
| [hannsxpeter/humanizer](https://github.com/hannsxpeter/humanizer/blob/main/SKILL.md) | 保留作者语气、克制编辑与事实保护 | 尊重样稿和领域语体，不统一改成聊天口吻 |
| [jpeggdev/humanize-writing](https://github.com/jpeggdev/humanize-writing/blob/main/SKILL.md) | 分层编辑、朗读检查与变化说明 | 采用分层复核；不沿用可能诱导虚构经历或来源的示例写法 |
| [anthropics/skills: pptx](https://github.com/anthropics/skills/blob/main/skills/pptx/SKILL.md) | 文件制作、编辑、渲染与视觉 QA | 提炼实际渲染验证；不把其环境依赖和风格偏好当成本机事实 |
| [anthropics/skills: frontend-design](https://github.com/anthropics/skills/blob/main/skills/frontend-design/SKILL.md) | 主题驱动视觉、克制默认装饰 | 迁移到演示稿的主次和版式选择，不迁移网页实现规则 |

前四项偏去 AI 味；后两项为制作与设计补充，并非专门的中文 PPT humanizer。

## 共性与新增判断

综合判断：具体信息比辞藻有效；机械重复比单个词更值得审查；风格须适配作者与受众；编辑完成后需要复核实际输出。

本技能补充中文汇报腔处理、现场演讲与独立阅读的分流、证据不足时的降级写法，以及保持事实不变的案例。将来源之间冲突的规则改成条件判断：三项列表、纯文字页、品牌配色和正式标题都有合理用途。

这些是编辑与设计启发式，不构成 AI 来源检测方法。未进行真实用户 PPT 的前后对比效果测试；技能结构验证不等于设计效果验证。
