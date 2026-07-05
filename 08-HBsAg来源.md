# Ch 8 · HBsAg 从哪里来

> 弄懂这个,才明白新药为什么能做到老药做不到的事。

---

## 一个简单但被忽略的问题

医生跟你说:"HBsAg 转阴就是治愈了。"

那问题来了——**HBsAg 到底从哪造出来的?**

答案不是一个,是**两个**:

1. **cccDNA** — 经典来源
2. **整合 DNA** — 长期被忽略的来源

这两个来源的比例,在感染的不同阶段是不同的。

---

## 感染早期:主要靠 cccDNA

刚感染,或者未治疗的慢性感染者:

- cccDNA 是活跃的,pgRNA 大量转录
- HBsAg 主要来自 cccDNA 转录 → S mRNA → 表面蛋白
- HBV DNA、HBeAg、HBsAg 三者常常**同向变化**

这是教科书里"标准"的乙肝画面。

---

## 长期治疗后:主要靠整合 DNA

吃了几年核苷药之后,情况变了。

- HBV DNA 被压到检测不到
- cccDNA 数量减少,而且很多被"沉默"
- 但你会发现——**HBsAg 依然阳性,而且死活降不下去**

Johns Hopkins 团队 2025 年的研究直接测到了这个现象:

> **长期治疗后,HBsAg 转录来源从 cccDNA 迁移到整合 DNA。**

也就是说,**当 cccDNA 被压下去后,整合 DNA 接管了 HBsAg 生产。**

**这就是为什么核苷药永远做不到 HBsAg 转阴——它从没针对整合 DNA。**

---

## 一张图看清

```
     感染早期                长期治疗后
   ┌──────────┐           ┌──────────┐
   │ cccDNA ██│           │ cccDNA ▓ │  ← 被压制
   │        ██│           │          │
   │ 整合 ▓▓  │           │ 整合 ██▓▓│  ← 变成主力
   └──────────┘           └──────────┘
        ↓                       ↓
       HBsAg                   HBsAg
      (混合)               (主要来自整合)
```

---

## 为什么这个"来源迁移"这么重要

三个原因:

**① 它解释了老药的天花板**

核苷药、干扰素——都作用在 cccDNA 相关环节。一旦 HBsAg 主要来自整合,这些药就打不到了。

**② 它解释了新药为什么能突破**

siRNA 和 ASO 打的是 **mRNA**。整合 DNA 也要转录 mRNA,所以 siRNA/ASO **能一起打**。

第 4 章那张对比表最后一行:"通吃 cccDNA + 整合"——就是这个意思。

**③ 它重新定义了"HBsAg 消失"的意义**

如果 HBsAg 转阴,不代表 cccDNA 清除,也不代表整合 DNA 消失——**只代表这两个源头都被压得足够安静**。

所以"功能性治愈"这个术语选得很精准——**是"功能上不再造抗原",而不是"彻底根除病毒"**。

---

## HBeAg 又是什么情况

顺带把 HBeAg 讲清楚,免得混淆。

- **HBeAg 只能从 cccDNA 产生**,整合 DNA **不产 HBeAg**(因为整合位点通常缺 C 区完整启动子)
- 所以 HBeAg 是**cccDNA 活跃程度的直接指标**
- HBeAg 转阴,通常意味着 cccDNA 转录被大幅压制
- 但 HBsAg 还阳性——因为整合 DNA 还在造

**这就解释了"HBeAg 阴性、HBsAg 阳性"这一大类患者的分子基础。**

---

## HBV RNA 是什么

近几年临床试验频繁出现一个新指标:**血清 HBV RNA**。

它是什么?

- cccDNA 转录出 pgRNA,大多数被包进核衣壳
- 一小部分包着 pgRNA 的核衣壳会被分泌到血里
- 血里的 HBV RNA,**主要反映 cccDNA 的活跃转录状态**

为什么重要?

- HBV DNA 被核苷药压到测不到,不代表 cccDNA 不活跃
- 但如果 **HBV RNA 也测不到**,说明 cccDNA 转录本身也被压制了
- 停药后 HBV RNA 的变化,能预测反弹风险

**HBV RNA 现在被当作 cccDNA 活性的替代标志物**,尤其在新药试验里。

---

## HBcrAg 是什么

另一个新指标:**乙肝核心相关抗原(HBcrAg)**。

它是一个"混合物",包含:
- HBcAg(核心抗原)
- HBeAg(e 抗原)
- 一部分核心蛋白前体

意义:反映 cccDNA 池的**总活性**。

HBcrAg 高,提示 cccDNA 活跃;低,提示被抑制或减少。

**在临床上,HBcrAg 越来越用来判断:**
- 停药后反弹风险
- HCC 长期风险
- 新药的深度抗病毒效果

---

## 一张综合指标表

| 指标 | 反映 | 用途 |
|------|------|------|
| HBV DNA | 病毒复制 | 常规监测 |
| HBsAg 定量 | cccDNA + 整合 | 治愈评估 |
| HBeAg | cccDNA 活跃 | 分期、疗效 |
| **HBV RNA** | cccDNA 转录 | **新药试验替代终点** |
| **HBcrAg** | cccDNA 池总量 | **停药预测、HCC 风险** |
| ALT/AST | 肝损伤 | 炎症监测 |

前三个是老熟人,**后两个是新药时代的关键指标**。

---

## 回到治愈:两个来源都要搞定

一句话总结:

> **要 HBsAg 转阴,必须同时压制 cccDNA 和整合 DNA。**
>
> **要真正根除,还得清除 cccDNA、让感染细胞死掉、让整合 DNA 沉默。**

**新药联合疗法的整个逻辑,就建立在这个"两个来源"的认识之上。**

---

## 📍 本章要点

- HBsAg 有两个来源:cccDNA 转录 + 整合 DNA 转录
- 感染早期以 cccDNA 为主
- **长期治疗后主要来自整合 DNA**——这是核苷药的天花板
- siRNA / ASO 打 mRNA,能通吃两个来源
- HBeAg 只从 cccDNA 来,是 cccDNA 活性直接指标
- **HBV RNA 和 HBcrAg 是新一代 cccDNA 活性替代指标**

---

**延伸阅读**
- Wooddell CI. et al. *HBsAg from integrated DNA sustains circulation after nucleic acid therapy*. Sci Transl Med. 2017
- Johns Hopkins. *Transcription of HBsAg shifts from cccDNA to integrated HBV DNA during treatment*. 2025

> 下一章 → [Ch 9 · 乙肝 vs 丙肝 vs HIV](./09-HBV-vs-HCV-vs-HIV.md)
