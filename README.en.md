# Nutrition Science | Osteoporosis Nutrition Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Adults with Osteoporosis (2026 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Adults with Osteoporosis (2026 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Bone-risk assessment**: IOF one-minute 19-question self-test plus OSTA index calculation
- **Calcium and vitamin D**: calcium-supplement planning, vitamin D transport role, and 25(OH)D target management
- **Dietary-nutrition principles**: detailed interpretation and practical advice for 8 official principles
- **TCM dietary support**: 2 syndrome patterns (spleen-kidney yang deficiency / liver-kidney yin deficiency) plus seasonal health preservation
- **Regional menus**: 7 regions × 4 seasons × 3 energy levels, with calcium-content annotation
- **Fall-prevention guidance**: exercise, sun exposure, and weight management
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Calcium (age 50+) | 1000–1200 mg/day | One jin of milk is about 500 mg; more is still needed |
| Vitamin D (ages 18–64) | 10 μg (400 IU)/day | One standard vitamin D tablet |
| Vitamin D (age ≥65) | 15 μg (600 IU)/day | Older adults need more |
| Protein | 1.2–1.5 g/kg/day | For 60 kg, about 72–90 g |
| Dairy | ≥300 mL/day | Start with one cup of milk |
| Salt | <5 g/day | About one beer-bottle cap |
| Cooking oil | ≤25 g/day | No more than about two tablespoons |
| Sun exposure | 10–20 minutes/day | Expose arms and face; avoid noon |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~08 | Eight dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-09~14 | Diagnosis, food choices, exchange tables, menus, formulas, and risk tools | Appendices |
| KPK-15~17 | Definition, TCM understanding, and guideline use | Preface + disease characteristics + Q&A |

## File Structure

```text
- skill.yaml: Skill configuration
- system_prompt.md: System prompt
- knowledge_base.md: KPK knowledge base with 17 knowledge points
- recipes_data.md: 7 regions and 84 menus with calcium annotation
- recipes_overview.md: Menu overview and usage guide
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medication treatment or professional medical diagnosis.
2. Osteoporosis diagnosis requires DXA bone-density testing; self-test tools are only preliminary screening.
3. People at high fracture risk must receive professional treatment guidance.
4. Food-medicine substances and nutrition supplements should be used under professional guidance and not taken in excessive amounts.
5. People with hypertension, diabetes, kidney disease, or other underlying conditions should receive professional physician and nutrition guidance.
6. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT

<!-- Maintainer update: Runyuan Wang (9s5bz2jvd2-lang). -->
