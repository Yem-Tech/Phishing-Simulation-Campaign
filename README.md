# Phishing Simulation Campaign
### User Awareness and Education Assessment

> **Confidentiality Notice:** This project documents an authorised phishing simulation conducted strictly for awareness, education, and security control improvement purposes. All exercises were performed in a controlled lab environment. No real users, systems, or credentials were targeted or compromised.

---

## Campaign Overview

| Field | Details |
|---|---|
| **Campaign Type** | Internal phishing simulation for user awareness and education |
| **Simulation Platform** | Zphisher (authorised internal lab use only) |
| **Environment** | Isolated local environment (localhost 127.0.0.1) |
| **Measured KPIs** | Click rate, credential submission rate, reported rate |
| **Prepared By** | Cybersecurity Analyst in Training |
| **Purpose** | Academic lab exercise — Security Awareness Education |

---

## 1. Executive Summary

This project presents a controlled phishing simulation conducted to assess user susceptibility to phishing attempts and to demonstrate the effectiveness of security awareness education. The simulation was executed in an authorised, isolated lab environment and evaluated user behaviour against key indicators of phishing resilience.

The primary purpose of the exercise was to establish a behavioural baseline, demonstrate how phishing attacks operate from a technical perspective, and reinforce why end-user awareness is a critical layer of any organisation's security posture. The project focuses on three core KPIs: click rate, credential submission rate, and reporting rate.

> This lab exercise is aligned with the **CIA Triad** — specifically addressing **Confidentiality** risks introduced by social engineering, and how **Availability** and **Integrity** of systems can be compromised when users fall victim to phishing attacks.

---

## 2. Objectives

- Demonstrate how phishing simulation tools operate in a controlled lab environment
- Understand the technical mechanics behind credential harvesting phishing pages
- Assess the importance of user awareness training in reducing phishing susceptibility
- Identify how organisations can measure and improve phishing resilience through KPI tracking
- Develop documentation skills aligned with professional cybersecurity reporting standards

---

## 3. Scope and Approach

The simulation covered a controlled phishing exercise designed entirely for internal awareness testing within an isolated lab environment. A pre-awareness phishing exercise was conducted to establish a baseline, followed by awareness and education activities. A post-awareness review was then used to measure understanding of behavioural change against the same KPI categories.

> **Ethical and Governance Note:** This simulation was conducted with full academic authorisation, within a defined lab scope, and with clear rules of engagement. This documentation intentionally describes the exercise at a high level and does not include technical details that would enable misuse outside an authorised context.

---

## 4. Methodology

**Step 1 — Environment Setup:**
A dedicated simulation directory was created within an isolated Kali Linux lab environment to contain all project files and tooling.

**Step 2 — Tool Deployment:**
An open-source phishing simulation framework was cloned and configured within the controlled environment for educational demonstration purposes.

**Step 3 — Simulated Page Generation:**
A replica login page was generated on localhost to demonstrate how phishing pages mimic legitimate services to deceive users.

**Step 4 — Baseline Measurement:**
Dummy test credentials were submitted to the simulated page to observe how credential harvesting operates technically, using entirely fictitious data.

**Step 5 — Awareness Intervention:**
Findings were reviewed and mapped to user awareness training content covering phishing identification, safe response behaviour, and internal reporting procedures.

**Step 6 — Comparative Analysis:**
Before-and-after KPI values were reviewed conceptually to determine how awareness programmes improve organisational resilience.

---

## 5. KPI Definitions

| KPI | Definition |
|---|---|
| **Click Rate** | The percentage of targeted users who clicked the phishing link or interacted with the simulated malicious prompt |
| **Credential Submission Rate** | The percentage of targeted users who entered credentials or sensitive information into the simulated phishing page |
| **Reported Rate** | The percentage of targeted users who identified the message as suspicious and reported it through the approved reporting channel |

---

## 6. KPI Comparison

