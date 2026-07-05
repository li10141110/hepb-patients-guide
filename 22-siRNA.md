# Ch 22 · siRNA

> 关掉 HBsAg 工厂的开关。

---

## 一分钟理解 siRNA

siRNA = **small interfering RNA**(小干扰 RNA)。

原理:

1. 你注射进去一段**人工设计的双链 RNA**
2. 这段 RNA 序列**和 HBV 的 mRNA 互补**
3. 它进入细胞后,和 HBV mRNA 结合
4. 细胞里的 RNAi 机器把这段 mRNA **切成两段**、降解
5. HBsAg 和其他 HBV 蛋白**造不出来**

**一句话:让 HBV 的 mRNA "全部作废"。**

---

## 为什么它是革命性的

回顾第 4 章那张表——**siRNA 打的是 mRNA,不是 DNA**。

结果:

- **cccDNA 的 mRNA** — 被切
- **整合 DNA 的 mRNA** — **也被切**

**这是核苷药做不到的"通吃两个来源"。**

临床数据显示,siRNA 能把 HBsAg 降 **2-3 个 log**——从 10⁴ 降到 10¹ 级别,是核苷药几十年都做不到的深度。

---

## 目前的主要候选药

**Vir-2218**(Vir Biotechnology)
- 皮下注射
- 每 4 周一次
- 已进入 II/III 期
- 常与 Peg-IFN 或治疗性抗体 VIR-3434 联合

**JNJ-3989**(Arrowhead / Janssen)
- 也叫 ARO-HBV
- II/III 期
- 与 NUCs 联合

**RG6346**(Roche / Dicerna)
- 也叫 DCR-HBVS
- II 期
- 数据显示强力 HBsAg 下降

**Elebsiran**(Alnylam)
- II 期
- 半衰期长,给药频率更低

**中国候选药**:恒瑞、正大天晴、Silence Therapeutics 合作项目等,详细阶段待用最新数据核对。

---

## GalNAc 递送:让药物精准到肝

siRNA 之所以能进入临床,离不开一个技术突破——**GalNAc 结合**。

GalNAc(N-乙酰半乳糖胺)是肝细胞表面 **ASGPR 受体**特异识别的糖分子。把 siRNA 和 GalNAc 连起来,注射后:

- 皮下注射进入血液
- 血液流经肝脏,肝细胞的 ASGPR "抓住" GalNAc
- siRNA 被内吞进肝细胞
- 精准到达 HBV mRNA 所在位置

**这就是为什么现代 siRNA 药物几乎全部靶向肝脏——GalNAc 天然只识别肝细胞。**

---

## 效果:HBsAg 深度下降

一些代表性临床数据:

**JNJ-3989 + NUC**:
- HBsAg 下降 **1.5-2.5 log**
- 大部分患者达到 < 100 IU/mL
- 少数达到 < 10 IU/mL

**VIR-2218 单药**:
- HBsAg 下降 **1.5-1.7 log**
- 部分患者接近功能性治愈的临界值

**siRNA + Peg-IFN**:
- HBsAg 下降更深
- 少数达到 HBsAg 转阴(约 5-15%)

**siRNA + 治疗性疫苗或 PD-1**:
- 早期数据显示叠加效应
- 停药后维持率仍在观察中

---

## 优点

- **深度降 HBsAg** — 这是核心武器
- **通吃 cccDNA + 整合** — 覆盖两个来源
- **注射频率友好** — 一般每 4-12 周一次
- **口服核苷药相比,能实现"停药后维持"的可能性**
- **副作用总体温和**——注射部位反应,偶见 ALT 升高

---

## 缺点和挑战

**① 停药后 HBsAg 会反弹**
- siRNA 不消灭 cccDNA
- 停药后 mRNA 又开始被转录
- HBsAg 会缓慢回升
- **除非**停药前免疫系统被"重新训练"

**② 需要长期或联合方案**
- 单药很难独自实现治愈
- 必须搭配免疫策略

**③ 免疫反弹相关的 ALT 升高**
- 部分患者用药中或后 ALT 升高
- 通常是免疫开始活跃的迹象(可以是好事)
- 但也可能是免疫过度(坏事)
- **需要密切监测**

**④ 长期安全性尚在积累**
- siRNA 在 HBV 领域临床应用不到 10 年
- 长期(> 5 年)数据还有限

---

## siRNA vs ASO 简单对比

siRNA 和 ASO 常被并列讨论,但机制略有不同:

| 维度 | siRNA | ASO |
|------|-------|-----|
| 化学结构 | 双链 RNA | 单链 DNA-like |
| 切割机制 | RISC 复合体切 mRNA | RNase H 切 mRNA |
| 靶点选择 | 更严格 | 灵活性略高 |
| 给药频率 | 4-12 周 | 每周(bepirovirsen) |
| 递送 | GalNAc | 部分 GalNAc,部分裸露 |
| 代表药 | VIR-2218、JNJ-3989 | Bepirovirsen |

**都是 mRNA 层面攻击,效果类似,细节不同。**

---

## 一个患者视角

如果你在关注 siRNA 试验:

**入组常见要求:**
- HBsAg > 500 或 > 1000 IU/mL
- 已经稳定核苷药治疗
- 无肝硬化或轻度纤维化
- ALT < 2-3 × ULN

**试验期间要求:**
- 定期抽血(密集)
- 皮下注射(通常肚脐周围)
- 长期随访

**结束后:**
- 停药观察
- HBsAg 反弹很常见——不用绝望
- 一小部分达到功能性治愈——那就是你

---

## 5-10 年后的图景

如果我押注,siRNA 是**未来 5 年最有可能获批的新型药物之一**。

**可能的场景:**

- **2027-2029** — Bepirovirsen(ASO)或 VIR-2218(siRNA)获批,作为核苷药**附加**方案
- **2030+** — siRNA + 免疫的联合方案获批
- **2035+** — siRNA 加入初治标准方案,替代或与 NUC 组合

**siRNA 不会独自治愈乙肝,但它是"第一次真正在 HBsAg 上取得突破"的药物类别。**

---

## 📍 本章要点

- siRNA **降解 HBV mRNA**,让 HBsAg 造不出来
- **通吃 cccDNA 和整合 DNA 两个来源**
- 靠 GalNAc 递送,精准到肝
- HBsAg 深度下降 2-3 log(核苷药做不到)
- 主要候选:**VIR-2218、JNJ-3989、RG6346、Elebsiran**
- 单药不能治愈,需要联合免疫策略
- **是未来 5 年最有希望获批的新型药物之一**

---

**延伸阅读**
- Yuen MF. et al. *JNJ-3989 in chronic HBV*. Lancet Gastroenterol Hepatol. 2022
- Gane E. et al. *VIR-2218 clinical data*. J Hepatol. 2023

> 下一章 → [Ch 23 · ASO](./23-ASO.md)
