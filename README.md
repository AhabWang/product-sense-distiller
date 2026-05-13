# Product Sense Distiller

Product Sense Distiller 是一个基于「王师傅产品哲学」构建的产品判断 Skill。

它不是通用产品分析模板，而是一个面向硬件产品经理的产品决策系统，用来帮助分析产品机会、定义硬件产品、拆解众筹案例、评估产品策略，并通过专家 Lens 补充不同视角。

核心目标只有一个：

> 让产品判断更锋利。

---

## 这个 Skill 适合做什么？

适合用于：

- 产品机会分析
- 硬件产品定义
- 用户场景分析
- 需求强度判断
- 购买决策分析
- 价值锚点 / 价格锚点判断
- PRD / Charter 评审
- 众筹案例分析
- 硬件可行性与风险检查
- 专家 Lens 分析
- 产品策略与表达优化

---

## 核心理念

默认使用「王师傅产品哲学」作为主脑。

重点判断：

- 用户是谁
- 场景是否真实
- 需求是否够硬
- 购买触发是什么
- 价值锚点是否清晰
- 价格锚点是否合理
- 产品定义是否聚焦
- 硬件现实是否能跑通
- 商业模型是否成立
- 下一步应该验证什么

默认原则：

> 先判断产品是否成立，再调用框架和专家 Lens 补充视角。

---

## 文件结构

    product-sense-distiller/
    ├── SKILL.md
    ├── README.md
    └── references/
        ├── 00-system-architecture.md
        ├── 01-wang-product-philosophy.md
        ├── 02-wang-judgment-rules.md
        ├── 03-hardware-pm-reality-check.md
        ├── 04-crowdfunding-analysis-framework.md
        ├── 05-product-definition-framework.md
        ├── 06-wang-expression-style.md
        ├── expert-lenses/
        │   ├── 01-jobs-lens.md
        │   ├── 02-zhang-xiaolong-lens.md
        │   ├── 03-zhang-yiming-lens.md
        │   ├── 04-elon-musk-lens.md
        │   ├── 05-tony-fadell-lens.md
        │   ├── 06-marty-cagan-lens.md
        │   └── 07-brian-chesky-lens.md
        └── cases/
            ├── eufy-bottle-washer-s1.md
            ├── evaporative-humidifier-nature-mist.md
            └── lumia-2.md

---

## 演示示例

示例 Prompt：

    用 product-sense-distiller 分析 Lumia 2 这个案例，重点看它为什么不是又一个 Oura / Whoop，以及它的新指标是否能成立为购买理由。

可能的输出方向：

- 一句话判断
- 核心矛盾
- 目标用户与场景
- 新指标的价值锚点
- 购买触发
- 众筹为什么成立
- 长期生意风险
- 下一步验证建议

---

## 最终原则

这个 Skill 不是为了把每个产品都说得很有前途。

它要回答的是：

> 这个产品在真实用户、真实购买决策、真实市场竞争、真实硬件约束、真实供应链和真实商业模型里，到底能不能成立？
