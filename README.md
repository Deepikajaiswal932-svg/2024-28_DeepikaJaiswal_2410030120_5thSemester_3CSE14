# YUVA Cybersecurity Internship — Deliverables & Portfolio

**Intern:** Deepika Jaiswal  
**Student ID:** 2410030120  
**Role:** Junior Cyber Security Analyst  
**Program:** YUVA Cybersecurity Internship Program  
**Target System:** AuraGov National Citizen Services Portal (`auragov.service.gov`)  

---

## 📌 Executive Summary

This repository contains the complete technical deliverables for my 4-week engagement in the **YUVA Cybersecurity Internship Program**. During this internship, I evaluated and strengthened the security posture of the **AuraGov National Citizen Services Portal**, a high-volume cloud-native e-governance platform hosting 150+ digital public services.

### Key Milestones Summary
* **Week 1 (Infrastructure Assessment):** Mapped Kubernetes microservices topology and identified critical vulnerabilities including Broken Object Level Authorization (BOLA), JWT signature validation gaps, and weak rate-limiting.
* **Week 2 (Threat & Risk Modeling):** Built a 6-tier threat matrix mapped to MITRE ATT&CK techniques, scored risks quantitatively ($R = L \times I$), and established a 180-day technical mitigation plan.
* **Week 3 (Incident Response Simulation):** Participated in "Operation Silent Exfil" (BOLA + forged JWT attack simulation) under NIST SP 800-61 guidelines—achieving a **7-min MTTD**, **15-min MTTC**, and **0-minute system downtime**.
* **Week 4 (Strategic Planning 2026–2030):** Formulated a 4-year defense roadmap focusing on Post-Quantum Cryptography (ML-KEM/ML-DSA), AI-driven behavior monitoring, and Self-Sovereign Identity (SSI) with Zero-Knowledge Proofs (ZKP).

---

## 📁 Repository Structure & File Directory

| File Name | Description |
| :--- | :--- |
| `Deepika_Jaiswal_2410030120 Cybersecurity_Int...` | **Final Technical Report:** Complete 5-page synthesis detailing Week 1–4 audits, architecture diagrams, risk matrices, and incident response logs. |
| `Cybersecurity Internship Presentation.pdf` | **Executive Slide Deck:** Visual presentation summarizing core findings, incident metrics, and strategic recommendations. |
| `completion-letter-183345_406068_1788165962...` | **Official Certificate:** Internship completion verification issued by the YUVA Cybersecurity Internship Program. |

---

## 📊 Key Operational Metrics (Incident Response Drill)

| Metric | Target Baseline | Simulated Result | Status |
| :--- | :--- | :--- | :--- |
| **Mean Time to Detect (MTTD)** | < 15 Minutes | **7 Minutes** | Achieved |
| **Mean Time to Contain (MTTC)** | < 30 Minutes | **15 Minutes** | Achieved |
| **Service Downtime** | 0 Minutes | **0 Minutes** | Hot-patch deployed |
| **Data Exfiltration Capped** | < 5,000 Records | **1,240 Records** | Contained |
