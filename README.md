# 营养学 | 成人糖尿病食养助手 (Diabetes Food Guide Skill)

[English version](README.en.md)

基于**国家卫生健康委**发布的《**成人糖尿病食养指南（2023年版）**》的AI科普对话助手 | Nutrition Science Skill

> 🌱 初学AI，希望利用AI传播营养学知识，帮助更多的人。如果哪里不足，请大家多多指点，后续会努力做更多的营养学Skill。如果大家觉得还可以，请给我点个 ⭐ Star，谢谢！

---

## 指南出处

- **全称**：《成人糖尿病食养指南（2023年版）》
- **发布单位**：国家卫生健康委办公厅

## 功能特点

- **GI分类全覆盖**：高/中/低GI食物完整列表，科学控糖
- **食养原则**：8条官方原则，核心围绕"控糖、稳餐后、防并发症"
- **中医食养**：3种证型（阴虚热盛/气阴两虚/阴阳两虚）+ 9个食养方
- **地区食谱**：7大地区×4季节×3能量等级 = 84套完整食谱
- **食物交换表**：7类食物等量交换，灵活配餐
- **糖代谢诊断标准**：糖尿病前期+确诊的完整切点数据
- **科普风格**：说人话、给具象量、指误区——精准但不端着

## 关键数据速查

| 项目 | 推荐量 | 通俗理解 |
|------|--------|---------|
| 空腹血糖 | <6.1mmol/L（正常） / ≥7.0mmol/L（糖尿病） | 正常人的空腹血糖底线 |
| 餐后2h血糖 | <7.8mmol/L（正常） / ≥11.1mmol/L（糖尿病） | 餐后血糖更关键 |
| 主食定量 | 每餐1-2两（生重） | 一拳头大小的米饭 |
| 膳食纤维 | 25-30g/天 | 多吃蔬菜和全谷物 |
| 食盐 | <5g/天 | 一个啤酒瓶盖 |
| 烹调油 | ≤25g/天 | 两汤匙封顶 |
| 运动 | ≥150min/周中等强度 | 每天快走30分钟 |
| GI分级 | 低GI≤55 / 中GI55-70 / 高GI≥70 | 选低GI，控糖更轻松 |

## 知识体系

| KPK编号 | 主题 | 来源章节 |
|---------|------|---------|
| KPK-01~08 | 8大食养原则 | 食养原则章节 |
| KPK-09~12 | 附录知识（食物选择、GI分类、交换表、食养方、诊断标准） | 附录1-5 |
| KPK-13~14 | 疾病背景+问答版 | 前言+疾病特点+问答版 |

## 文件结构

```
diabetes-food-guide-skill/
├── skill.yaml           # Skill配置（含指南出处、创建者信息、免责声明）
├── system_prompt.md     # 系统提示词（科普对话风格）
├── knowledge_base.md    # KPK知识库（14个知识点）
├── recipes_data.md      # 7大地区84套完整食谱数据
├── recipes_overview.md  # 食谱概览与使用指南
├── dietary_formulas.md  # 9个食养方
├── README.md            # 本文件
├── install.sh           # Linux/macOS安装脚本
└── install.bat          # Windows安装脚本
```

## 声明

**免责声明**：
1. 本Skill内容全部来自《成人糖尿病食养指南（2023年版）》（国家卫生健康委办公厅发布），仅供食养科普参考，**不可替代药物治疗和专业医疗诊断**。
2. 血糖管理需结合药物、运动和饮食三个维度。
3. 胰岛素依赖型糖尿病患者方案需在医生指导下调整。
4. 食药物质使用应在专业人员指导下进行，不可自行超量服用。
5. 合并高血压、肾病等基础疾病者，须在专业医师和营养指导人员指导下辨证施膳。
6. 本Skill由AI辅助构建，虽力求忠实原文，但不排除存在转述偏差，如有疑义请以指南正式出版物原文为准。

## 创建者

**王润圆**
- 中国注册营养师
- 昆明医科大学 营养与食品卫生学 硕士
- 使用 WorkBuddy 构建

## License

MIT

<!-- Maintainer update: Runyuan Wang (9s5bz2jvd2-lang). -->

---

> **禁止抄袭商用，违者等同盗法，因果自负**
> **Plagiarism and commercial use are strictly prohibited. Violators shall be deemed as thieves of sacred scriptures and shall face divine karmic retribution themselves.**
>
> 公益开源项目，禁止商用 | Public welfare open-source project, commercial use prohibited
> License: CC BY-NC 4.0
