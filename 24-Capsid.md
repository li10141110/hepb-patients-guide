# Ch 24 · Capsid Assembly Modulator

> 让病毒的"外壳"装错。

---

## 一分钟原理

回忆第 2 章生命周期第⑥步——**装配**:核心蛋白(HBcAg)包裹 pgRNA 和聚合酶,形成新核衣壳。

Capsid Assembly Modulator(CAM)就打这一步。

**两大家族,打法不同:**

**A. CAM-I(异型装配,Heterologous)**
- 干扰核心蛋白之间的正确对接
- 结果:装配出**畸形的、非功能性的外壳**
- 无法包住 pgRNA,复制中断
- 代表:Bersacapavir(JNJ)、ABI-H3733

**B. CAM-E(空壳装配,Empty)**
- 让核心蛋白装得更快,但**是空的**
- 装配的外壳里**没有 pgRNA**
- 复制中断 + 减少 cccDNA 补货
- 代表:**ALG-000184**(新一代,见下文)

不管是哪种,结果都是——**新病毒装不出来,cccDNA 池的补货被切断**。

---

## 为什么有用

CAM 的独特价值:

- **切断补货** — 阻止新 rcDNA 回流,cccDNA 池逐渐缩减
- **兼容现有 NUC** — 不冲突,能联合
- **不依赖免疫** — 直接作用于病毒机器
- **口服** — 患者依从性好

**缺点:**

- **不清除现存 cccDNA** — 治标不治本
- **不降 HBsAg** — 因为整合 DNA 还在造
- **单药效果有限** — 必须联合

**所以 CAM 定位是——"补货切断者",在联合方案里是重要一环。**

---

## 主要候选药

### CAM-I 家族(异型装配)

**ABI-H3733**(Assembly Biosciences → now Gilead)
- 二代 CAM-I
- II 期进行中
- 强效核衣壳畸形化
- ABI-H2158(前身)—— 因肝毒性 II 期终止,现换为 H3733

**JNJ-56136379 / Bersacapavir**(Janssen)
- 曾是最有希望的 CAM-I
- **2022 年终止开发**(详见下文)

**RG7907 / RG7834**(Roche)
- II 期,部分数据显示合成致死效应

### CAM-E 家族(空壳装配)⭐

**ALG-000184**(Aligos Therapeutics)
- **新一代 CAM-E**,高活性化合物 ALG-001075 的口服前药
- **II 期临床进行中**——其中一项试验在**多伦多 UHN 大学健康网络**开展
- ⭐ **双重机制**,同时打两个环节:

  **机制①:装配"空壳"(主战场)**
  - 诱导核心蛋白异常聚合,组装出**没有包裹遗传物质的空衣壳**
  - 彻底阻断 pgRNA 包装和后续逆转录
  - 结果:HBV DNA 和 HBV RNA 出现**多对数级下降**

  **机制②:阻断新 cccDNA 生成(辅助战场)**
  - 高浓度下,阻止成熟核衣壳把遗传物质送进细胞核
  - 切断**de novo cccDNA** 的建立,也减少现有 cccDNA 池的自我补充
  - 结果:HBsAg、HBeAg、HBcrAg 产生受显著抑制

- 相比 CAM-I 的优势:同时压"新病毒装配" + "cccDNA 补货"两条线,降维打击
- 缺点和 CAM-I 类似:单药不足以治愈,必须联合

**为什么 ALG-000184 值得持续关注:**
- UHN II 期数据读出后,将是 CAM-E 家族最重要的临床验证
- 若数据积极,CAM-E 可能在下一代联合方案里取代失败的 CAM-I

**其他若干候选,细节待用 ClinicalTrials.gov 最新核对。**

---

## 效果:CAM 家族的"天花板"被 ALG-000184 打破了吗?

### 传统认知(Bersacapavir 时代)

旧一代 CAM(CAM-I)的典型效果:
- **HBV DNA 快速下降**——比单用 NUC 更深
- **HBV RNA 下降**——反映 cccDNA 转录被间接影响
- **HBsAg 略降或不变**——因为整合 DNA 还在造
- **HBcrAg 明显下降**

传统结论:**CAM 主要打"深度病毒学抑制",不是"治愈终点"。联合 siRNA/ASO 才能兼顾 HBsAg 下降。**

### 新数据:ALG-000184 Phase 1 的 96 周结果 ⭐

ALG-000184-201 试验公布的 96 周单药数据,让 CAM 家族的潜力被重新评估:

**病毒学压制(第一重机制验证):**
- HBeAg 阳性(大三阳)患者 300mg 治疗 96 周:**100% 实现 HBV DNA < LLOQ(< 10 IU/mL)**
- HBeAg 阴性(小三阳)患者:**第 20 周 100% HBV DNA < LLOQ,第 96 周全部检测不到**
- HBV RNA 在第 52 周全部降至定量下限以下
- **无病毒学突破**

**抗原下降(第二重机制验证,重点!):**
- **HBcrAg**(最直接的 cccDNA 替代指标):
  - HBeAg 阳性患者 **100% 出现 ≥ 1 log 下降,最大降幅 3.5 log**
  - HBeAg 阴性患者 9/11 也显著下降
  - 这强烈提示 **cccDNA 库确实被有效抑制和削减**
