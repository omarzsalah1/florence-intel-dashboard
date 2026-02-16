# Florence AI Navigator - Sales Enablement Package

**Version:** 1.0  
**Date:** February 15, 2026  
**Confidential - Internal Use Only**

---

## 1. Value Proposition Summary

Florence AI Navigator is an intelligent care coordination platform that sits alongside the EHR to automate the most time-consuming aspects of value-based care. Florence reduces navigator workload by up to 90% while improving care gap closure rates, HCC capture accuracy, and patient engagement.

### The Three Pillars of Florence

| Pillar | Description | Key Benefit |
|--------|-------------|-------------|
| **Pre-Visit Intelligence** | Analyzes claims, clinical data, and guidelines to identify care gaps before the visit | Ensures no gap is missed; reduces chart review from 30 min to 30 seconds |
| **Real-Time Clinical Support** | Provides MEAT-compliant documentation, staging, and physician decision support during the visit | Increases HCC capture by 15-25%; reduces physician documentation burden |
| **Post-Visit Automation** | Automates referral scheduling, lab orders, patient education, and follow-up tracking | Reduces post-visit tasks from 45 min to 5 min per patient |

---

## 2. Target Buyer Personas

### Chief Medical Officer (CMO)

**Pain Points:** Quality score performance, physician burnout, documentation compliance, HCC accuracy.

**Key Messages:**
- Florence ensures every diagnosis is documented with proper MEAT criteria, reducing audit risk
- Physicians spend less time on documentation and more time on patient care
- Quality measures are tracked and addressed proactively, not reactively

**ROI Metric:** 15-25% improvement in HCC capture rate translates to $500-$1,500 per member per year in risk adjustment revenue.

### VP of Quality / Population Health

**Pain Points:** Care gap closure rates, HEDIS/STARS performance, navigator efficiency, referral leakage.

**Key Messages:**
- Florence identifies and stages care gaps from multiple data sources (claims, clinical, pharmacy)
- Automated follow-up ensures referrals are completed, not just ordered
- Real-time dashboards show gap closure progress across the entire patient panel

**ROI Metric:** 20-30% improvement in care gap closure rates within 6 months of deployment.

### Care Navigation Director

**Pain Points:** Navigator staffing shortages, high turnover, inconsistent workflows, manual documentation.

**Key Messages:**
- Florence automates 80% of routine navigator tasks (documentation, scheduling, education)
- Standardized workflows reduce training time for new navigators from 6 weeks to 2 weeks
- Each navigator can manage 3x more patients with Florence

**ROI Metric:** Equivalent of 2-3 FTE navigators recovered per 500 Medicare patients.

### Chief Technology Officer (CTO)

**Pain Points:** EHR integration complexity, data security, scalability, vendor lock-in.

**Key Messages:**
- Florence integrates via FHIR APIs with athenaOne, Epic, Cerner, and other major EHRs
- SOC 2 Type II compliant, HIPAA-compliant, data encrypted at rest and in transit
- Cloud-native architecture scales from single practice to enterprise health system

**ROI Metric:** Implementation in 4-6 weeks with minimal IT resources required.

---

## 3. Frequently Asked Questions (FAQ)

### Clinical Questions

**Q: How accurate is Florence's gap identification?**
A: Florence uses a combination of claims data analysis, clinical NLP, and evidence-based guidelines. Our clinical validation studies show 94% precision and 91% recall for HCC gap identification. Every recommendation is reviewed by the care team before action.

**Q: Does Florence replace the physician's clinical judgment?**
A: Absolutely not. Florence is a decision support tool. It surfaces relevant clinical information and pre-populates documentation, but every diagnosis, order, and treatment decision is made by the physician. Florence simply ensures nothing is missed.

