# AI Maturity Assessment Framework

**A structured approach to evaluating organizational AI readiness and capabilities.**

> Based on MIT CISR Enterprise AI Maturity Model, OWASP AIMA, and practical consulting experience.

---

## Overview

This assessment framework helps organizations understand:
1. **Where they are** on the AI maturity spectrum
2. **What gaps exist** across critical dimensions
3. **How to prioritize** investments for maximum ROI
4. **What capabilities** to build at each stage

---

## The Five-Stage AI Maturity Model

```
Stage 1          Stage 2          Stage 3          Stage 4          Stage 5
AI Aware         AI Active        AI Operational   AI Systematic    AI Transformational
────────         ─────────        ──────────────   ─────────────    ───────────────────
Exploring        Piloting         Scaling          Optimizing       Innovating

• Awareness      • First pilots   • Production AI  • AI embedded    • AI-first business
• Education      • Skill building • Defined ops    • Self-service   • New business models
• Experimentation• POCs/MVPs      • Governance     • Automation     • Industry disruption
```

---

## Assessment Dimensions

### 1. Strategy & Leadership (Weight: 20%)

| Maturity Level | Characteristics | Score |
|----------------|-----------------|-------|
| **1 - Ad Hoc** | No AI strategy; exploration happens in silos | 1 |
| **2 - Developing** | Informal AI interest; no executive sponsorship | 2 |
| **3 - Defined** | Documented AI strategy; executive sponsor identified | 3 |
| **4 - Managed** | AI strategy aligned to business objectives; dedicated budget | 4 |
| **5 - Optimized** | AI embedded in corporate strategy; board-level oversight | 5 |

**Assessment Questions:**
- [ ] Is there a documented AI/ML strategy?
- [ ] Is there executive sponsorship for AI initiatives?
- [ ] Is AI investment aligned with business priorities?
- [ ] Are AI outcomes measured and reported to leadership?
- [ ] Is there a multi-year AI roadmap?

---

### 2. Data Foundation (Weight: 25%)

| Maturity Level | Characteristics | Score |
|----------------|-----------------|-------|
| **1 - Ad Hoc** | Data in silos; no data catalog; poor quality | 1 |
| **2 - Developing** | Some data integration; manual quality checks | 2 |
| **3 - Defined** | Data lake/warehouse established; data catalog exists | 3 |
| **4 - Managed** | Automated data quality; data lineage tracked; governed | 4 |
| **5 - Optimized** | Real-time data pipelines; self-service analytics; data mesh | 5 |

**Assessment Questions:**
- [ ] Is there a centralized data platform (lake/warehouse)?
- [ ] Is data quality monitored and measured?
- [ ] Is there a data catalog with discoverability?
- [ ] Are data governance policies enforced?
- [ ] Can business users access data without IT tickets?

---

### 3. Technology & Infrastructure (Weight: 20%)

| Maturity Level | Characteristics | Score |
|----------------|-----------------|-------|
| **1 - Ad Hoc** | Local laptops; no cloud; manual deployments | 1 |
| **2 - Developing** | Basic cloud usage; some containerization | 2 |
| **3 - Defined** | Cloud-native infrastructure; CI/CD pipelines | 3 |
| **4 - Managed** | MLOps platform; automated training/deployment | 4 |
| **5 - Optimized** | Full MLOps; feature stores; model monitoring; auto-scaling | 5 |

**Assessment Questions:**
- [ ] Is there cloud infrastructure for AI workloads?
- [ ] Are ML models deployed via automated pipelines?
- [ ] Is there a feature store for ML features?
- [ ] Are models monitored for drift and performance?
- [ ] Can models be retrained automatically?

---

### 4. Skills & Organization (Weight: 20%)

| Maturity Level | Characteristics | Score |
|----------------|-----------------|-------|
| **1 - Ad Hoc** | No AI skills; reliance on vendors | 1 |
| **2 - Developing** | A few data scientists; limited ML engineering | 2 |
| **3 - Defined** | AI/ML team established; defined roles | 3 |
| **4 - Managed** | Cross-functional AI teams; embedded in business | 4 |
| **5 - Optimized** | AI Center of Excellence; citizen data scientists; AI literacy org-wide | 5 |

**Assessment Questions:**
- [ ] Are there dedicated AI/ML practitioners?
- [ ] Is there a defined AI team structure?
- [ ] Are AI skills being developed across the organization?
- [ ] Are there AI champions in each business unit?
- [ ] Is there a formal AI training program?

---

### 5. Governance & Ethics (Weight: 15%)

| Maturity Level | Characteristics | Score |
|----------------|-----------------|-------|
| **1 - Ad Hoc** | No AI governance; no awareness of AI ethics | 1 |
| **2 - Developing** | Basic awareness; ad-hoc reviews | 2 |
| **3 - Defined** | AI governance framework documented; ethics guidelines | 3 |
| **4 - Managed** | AI ethics board; automated bias detection; audit trails | 4 |
| **5 - Optimized** | Continuous compliance; responsible AI embedded in culture | 5 |

**Assessment Questions:**
- [ ] Is there an AI governance framework?
- [ ] Are AI models reviewed for bias and fairness?
- [ ] Are AI decisions explainable to stakeholders?
- [ ] Is there regulatory compliance (GDPR, industry-specific)?
- [ ] Is there an AI ethics review process?

---

## Scoring Guide

### Calculate Your Score

```
Dimension                    Weight    Your Score    Weighted Score
─────────────────────────    ──────    ──────────    ──────────────
Strategy & Leadership        20%       ___/5         ___ × 0.20 = ___
Data Foundation              25%       ___/5         ___ × 0.25 = ___
Technology & Infrastructure  20%       ___/5         ___ × 0.20 = ___
Skills & Organization        20%       ___/5         ___ × 0.20 = ___
Governance & Ethics          15%       ___/5         ___ × 0.15 = ___
─────────────────────────────────────────────────────────────────────
TOTAL WEIGHTED SCORE                                 ___/5.00
```

