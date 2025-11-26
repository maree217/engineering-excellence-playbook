# Contributing to Engineering Excellence Playbook

Thank you for your interest in contributing! This playbook is a community effort to help organizations build better systems without vendor lock-in.

---

## How to Contribute

### 1. **Add Architecture Patterns**
Share platform-agnostic patterns in `/principles/`:
- Document the problem it solves
- Explain when to use (and when not to use)
- Provide examples across multiple platforms
- Include diagrams (Mermaid, draw.io, or images)

### 2. **Submit Case Studies**
Real-world examples help others learn. Include in `/case-studies/`:
- Business context and challenges
- Architecture decisions and trade-offs
- Implementation details (with code/IaC samples)
- Measurable outcomes (cost savings, performance improvements, ROI)

### 3. **Create Platform-Specific Guides**
Help fill in `/implementation-guides/aws/` or `/implementation-guides/gcp/`:
- Follow the structure in `/implementation-guides/azure/`
- Include Terraform/IaC examples
- Add cost considerations
- Link to official documentation

### 4. **Improve Decision Frameworks**
Enhance `/decision-frameworks/`:
- Update comparison tables with latest services/pricing
- Add new decision matrices (e.g., database selection, AI model selection)
- Share real-world decision-making examples

### 5. **Curate Learning Resources**
Add valuable external resources to `/learning-resources/`:
- Certification paths
- Books, whitepapers, videos
- Conference talks
- Blog posts from practitioners

---

## Contribution Guidelines

### Writing Style
- **Clear and Concise**: Avoid jargon. Explain acronyms on first use.
- **Objective**: Present trade-offs, not opinions. Support claims with data.
- **Practical**: Include code examples, diagrams, and real-world scenarios.
- **Platform-Agnostic** (in `/principles/`): Focus on universal concepts, not specific cloud services.

### Code Standards
- **Infrastructure as Code**: Use Terraform for multi-cloud, native IaC (Bicep/CloudFormation) for single-cloud.
- **Follow Best Practices**: Apply principles from this repo (security by design, observability, etc.).
- **Include Tests**: For code samples, include validation/testing examples.
- **Document Dependencies**: List required tools, versions, and prerequisites.

### Documentation Standards
- **Use Markdown**: GitHub-flavored Markdown for all documentation.
- **Add Diagrams**: Use Mermaid for simple diagrams, PNG/SVG for complex architectures.
- **Link Liberally**: Reference other sections of the repo and external authoritative sources.
- **Keep It Updated**: Include "Last Updated" dates for content that changes frequently.

---

## Pull Request Process

### 1. Fork and Clone
```bash
git clone https://github.com/maree217/engineering-excellence-playbook.git
cd engineering-excellence-playbook
git checkout -b feature/your-contribution
```

### 2. Make Your Changes
- Follow the directory structure
- Update relevant README.md files
- Add your content with clear commit messages

### 3. Test Locally
- Verify all links work
- Check Markdown rendering
- Test any code samples

### 4. Submit Pull Request
- Provide a clear description of your changes
- Reference any related issues
- Tag with appropriate labels (documentation, aws, azure, gcp, patterns, etc.)

### 5. Review Process
- Maintainers will review within 1 week
- Address feedback and requested changes
- Once approved, your contribution will be merged!

---

## Issue Guidelines

### Reporting Bugs or Errors
Use the **Bug Report** template:
- Broken links
- Outdated information
- Errors in code samples
- Incorrect platform comparisons

### Suggesting Enhancements
Use the **Feature Request** template:
- New architecture patterns
- Additional platform guides
- Improved decision frameworks
- New assessment templates

### Asking Questions
Use **GitHub Discussions** for:
- Clarifying concepts
- Getting advice on platform selection
- Discussing trade-offs
- Sharing experiences

---

## Content Areas We Need Help With

### High Priority
- [ ] AWS implementation guides
- [ ] GCP implementation guides
- [ ] Multi-cloud case studies
- [ ] Cost comparison calculators
- [ ] Assessment scorecard templates

### Medium Priority
- [ ] Additional architecture patterns (SAGA, BFF, Strangler Fig)
- [ ] Industry-specific compliance guides (GDPR, HIPAA, PCI-DSS)
- [ ] DevOps CI/CD pipeline examples
- [ ] Kubernetes multi-cloud patterns
- [ ] Video tutorials and workshops

### Ongoing
- [ ] Keeping platform comparisons up to date
- [ ] Updating pricing information
- [ ] Adding new case studies
- [ ] Curating learning resources

---

## Code of Conduct

### Our Pledge
We are committed to making participation in this project a harassment-free experience for everyone.

### Our Standards
- **Be Respectful**: Value diverse perspectives and experiences
- **Be Collaborative**: Help others learn and grow
- **Be Professional**: Focus on what's best for the community
- **Be Honest**: Admit mistakes, correct them, and learn

### Unacceptable Behavior
- Harassment, trolling, or personal attacks
- Publishing others' private information
- Promoting specific vendors for personal gain
- Plagiarizing content without attribution

### Enforcement
Violations will result in:
1. Warning
2. Temporary ban from contributing
3. Permanent ban for repeated violations

Report issues to: [maintainers contact - add your email]

---

## Attribution

### Contributors
All contributors will be acknowledged in:
- GitHub Contributors page
- Annual acknowledgments in README.md
- Individual commit history

### Licensing
By contributing, you agree that your contributions will be licensed under the **MIT License**.

---

## Recognition

### Contributor Levels

| Level | Criteria | Badge |
|-------|----------|-------|
| **Contributor** | 1+ merged PR | ![Contributor](https://img.shields.io/badge/Contributor-blue) |
| **Regular Contributor** | 5+ merged PRs | ![Regular](https://img.shields.io/badge/Regular-green) |
| **Core Contributor** | 20+ merged PRs + ongoing engagement | ![Core](https://img.shields.io/badge/Core-gold) |
| **Maintainer** | Invited by project lead | ![Maintainer](https://img.shields.io/badge/Maintainer-red) |

---

## Getting Started Checklist

Before your first contribution:
- [ ] Read this CONTRIBUTING.md
- [ ] Browse existing content to understand the style
- [ ] Check open issues for "good first issue" labels
- [ ] Join GitHub Discussions to introduce yourself
- [ ] Fork the repository
- [ ] Make a small contribution (fix a typo, improve formatting)
- [ ] Submit your first PR!

---

## Questions?

- 📧 Open an issue with the "question" label
- 💬 Start a discussion in [GitHub Discussions](https://github.com/maree217/engineering-excellence-playbook/discussions)
- 📖 Review existing documentation in `/docs/`

---

**Thank you for helping make engineering excellence accessible to everyone!**