**Q: How does Florence handle false positives (gaps that aren't real)?**
A: Florence provides a confidence score for each gap and includes the clinical evidence supporting the recommendation. The navigator reviews and filters gaps before they reach the physician. Physicians can dismiss any gap with a documented reason, which Florence uses to improve future recommendations.

**Q: What clinical guidelines does Florence use?**
A: Florence incorporates CMS HCC risk adjustment guidelines, HEDIS/STARS quality measures, USPSTF screening recommendations, and specialty-specific clinical practice guidelines. Guidelines are updated quarterly.

### Technical Questions

**Q: How does Florence integrate with our EHR?**
A: Florence uses FHIR R4 APIs for bidirectional data exchange. For athenaOne, we use the athenaOne Marketplace APIs. For Epic, we use the Epic App Orchard. Integration typically takes 4-6 weeks.

**Q: Where is patient data stored?**
A: Patient data is processed in real-time and stored in HIPAA-compliant cloud infrastructure (AWS GovCloud). Data is encrypted at rest (AES-256) and in transit (TLS 1.3). We maintain SOC 2 Type II certification.

**Q: Can Florence work with our existing population health platform?**
A: Yes. Florence can ingest data from COOP, Arcadia, Innovaccer, Lightbeam, and other population health platforms via standard data feeds or API integration.

**Q: What happens if Florence is unavailable?**
A: Florence is designed with 99.9% uptime SLA. In the unlikely event of downtime, navigators and physicians can continue working in the EHR as usual. Florence will sync any changes when service is restored.

### Business Questions

**Q: What is the pricing model?**
A: Florence is priced on a per-member-per-month (PMPM) basis, scaled to your Medicare/Medicaid population size. Contact our sales team for a custom quote.

**Q: How long does implementation take?**
A: Typical implementation is 4-6 weeks, including EHR integration, data onboarding, workflow configuration, and staff training. We provide a dedicated implementation manager.

**Q: What training is required?**
A: Florence is designed to be intuitive. Navigator training is typically 4 hours (half-day). Physician training is 30 minutes (integrated into existing workflow). We provide ongoing training resources and a dedicated customer success manager.

**Q: Can we pilot Florence before a full rollout?**
A: Yes. We recommend starting with a pilot of 200-500 patients over 90 days. This allows you to measure ROI and refine workflows before scaling.

---

## 4. Objection Handling Guide

### "We already have a population health platform."

> "That's great, and Florence is designed to complement your existing platform, not replace it. Your pop health platform identifies gaps at the population level. Florence takes those gaps and operationalizes them at the point of care, ensuring they're addressed during the patient visit. Think of it as the 'last mile' of care gap closure."

### "Our navigators already do this manually."

> "Your navigators are incredibly valuable, and that's exactly why we want to free them from manual tasks. Today, a navigator spends 70% of their time on documentation, scheduling, and data entry. Florence automates those tasks so your navigators can spend 70% of their time on what they do best: building relationships with patients and coordinating complex care."

### "We're concerned about AI making clinical decisions."

> "We share that concern, which is why Florence is designed as a decision support tool, not a decision-making tool. Every recommendation goes through a human review process: the navigator stages gaps, and the physician accepts or dismisses them. Florence simply ensures the right information is in front of the right person at the right time."

### "We don't have the IT resources for another integration."

> "We understand IT bandwidth is limited. That's why Florence is designed for minimal IT involvement. Our implementation team handles the EHR integration, data mapping, and configuration. Your IT team's involvement is typically limited to API access provisioning and security review, which takes about 2-3 hours total."

### "How do we know this will actually improve our quality scores?"

> "We offer a 90-day pilot with clear success metrics. We'll measure care gap closure rates, HCC capture accuracy, navigator time savings, and patient engagement before and after Florence. If we don't demonstrate measurable improvement, you can walk away with no obligation."

### "We've been burned by AI vendors before."

> "We hear that a lot, and it's a valid concern. What makes Florence different is that we're not asking you to trust a black box. Every recommendation comes with clinical evidence, confidence scores, and a clear audit trail. Your clinical team maintains full control. And our 90-day pilot lets you validate results before committing."

---

## 5. ROI Calculator

### Assumptions

| Parameter | Value | Source |
|-----------|-------|--------|
| Medicare patients | 500 | Practice input |
| Average navigator salary (loaded) | $65,000/year | BLS 2025 |
| Navigator hours per patient per year | 4.5 hours | Industry benchmark |
| Florence time reduction | 80% | Internal validation |
| Average HCC gap value | $1,200/year | CMS RAF data |
| Current HCC capture rate | 65% | Practice input |
| Improved HCC capture rate | 82% | Florence benchmark |
| Care gap closure improvement | 25% | Florence benchmark |

### Annual ROI Projection

| Category | Calculation | Annual Value |
|----------|-------------|-------------|
| **Navigator Time Savings** | 500 patients x 4.5 hrs x 80% reduction x $31.25/hr | **$56,250** |
| **HCC Revenue Recovery** | 500 patients x 17% improvement x $1,200 avg value | **$102,000** |
| **Quality Bonus Improvement** | 25% gap closure improvement on STARS/HEDIS measures | **$25,000-$75,000** |
| **Reduced Readmissions** | 15% reduction in 30-day readmissions (TCM compliance) | **$30,000-$50,000** |
| **Total Annual Value** | | **$213,250-$283,250** |

### Payback Period

At a typical PMPM rate, most practices achieve full ROI within 4-6 months of deployment.

---

## 6. Competitive Landscape

| Capability | Florence AI | Innovaccer | Arcadia | Lightbeam |
|-----------|------------|------------|---------|-----------|
| Real-time EHR integration | Yes | Partial | No | No |
| AI-powered gap identification | Yes | Yes | Yes | Yes |
| Automated MEAT documentation | Yes | No | No | No |
| Point-of-care physician support | Yes | No | No | No |
| Automated referral scheduling | Yes | No | No | No |
| Patient communication automation | Yes | Partial | No | Partial |
| TCM call workflow | Yes | No | No | No |
| Navigator task automation | Yes | No | Partial | No |

### Key Differentiators

1. **Point-of-Care Integration:** Florence is the only solution that provides real-time decision support during the patient visit, not just pre-visit analytics.

2. **Full-Cycle Automation:** From gap identification through referral completion and patient education, Florence automates the entire care coordination lifecycle.

3. **MEAT-Compliant Documentation:** Florence is the only solution that generates audit-ready MEAT documentation for every diagnosis, reducing compliance risk.

4. **Navigator Workflow Optimization:** Florence is purpose-built for care navigators, not retrofitted from a population health platform.

---

## 7. Implementation Timeline

| Week | Milestone | Activities |
|------|-----------|------------|
| 1-2 | **Discovery & Planning** | Workflow assessment, data mapping, success metrics definition |
| 3-4 | **Integration & Configuration** | EHR API setup, data onboarding, workflow configuration |
| 5 | **Training & Testing** | Navigator training (4 hrs), physician orientation (30 min), UAT |
| 6 | **Go-Live** | Pilot launch with 200-500 patients, daily monitoring |
| 7-12 | **Optimization** | Weekly reviews, workflow refinement, expansion planning |
| 13+ | **Scale** | Full patient panel rollout, advanced features activation |

---

*For questions or to schedule a demo, contact the NightingaleMD sales team.*