### Interpretation

| Score Range | Maturity Stage | Recommended Focus |
|-------------|----------------|-------------------|
| **1.0 - 1.4** | Stage 1: AI Aware | Education, strategy development, data foundation |
| **1.5 - 2.4** | Stage 2: AI Active | Pilot projects, skill building, governance basics |
| **2.5 - 3.4** | Stage 3: AI Operational | Scale successful pilots, MLOps, organization design |
| **3.5 - 4.4** | Stage 4: AI Systematic | Optimization, self-service, advanced governance |
| **4.5 - 5.0** | Stage 5: AI Transformational | Innovation, new business models, industry leadership |

---

## Gap Analysis Template

### Identify Priority Gaps

| Dimension | Current Score | Target Score (12mo) | Gap | Priority |
|-----------|---------------|---------------------|-----|----------|
| Strategy & Leadership | ___ | ___ | ___ | High/Med/Low |
| Data Foundation | ___ | ___ | ___ | High/Med/Low |
| Technology & Infrastructure | ___ | ___ | ___ | High/Med/Low |
| Skills & Organization | ___ | ___ | ___ | High/Med/Low |
| Governance & Ethics | ___ | ___ | ___ | High/Med/Low |

### Prioritization Framework

**High Priority if:**
- Score is 2+ levels below target
- Blocking other improvements
- Regulatory or compliance risk

**Medium Priority if:**
- Score is 1 level below target
- Enabling but not blocking

**Low Priority if:**
- Score meets or exceeds target
- Nice-to-have improvements

---

## Roadmap Development

### Stage 1 → Stage 2 (Typical: 6-12 months)

**Key Actions:**
1. Develop AI strategy document with executive sponsorship
2. Establish basic data platform (cloud data lake/warehouse)
3. Hire or contract first AI/ML practitioners
4. Launch 2-3 pilot projects with clear success criteria
5. Create AI governance awareness and basic guidelines

**Investment**: £100K-300K
**Expected ROI**: Pilot validation, organizational learning

---

### Stage 2 → Stage 3 (Typical: 12-18 months)

**Key Actions:**
1. Scale successful pilots to production
2. Implement MLOps pipeline (automated training/deployment)
3. Establish AI/ML team with defined roles
4. Implement data quality monitoring and governance
5. Create formal AI governance framework

**Investment**: £300K-600K
**Expected ROI**: 2-4x on pilot investments

---

### Stage 3 → Stage 4 (Typical: 18-24 months)

**Key Actions:**
1. Embed AI teams in business units
2. Implement self-service analytics and AI tools
3. Automate model monitoring and retraining
4. Establish AI ethics board and bias detection
5. Develop citizen data scientist program

**Investment**: £500K-1M
**Expected ROI**: 5-10x, operational efficiency gains

---

### Stage 4 → Stage 5 (Typical: 24-36 months)

**Key Actions:**
1. AI-driven innovation programs
2. New AI-enabled products and services
3. Industry-leading governance and responsible AI
4. AI literacy across entire organization
5. Continuous model improvement automation

**Investment**: £1M+
**Expected ROI**: Business model transformation, market leadership

---

## External Framework References

### MIT CISR Enterprise AI Maturity Model
- **Source**: [MIT CISR](https://cisr.mit.edu/publication/2024_1201_EnterpriseAIMaturityModel_WeillWoernerSebastian)
- **Key Insight**: Four stages (Foundational → Integrated → Optimized → Transformative) with financial performance improving at each stage

### OWASP AI Maturity Assessment (AIMA)
- **Source**: [OWASP AIMA](https://github.com/OWASP/www-project-ai-maturity-assessment)
- **Key Insight**: Security and responsible AI focus; complements operational maturity with risk management

### Gartner AI Maturity Model
- **Key Insight**: Five levels (Awareness → Active → Operational → Systemic → Transformational) with focus on value realization

### MITRE AI Maturity Model
- **Key Insight**: Six pillars (Ethical Use, Strategy, Organization, Technology Enablers, Data, Performance Measurement)

---

## Workshop Agenda Template

### AI Maturity Assessment Workshop (4 hours)

| Time | Activity | Participants |
|------|----------|--------------|
| 0:00-0:30 | Introduction & Objectives | All |
| 0:30-1:30 | Dimension Assessment (Strategy, Data) | Cross-functional |
| 1:30-1:45 | Break | - |
| 1:45-2:45 | Dimension Assessment (Tech, Skills, Governance) | Cross-functional |
| 2:45-3:15 | Scoring & Gap Analysis | Facilitator + Leads |
| 3:15-3:45 | Prioritization & Quick Wins | All |
| 3:45-4:00 | Next Steps & Action Items | All |

**Pre-work Required:**
- Complete self-assessment questionnaire
- Gather data platform documentation
- List current AI/ML initiatives

---

## Deliverables

After completing this assessment, you will have:

1. **AI Maturity Scorecard** - Quantified current state across 5 dimensions
2. **Gap Analysis** - Prioritized list of improvement areas
3. **Roadmap** - 12-month action plan with milestones
4. **Business Case** - ROI projections for recommended investments
5. **Quick Wins** - Immediate actions (< 30 days) to build momentum

---

## Related Resources

- [Cloud Readiness Assessment](./cloud-readiness-assessment.md)
- [Technical Debt Audit](./technical-debt-audit.md)
- [Well-Architected Review](./well-architected-review.md)
- [Three-Layer AI Framework](../../principles/three-layer-architecture.md)

---

**Framework Version**: 2.0 | **Last Updated**: November 2025
