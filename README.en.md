# Nutrition Science | Adult Diabetes Food Guide Skill

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Adults with Diabetes (2023 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Adults with Diabetes (2023 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Complete GI classification coverage**: high-, medium-, and low-GI food lists for scientific glucose control
- **Dietary-nutrition principles**: 8 official principles centered on glucose control, stable post-meal glucose, and complication prevention
- **TCM dietary support**: 3 syndrome patterns (yin deficiency with heat / qi-yin deficiency / yin-yang deficiency) plus 9 dietary formulas
- **Regional menus**: 7 regions × 4 seasons × 3 energy levels = 84 complete meal plans
- **Food exchange tables**: 7 food categories for flexible meal planning
- **Glucose-metabolism diagnostic criteria**: complete cutoffs for prediabetes and diabetes diagnosis
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Fasting blood glucose | <6.1 mmol/L normal / ≥7.0 mmol/L diabetes | Baseline fasting glucose reference |
| 2-hour post-meal glucose | <7.8 mmol/L normal / ≥11.1 mmol/L diabetes | Post-meal glucose is especially important |
| Staple-food portion | 1–2 liang raw weight per meal | About a fist-sized amount of rice |
| Dietary fiber | 25–30 g/day | Eat more vegetables and whole grains |
| Salt | <5 g/day | About one beer-bottle cap |
| Cooking oil | ≤25 g/day | No more than about two tablespoons |
| Exercise | ≥150 min/week moderate intensity | About 30 minutes of brisk walking daily |
| GI level | Low GI ≤55 / medium 55–70 / high ≥70 | Choose low-GI foods for easier glucose control |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~08 | Eight dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-09~12 | Appendix knowledge: food choices, GI classification, exchange tables, dietary formulas, diagnostic criteria | Appendices 1–5 |
| KPK-13~14 | Disease background + Q&A version | Preface + disease characteristics + Q&A version |

## File Structure

```text
- skill.yaml: Skill configuration
- system_prompt.md: System prompt
- knowledge_base.md: KPK knowledge base with 14 knowledge points
- recipes_data.md: 7 regions and 84 complete menus
- recipes_overview.md: Menu overview and usage guide
- dietary_formulas.md: 9 dietary formulas
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medication treatment or professional medical diagnosis.
2. Glucose management should combine medication, exercise, and diet.
3. Insulin-dependent diabetes plans should be adjusted under medical guidance.
4. Food-medicine substances should be used under professional guidance and not taken in excessive amounts.
5. People with hypertension, kidney disease, or other underlying conditions should receive professional physician and nutrition guidance.
6. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT
