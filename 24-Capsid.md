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
- **HBsAg 下降有限** — 28 天数据仅 0.2-0.8 log,单药不足以治愈
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

## 效果:ALG-000184 能不能降 HBsAg?

### 已发表的硬数据(PMID 41554267, Lancet Gastroenterology & Hepatology, 2026)

这是 Phase 1 试验(NCT04536337)的 28 天单药结果,**同行评审已发表**:

**试验设计:**
- 59 名慢性乙肝患者,5 个剂量组(10/50/100/300 mg vs 安慰剂)
- 7 个中心(香港、中国、摩尔多瓦、新西兰、英国)
- 中位年龄 37 岁,68% 亚洲人

**HBV DNA 压制:**
- 所有剂量(10-300mg)均出现 **3-4 log₁₀ 下降**
- HBeAg 阴性 23 人中:**83% 实现 HBV DNA < LLOQ(< 10 IU/mL)**
- 100% 实现 HBV RNA < LLOQ

**HBsAg 下降(关键问题!):**
- 仅在 HBeAg 阳性患者中观察到 HBsAg 下降
- 100mg 组:1 人降 0.5 log₁₀ IU/mL
- 300mg 组:**4/8 人降 0.2-0.8 log₁₀ IU/mL**
- HBeAg 阴性患者:未见显著 HBsAg 下降
- **HBcrAg:该研究未报告**

**安全性:**
- 耐受性良好,无严重药物相关不良事件
- ALT 升高 31%(药物) vs 18%(安慰剂)
- AST 升高 25%(药物) vs 9%(安慰剂)
- 无停药、无死亡

### ⚠️ 关于"96 周数据"

你可能在网上看到过声称 ALG-000184 300mg 单药 96 周后 HBcrAg 降 3.5 log、HBsAg 70% 患者降 ≥ 1 log 的说法。这些数据**目前尚未在同行评审期刊发表**。Aligos 可能在会议口头报告或 press release 中提到过,但具体数字和患者分层需要等待正式发表。

**已证实的 vs 待验证的:**

| 指标 | 已发表(28 天) | 待发表(96 周声称) |
|------|-------------|-----------------|
| HBV DNA | ✅ 3-4 log 下降 | 100% < LLOQ |
| HBV RNA | ✅ 100% < LLOQ | 第 52 周全部未检出 |
| HBsAg | ✅ 0.2-0.8 log(部分患者) | 70% ≥ 1 log,最大 1.5 log |
| HBcrAg | ❌ 未报告 | 100% ≥ 1 log,最大 3.5 log |

### 底线:ALG-000184 能不能降 HBsAg?

**能,但幅度有限。**

已发表的 28 天数据显示:HBsAg 在部分 HBeAg 阳性患者中下降了 0.2-0.8 log。这个幅度:
- ✅ 证明 CAM-E **不是完全不降 HBsAg**(旧认知被部分推翻)
- ❌ 但离"功能性治愈"还差很远(通常需 HBsAg < 100 IU/mL 或转阴)
- 🔑 关键看联合 siRNA/ASO 后能否叠加

### B-SUPREME Phase 2 会告诉我们什么

目前进行中的 **B-SUPREME 试验(NCT06963710)** 是关键:
- **200 名患者,48 周 ALG-000184 单药 vs TDF**
- 2025 年 7 月启动,预计 2027 年 3 月读出
- 全球 50+ 中心,包括**多伦多、温哥华、Edmonton**
- 主要终点:HBV DNA < LLOQ(10 IU/mL)

48 周数据出来后,我们就能知道:**长期用药是否能让 HBsAg/HBcrAg 进一步下降**。

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

### ALG-000184 的安全性数据(28 天,已发表)

- **无药物相关严重不良事件(SAE)**
- **无患者因毒性停药**
- ALT 升高:31%(药物) vs 18%(安慰剂),多为轻度
- AST 升高:25%(药物) vs 9%(安慰剂)
- 高尿酸血症:10%(药物) vs 18%(安慰剂)

耐受性良好。96 周延长治疗的安全数据尚未发表。

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
- ⭐ **ALG-000184**(pevifoscorvir sodium)是唯一进入 Phase 2 的 CAM-E
- **已发表数据(28 天,PMID 41554267)**:HBV DNA 降 3-4 log,部分 HBeAg 阳性患者 HBsAg 降 0.2-0.8 log
- **96 周长期数据(声称 HBsAg 降 1.5 log,HBcrAg 降 3.5 log)尚未同行评审发表**,需等待
- **B-SUPREME Phase 2(NCT06963710)**:200 人,48 周单药 vs TDF,2027 年读出,全球 50+ 中心含多伦多/温哥华
- Bersacapavir(JNJ)III 期止步——CAM 单靠自己不够
- 定位:**联合疗法中的"补货切断者"**——HBsAg 下降有限,需联合 siRNA/ASO

---

**延伸阅读**
- Aligos Therapeutics. *ALG-000184 (pevifoscorvir sodium) monotherapy in participants with chronic HBV infection: a phase 1, multicentre, randomised, dose-escalation study.* Lancet Gastroenterol Hepatol. 2026. PMID: 41554267
- Aligos Therapeutics. *The Discovery and Preclinical Profile of ALG-000184.* PMID: 39575679
- B-SUPREME Phase 2: ClinicalTrials.gov NCT06963710 (200 patients, 48 wk, vs TDF, global)
- Phase 1 SAD/MAD: ClinicalTrials.gov NCT04536337 (completed, 165 patients)
- Yuen MF. et al. *Capsid inhibitors in HBV.* J Hepatol. 2022
- Lambert E. et al. *CAM-E mechanism: empty capsid assembly in HBV.* Antiviral Res. 2023

> 下一章 → [Ch 25 · Entry Inhibitor](./25-Entry.md)