| KPI | Before Awareness | After Awareness | Change | Interpretation |
|---|---|---|---|---|
| Click Rate | High | Reduced | ↓ Decrease | Lower values indicate improved user caution |
| Credential Submission Rate | High | Reduced | ↓ Decrease | Lower values indicate reduced compromise likelihood |
| Reported Rate | Low | Increased | ↑ Increase | Higher values indicate stronger security awareness and escalation behaviour |

> In a real organisational deployment, these values would be populated with precise percentage measurements from the campaign analytics dashboard.

---

## 7. Analysis of Results

Lower click and credential submission rates typically indicate improved user caution, message scrutiny, and understanding of phishing indicators. A higher reporting rate indicates that users are not only identifying suspicious content but are also following the organisation's escalation procedure correctly.

**Baseline risk indicator:**
Prior to awareness intervention, simulated users demonstrated high susceptibility — clicking links and submitting credentials without verifying the legitimacy of the page or sender.

**Post-awareness improvement:**
Following awareness content delivery, simulated users demonstrated improved ability to identify phishing indicators including suspicious URLs, mismatched branding, and unsolicited credential requests.

**Residual concern:**
Even after awareness training, a subset of users may remain susceptible — particularly to highly convincing spear-phishing lures that closely mimic trusted internal communications.

**Operational implication:**
Results demonstrate that technical controls alone are insufficient. Human behaviour remains a critical attack surface. Continuous awareness training, clear reporting procedures, and periodic simulation are essential components of a mature security awareness programme.

---

## 8. Key Findings

- **Finding 1:** Phishing pages can convincingly replicate legitimate login portals, making visual inspection alone an unreliable defence mechanism for untrained users.
- **Finding 2:** Credential submission behaviour represents the highest risk outcome — once credentials are harvested, attackers gain unauthorised access without any further technical exploit.
- **Finding 3:** User reporting behaviour is typically the weakest KPI prior to awareness intervention, highlighting the need for clear, practised escalation procedures.
- **Finding 4:** Awareness and education activities demonstrably improve user resilience when content is relevant, timely, and reinforced through repeated simulation cycles.

---

## 9. Recommendations

- Continue periodic phishing simulations to reinforce awareness and measure long-term behavioural trends
- Provide targeted retraining for users or departments with higher click or credential submission rates
- Improve internal reporting visibility by making the reporting process simple, visible, and routinely practised
- Align phishing awareness content with common lures relevant to the organisation's business context
- Track KPI trends over time and report them to management as part of the broader security awareness programme
- Implement supplementary technical controls including email filtering, warning banners, MFA enforcement, and conditional access policies

---

## 10. Conclusion

This phishing simulation lab exercise provides measurable insight into user phishing resilience and the effectiveness of awareness interventions. When supported by management authorisation, repeated assessment cycles, and clear reporting procedures, phishing simulations significantly improve organisational readiness against social engineering threats.

This project demonstrates understanding of how phishing attacks operate technically, why they remain one of the most effective attack vectors against organisations, and how cybersecurity professionals design and execute awareness programmes to measurably reduce human risk.

---

## Tools & Environment

| Component | Details |
|---|---|
| **Operating System** | Kali Linux |
| **Simulation Framework** | Zphisher v2.3.5 |
| **Environment Type** | Isolated localhost lab (127.0.0.1) |
| **Purpose** | Authorised educational simulation only |

---

## Ethical Disclaimer

> This project was conducted exclusively within an authorised academic lab environment. All targets were dummy accounts with fictitious credentials. No real users, real credentials, or live systems were involved at any stage. The techniques documented here are presented for educational purposes to help cybersecurity professionals understand attack vectors and design effective defences. Unauthorised use of phishing tools against real users or systems is illegal and unethical.

---

## Author

**Cybersecurity Analyst | Loram Maintenance of Way**
Certifications: CCNA | Microsoft Azure | AWS | CompTIA Security+ | Python
Education: Post-Graduate Diploma in Business Analytics | Diploma in French
Currently pursuing: Advanced Cybersecurity specialisation

---

*This report was prepared following professional cybersecurity reporting standards for academic portfolio purposes.*

