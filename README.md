# Awesome AI Compliance [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, frameworks, resources, and guides for AI compliance,
> governance, and regulatory risk management.

Covers: **EU AI Act · NIST AI RMF · ISO/IEC 42001 · GPAI · SOC 2 AI · IEEE standards**

Maintained by [@mmilovanovic87](https://github.com/mmilovanovic87) —
Associate Professor, University of Niš · 50+ papers on AI systems.

---

## Contents

- [Frameworks and Regulations](#frameworks-and-regulations)
- [Self-Assessment Tools](#self-assessment-tools)
- [CI/CD and Compliance-as-Code](#cicd-and-compliance-as-code)
- [Enterprise Platforms](#enterprise-platforms)
- [Libraries and SDKs](#libraries-and-sdks)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Learning Resources](#learning-resources)
- [Newsletters and Communities](#newsletters-and-communities)
- [Conferences and Events](#conferences-and-events)

---

## Frameworks and Regulations

### EU AI Act
- [EU AI Act Full Text](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689) - Official regulation text.
- [EU AI Act Explorer](https://artificialintelligenceact.eu/ai-act-explorer/) - Interactive article browser.
- [EU AI Act Compliance Checker](https://artificialintelligenceact.eu/assessment/eu-ai-act-compliance-checker/) - Official risk classification wizard.
- [High-Risk AI Systems (Annex III)](https://artificialintelligenceact.eu/annex/3/) - Full list of high-risk use cases.
- [GPAI Code of Practice](https://digital-strategy.ec.europa.eu/en/policies/ai-code-practice) - General-purpose AI model obligations.

### NIST AI RMF
- [NIST AI RMF 1.0](https://airc.nist.gov/RMF) - Official Risk Management Framework.
- [NIST AI RMF Playbook]. - Implementation guidance.
- [NIST AI RMF Quick Start Guide] - Condensed onboarding.
- [AI RMF Crosswalk] - Mapping to other frameworks.

### ISO/IEC 42001
- [ISO 42001 Overview](https://www.iso.org/standard/81230.html) - AI Management System standard.
- [ISO 42001 vs EU AI Act Mapping](https://www.enisa.europa.eu/) - Crosswalk between standards.

---

## Self-Assessment Tools

- [GapSight](https://gapsight.vercel.app) - Open-source ML compliance self-assessment.
  Maps ML metrics to EU AI Act, NIST AI RMF, and ISO 42001 gaps.
  Includes GitHub Action for CI/CD compliance checks. Free, no login.
  [![GitHub](https://img.shields.io/github/stars/mmilovanovic87/gapsight?style=flat)](https://github.com/mmilovanovic87/gapsight)
- [VerifyWise](https://github.com/bluewave-labs/verifywise) - Open-source AI governance platform covering EU AI Act, ISO 42001, NIST AI RMF.
- [FRAI](https://frai.cc) - AI compliance checks with git pre-commit hooks.

---

## CI/CD and Compliance-as-Code

- [GapSight GitHub Action](https://github.com/mmilovanovic87/gapsight) - Run EU AI Act / NIST AI RMF / ISO 42001 compliance checks in CI/CD pipelines. Generates compliance artifacts alongside test results.
- [Systima Comply](https://dev.to/systima/open-source-eu-ai-act-compliance-scanning-for-cicd-4ogj) - Open-source EU AI Act scanner with AST-based detection of 37+ ML frameworks.

---

## Enterprise Platforms

- [Vanta](https://vanta.com) - Automated compliance platform, includes EU AI Act coverage. From ~$10K/year.
- [Credo AI](https://credo.ai) - AI governance platform with policy packs and risk scoring.
- [Regulativ.ai](https://regulativ.ai) - Supports 40+ compliance frameworks.
- [Aikido Security](https://aikido.dev) - Developer-first security and compliance, includes AI system checks.
- [Enzai](https://enzai.ai) - Pre-built EU AI Act policy packs and audit workflows.

---

## Libraries and SDKs

- [Fairlearn](https://fairlearn.org) - Python library for assessing and improving fairness in ML models.
- [AI Fairness 360 (IBM)](https://aif360.mybluemix.net) - Toolkit to detect and mitigate bias in ML models.
- [Alibi Detect](https://github.com/SeldonIO/alibi-detect) - Outlier, adversarial, and drift detection.
- [Evidently AI](https://evidentlyai.com) - ML model monitoring and evaluation.
- [Deepchecks](https://deepchecks.com) - Testing and monitoring for ML models.
- [SHAP](https://github.com/slundberg/shap) - Explainability for ML model outputs.
- [LIME](https://github.com/marcotcr/lime) - Local interpretable model-agnostic explanations.

---

## Datasets and Benchmarks

- [AI Incident Database](https://incidentdatabase.ai) - Documented real-world AI failures.
- [NIST ARIA](https://airc.nist.gov/aria) - Assessing Risks and Impacts of AI benchmark.
- [BigBench](https://github.com/google/BIG-bench) - Diverse tasks for LLM evaluation.

---

## Learning Resources

### Official Guidance
- [EU AI Office](https://digital-strategy.ec.europa.eu/en/policies/ai-office) - Official EU AI Act implementation body.
- [NIST AI Resource Center](https://airc.nist.gov) - Full NIST AI RMF documentation and tools.
- [ENISA AI Cybersecurity](https://www.enisa.europa.eu/topics/artificial-intelligence) - EU cybersecurity agency AI guidance.

### Articles and Guides
- [EU AI Act Compliance Roadmap for August 2026 Deadline](https://www.legalnodes.com/article/eu-ai-act-compliance-roadmap-for-august-2026-deadline) - LegalNodes step-by-step guide.
- [The EU AI Act's Hidden Market](https://medium.com/@arturs.prieditis/the-eu-ai-acts-hidden-market-how-high-risk-ai-compliance-became-a-17-billion-opportunity-734cea9b41e2) - €17B market analysis.
- [How open-source devtools get monetized](https://posthog.com/blog/open-source-business-models) - PostHog handbook on open-source business models.

### Papers
- [A Survey of Fairness in Machine Learning](https://arxiv.org/abs/1908.09635) - Moritz Hardt et al.
- [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/) - Christoph Molnar, free book.

---

## Newsletters and Communities

- [MLOps Community Slack](https://go.mlops.community/slack) - 27,900+ ML engineers. Best community for production ML.
- [DataTalks.Club Slack](https://datatalks.club/slack.html) - 13,300+ data practitioners.
- [IAPP AI Governance Community](https://iapp.org) - Privacy and AI governance professionals.
- [EU Artificial Intelligence Act Newsletter](https://artificialintelligenceact.eu) - Weekly updates on EU AI Act developments.
- [TLDR AI](https://tldr.tech/ai) - Daily AI newsletter, 500K+ subscribers.
- [The Batch (DeepLearning.AI)](https://www.deeplearning.ai/the-batch/) - Weekly AI news with practical focus.

---

## Conferences and Events

- [IAPP AI Governance Global Europe 2026](https://iapp.org/conference/iapp-ai-governance-global-europe/) - Dublin, June 1–4, 2026. Premier EU AI Act compliance event.
- [MLOps World](https://mlopsworld.com) - Annual conference for ML engineering and operations.
- [FAccT (ACM)](https://facctconference.org) - Fairness, Accountability, and Transparency in ML.
- [NeurIPS](https://neurips.cc) - Top ML research conference with growing governance track.

---

## Contributing

Contributions welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR.

To add a resource: fork the repo, add your entry in the correct section, and open a pull request.
Criteria: publicly accessible, actively maintained, genuinely useful for AI compliance practitioners.
