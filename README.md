# Fiction Writing Framework — 预览版

本目录为虚构文学创作框架的精选预览，展示框架的核心能力与知识体系。

完整版本包含 13 个子 skill、84 个文件，覆盖从立项到出版的全生命周期编排、子任务路由、治理机制、发布脚本与全部文档模板。

> 如需了解完整的编排流程、子 skill 触发逻辑与协作机制，请[联系我们](https://github.com/icimik/fiction-skill-sample/issues/new?labels=Request+for+Quotation)获取完整版文档。

---

## 文档索引

### 框架入口

| 文件 | 说明 |
|------|------|
| [SKILL.md](./SKILL.md) | 框架总览：skill 索引、全生命周期阶段划分、核心原则 |

### 叙事知识库

| 文件 | 说明 |
|------|------|
| [character.md](./skills/narrative-knowledge/references/character.md) | 角色设计方法论——荣格面具与阴影、格雷马斯动体模型、苏格拉底式对话交锋 |
| [worldbuilding.md](./skills/narrative-knowledge/references/worldbuilding.md) | 世界观搭建——托尔金次级信仰、桑德森力量体系三定律、海明威冰山理论 |
| [structure-toolbox.md](./skills/narrative-knowledge/references/structure-toolbox.md) | 11 种叙事结构的适用场景、实施方法与组合模板（故事圈、三幕、七点式、费希特曲线等） |

### 评审体系

| 文件 | 说明 |
|------|------|
| [scoring-rubric.md](./skills/review-rubric/references/scoring-rubric.md) | 统一评分标准——10 通用维度 + 3 出版附加维度 + 分歧分析规则 |
| [mbti-readers.md](./skills/review-rubric/references/mbti-readers.md) | MBTI 读者评审系统——8 种读者原型、四层架构、与出版编辑流程的衔接 |
| [INFP.md](./skills/review-rubric/references/personas/INFP.md) | 读者角色卡示例（INFP·人物共鸣读者）——偏好权重、反馈口吻、判断逻辑 |

### 中文写作规范

| 文件 | 说明 |
|------|------|
| [anti-patterns.md](./skills/chinese-writing-constraints/references/anti-patterns.md) | 12 种高频翻译腔模式识别 + 中文叙事正面特征 + 伪高级句式清单 |

### 出版与样式

| 文件 | 说明 |
|------|------|
| [publication-build.sample.json](./assets/publication-build.sample.json) | 出版构建配置示例 |
| [vivliostyle-book.css](./assets/vivliostyle-book.css) | A5 书籍排版样式表（中文字体、页眉、目录、正文缩进） |

### 文档模板

| 文件 | 说明 |
|------|------|
| [模板_STYLEGUIDE.md](./skills/templates/references/立项/模板_STYLEGUIDE.md) | 项目级风格约束模板——叙事基线、POV 区分、中文语言规则、复核流程 |
| [模板_SOUL.md](./skills/templates/references/样章/模板_SOUL.md) | 角色 SOUL 模板——驱动力、思维习惯、说话方式、书写红线、OOC 风险防控 |

---

## 完整版包含但预览版未展示的内容

- **流程层 skill**：fiction-create / fiction-rewrite / fiction-review / fiction-publish / fiction-import 的触发条件与执行逻辑
- **治理机制**：协作流程、阶段裁决规则、联动更新机制、字数统计脚本
- **完整模板库**：18 个文档模板，覆盖立项、规划、导入、样章、审阅、发布、运营全阶段
- **市场调研**：调研方法论 + 日本轻小说与中国网文市场调研报告
- **亲密内容分级**：L0-L5 分级标准与写作指南
- **MBTI 读者角色卡**：全部 8 种读者原型的完整画像
- **中文语言规范**：现代汉语语法、词汇、修辞三大规范文档（共 50K 字）
- **出版构建脚本**：Pandoc 自动化构建流水线
