# External Frameworks & References

**Curated collection of industry-leading frameworks for AI, cloud architecture, and engineering excellence.**

> We don't reinvent the wheel. This playbook builds on proven frameworks from industry leaders.

---

## AI Maturity & Assessment Frameworks

### MIT CISR Enterprise AI Maturity Model
**Source**: [MIT Center for Information Systems Research](https://cisr.mit.edu/publication/2024_1201_EnterpriseAIMaturityModel_WeillWoernerSebastian)

**Key Concepts**:
- Four stages: Foundational → Integrated → Optimized → Transformative
- Financial performance improves at each stage
- Based on survey of 721 companies

**How We Use It**: Foundation for our [AI Maturity Assessment](../consulting-toolkit/assessment-tools/ai-maturity-assessment.md)

---

### OWASP AI Maturity Assessment (AIMA)
**Source**: [OWASP Project](https://github.com/OWASP/www-project-ai-maturity-assessment)

**Key Concepts**:
- Security and responsible AI focus
- Based on OWASP SAMM methodology
- Eight practices across AI lifecycle

**How We Use It**: Governance and security dimensions of our assessments

---

### Gartner AI Maturity Model
**Source**: Gartner Research (subscription required)

**Key Concepts**:
- Five levels: Awareness → Active → Operational → Systemic → Transformational
- Focus on value realization and organizational change
- Industry benchmarking

**How We Use It**: Client positioning and industry comparisons

---

### MITRE AI Maturity Model
**Source**: [MITRE AI Resources](https://www.mitre.org/)

**Key Concepts**:
- Six pillars: Ethical Use, Strategy, Organization, Technology Enablers, Data, Performance Measurement
- Structured questionnaires for each pillar
- Five maturity levels per pillar

**How We Use It**: Detailed dimension assessments

---

## Cloud Architecture Frameworks

### AWS Well-Architected Framework
**Source**: [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/)

**Pillars**:
1. Operational Excellence
2. Security
3. Reliability
4. Performance Efficiency
5. Cost Optimization
6. Sustainability (added 2021)

**How We Use It**: Platform-agnostic adaptation in our [Well-Architected Review](../consulting-toolkit/assessment-tools/well-architected-review.md)

---

### Azure Well-Architected Framework
**Source**: [Microsoft Learn](https://learn.microsoft.com/azure/well-architected/)

**Pillars**:
1. Reliability
2. Security
3. Cost Optimization
4. Operational Excellence
5. Performance Efficiency

**How We Use It**: Azure-specific implementations in our [Azure CoE](https://github.com/maree217/azure-enterprise-solutions-architecture)

---

### Google Cloud Architecture Framework
**Source**: [Google Cloud](https://cloud.google.com/architecture/framework)

**Pillars**:
1. System Design
2. Operational Excellence
3. Security, Privacy, and Compliance
4. Reliability
5. Cost Optimization
6. Performance Optimization

**How We Use It**: GCP-specific guidance and comparisons

---

## Enterprise Architecture Frameworks

### TOGAF (The Open Group Architecture Framework)
**Source**: [The Open Group](https://www.opengroup.org/togaf)

**Key Concepts**:
- Architecture Development Method (ADM)
- Enterprise Continuum
- Architecture Repository

**How We Use It**: Enterprise-wide architecture governance

---

### Zachman Framework
**Source**: [Zachman International](https://www.zachman.com/)

**Key Concepts**:
- 6x6 matrix of perspectives and abstractions
- What, How, Where, Who, When, Why

**How We Use It**: Stakeholder communication and documentation structure

---

## DevOps & Engineering Frameworks

### CNCF Cloud Native Landscape
**Source**: [CNCF Landscape](https://landscape.cncf.io/)

**Key Concepts**:
- Comprehensive map of cloud-native technologies
- Graduated, incubating, and sandbox projects
- Community-driven standards

**How We Use It**: Technology selection and comparison

---

### ThoughtWorks Technology Radar
**Source**: [ThoughtWorks Radar](https://www.thoughtworks.com/radar)

**Key Concepts**:
- Four rings: Adopt, Trial, Assess, Hold
- Four quadrants: Techniques, Platforms, Tools, Languages & Frameworks
- Updated biannually

**How We Use It**: Technology recommendations in our [decision frameworks](../decision-frameworks/)

---

### Google SRE (Site Reliability Engineering)
**Source**: [SRE Books](https://sre.google/books/)

**Key Concepts**:
- Error budgets
- Service Level Objectives (SLOs)
- Toil elimination
- Blameless postmortems

**How We Use It**: Operational excellence and reliability engineering

---

### Team Topologies
**Source**: [teamtopologies.com](https://teamtopologies.com/)

**Key Concepts**:
- Four team types: Stream-aligned, Platform, Enabling, Complicated Subsystem
- Three interaction modes: Collaboration, X-as-a-Service, Facilitating
- Cognitive load management

**How We Use It**: Organization design and team structure recommendations

---

## Data & AI Engineering

### Data Mesh Principles
**Source**: [Zhamak Dehghani](https://martinfowler.com/articles/data-mesh-principles.html)

**Key Concepts**:
- Domain-oriented ownership
- Data as a product
- Self-serve data platform
- Federated computational governance

**How We Use It**: Data architecture patterns in [principles](../principles/data-engineering/)

---

### MLOps Maturity Model
**Source**: [Microsoft MLOps](https://learn.microsoft.com/azure/architecture/example-scenario/mlops/mlops-maturity-model)

**Key Concepts**:
- Five levels from no MLOps to full automation
- Focus on reproducibility, traceability, and governance

**How We Use It**: AI infrastructure assessments

---

### Medallion Architecture
**Source**: [Databricks](https://www.databricks.com/glossary/medallion-architecture)

**Key Concepts**:
- Bronze (raw) → Silver (cleaned) → Gold (curated)
- Incremental data quality improvement
- Lakehouse pattern foundation

**How We Use It**: Data platform design recommendations

---

## Security Frameworks

### NIST Cybersecurity Framework
**Source**: [NIST CSF](https://www.nist.gov/cyberframework)

**Key Concepts**:
- Five functions: Identify, Protect, Detect, Respond, Recover
- Implementation tiers
- Framework profiles

**How We Use It**: Security assessments and governance

---

### OWASP Top 10
**Source**: [OWASP Top 10](https://owasp.org/www-project-top-ten/)

**Key Concepts**:
- Top 10 web application security risks
- Updated every 3-4 years
- Includes remediation guidance

**How We Use It**: Security reviews and developer training

---

### Zero Trust Architecture
**Source**: [NIST SP 800-207](https://csrc.nist.gov/publications/detail/sp/800-207/final)

**Key Concepts**:
- Never trust, always verify
- Assume breach
- Least privilege access

**How We Use It**: Security architecture patterns in [principles](../principles/security-by-design/)

---

## How to Choose Frameworks

### For Client Engagements

| Client Need | Recommended Framework |
|-------------|----------------------|
| AI strategy and roadmap | MIT CISR + Our AI Maturity Assessment |
| Cloud migration | AWS/Azure/GCP Well-Architected + Cloud Readiness |
| AI security and governance | OWASP AIMA + NIST AI RMF |
| Enterprise architecture | TOGAF + Zachman |
| DevOps transformation | CNCF + SRE + Team Topologies |
| Data platform modernization | Data Mesh + Medallion Architecture |

### Framework Combination Strategy

Most engagements use 2-3 frameworks:
1. **Primary**: Domain-specific (e.g., MIT CISR for AI, TOGAF for EA)
2. **Secondary**: Platform-specific (e.g., Azure Well-Architected)
3. **Tertiary**: Industry validation (e.g., ThoughtWorks Radar)

---

## Stay Updated

### Newsletters & Publications
- [ThoughtWorks Insights](https://www.thoughtworks.com/insights)
- [Martin Fowler's Blog](https://martinfowler.com/)
- [CNCF Newsletter](https://www.cncf.io/newsletter/)
- [MIT CISR Research](https://cisr.mit.edu/)

### Conferences
- KubeCon + CloudNativeCon
- AWS re:Invent
- Microsoft Ignite
- Google Cloud Next

### Certifications
- AWS Solutions Architect
- Azure Solutions Architect Expert
- Google Cloud Professional Cloud Architect
- Kubernetes Administrator (CKA)
- TOGAF Certified

---

**Remember**: Frameworks are tools, not dogma. Adapt them to your client's context and maturity level.