- **HBsAg**:
  - 70% 的 HBeAg 阳性患者 **HBsAg 下降 ≥ 1 log,最大 1.5 log**
  - 这个幅度对单药 CAM 来说是前所未有的

**解读:**
ALG-000184 的数据**部分颠覆了"CAM 不降抗原"的旧结论**。双重机制让它在压 DNA/RNA 的同时,也通过阻断 cccDNA 补货,让 HBcrAg 和 HBsAg 都显著下降。当然,1.5 log 的 HBsAg 降幅还不足以单药实现功能性治愈(通常需 ≥ 2 log + 转阴),但已经足够让 CAM-E 家族成为联合方案的强力候选。

---

## 一个前车之鉴:JNJ-56136379 (Bersacapavir)

Bersacapavir 曾是最有希望的 CAM 候选。**Janssen 在 2022 年终止了它的开发**。

原因:
- III 期数据显示,即使联合 NUC + siRNA + Bersacapavir,停药后 HBsAg 反弹率仍高
- 三药联合方案在**治愈终点上没有显著优势**

**教训:**

- CAM 不能独自实现治愈
- **必须**搭配免疫调节
- 联合设计要仔细选择组合和顺序

**这次失败让整个领域重新审视 CAM 的定位——它是"必要不充分"条件。**

---

## CAM-I vs CAM-E 的深入观察

基于最新数据,学界对两大家族的认知正在更新:

- **CAM-E(空壳)** — ALG-000184 用 96 周数据证明:不仅能压 DNA/RNA,还能显著降 HBcrAg 和 HBsAg。双重机制(空壳装配 + 阻断 cccDNA 核输入)是关键。
- **CAM-I(异型)** — 对已存在的核衣壳破坏更彻底,但 Bersacapavir 的失败让这一派需要新的临床证据

**ABI-H3733**(CAM-I)试图突破 Bersacapavir 的困境;**ALG-000184**(CAM-E)则在 UHN 的 II 期试验中接受更大样本验证。两条路线谁跑赢,还有待 II/III 期头对头数据。

---

## 副作用与安全性

CAM 类药物的常见副作用:
- **消化道不适**——恶心、腹泻
- **ALT 升高**——需要监测
- **皮疹**——某些结构的药物较常见
- **肝毒性**——曾导致部分候选药(如 ABI-H2158)停止开发

### ALG-000184 的安全性数据(96 周)

- **无药物相关严重不良事件(SAE)**
- **无患者因毒性停药**
- 部分患者出现 3 级及以上 ALT/AST 升高,但**继续服药后自行缓解**
- 独立安全审查委员会(ALT Flare Committee)评估:**这些 ALT 波动是免疫觉醒的信号,不是药物毒性**
- 肝脏合成与排泄功能未受影响

**这一安全性数据在 CAM 家族里是最长的单药随访记录之一。**

---

## 什么样的联合方案最合理

综合目前证据:

**CAM 最适合的位置**:
- **在 NUC + siRNA 的基础上加**
- 用于**深度抑制病毒**(pgRNA、HBV RNA 下降)
- 联合免疫调节(疫苗或 PD-1)
- 疗程 24-48 周

**期待的效果**:
- HBV DNA 快速深度抑制
- HBV RNA 下降到检测不到
- cccDNA 池缓慢缩减
- 为免疫接管创造窗口

---

## 未来展望

CAM 领域正在经历一次**重新定位**:

- **不再期望它单独实现治愈**
- 定位为"病毒学深压制"的关键一环
- 联合疗法中的"补货切断者"角色

**5-10 年内预期:**

- 至少一款 CAM 获批(作为联合方案组件)
- 更多 Class I CAM 进入临床
- 与 siRNA / 免疫的组合数据更成熟

---

## 📍 本章要点

- CAM 干扰**核衣壳装配**,切断 cccDNA 补货
- 两大家族:**CAM-I**(异型装配) vs **CAM-E**(空壳装配)
- ⭐ **ALG-000184 Phase 1 的 96 周数据**:100% HBV DNA 压制,HBcrAg 最大降 3.5 log,HBsAg 70% 患者降 ≥ 1 log——打破"CAM 不降抗原"的旧结论
- 安全性良好:无 SAE,无停药,ALT 波动被认为是免疫觉醒
- Bersacapavir(JNJ)III 期止步——CAM 单靠自己不够,但 CAM-E 带来了新希望
- ⭐ **ALG-000184**(CAM-E)正在 II 期,UHN 多伦多参与,双重机制是核心竞争力
- 定位:**联合疗法中的"补货切断者" + 抗原下降贡献者**
- 现有候选:ALG-000184(数据最亮眼)、ABI-H3733、Bersacapavir(已停)

---

**延伸阅读**
- Yuen MF. et al. *Capsid inhibitors in HBV*. J Hepatol. 2022
- Zoulim F. et al. *HBV cure strategies: capsid modulators*. 2023
- Aligos Therapeutics. *ALG-000184 Phase 1 (ALG-000184-201) 96-week data*. 2025/2026
- Aligos Therapeutics. *ALG-000184 Phase 2 trial (UHN Toronto)*. ClinicalTrials.gov
- Lambert E. et al. *CAM-E mechanism: empty capsid assembly in HBV*. Antiviral Res. 2023

> 下一章 → [Ch 25 · Entry Inhibitor](./25-Entry.md)
