# msw
A practical, lifecycle-based Guide to securing AI/ML systems. Covers Model Scanning, Threat Modeling, and Governance (MCP).

# 🛡️ Model Security Warriors

A practical guide to securing AI/ML systems across the lifecycle — from scanning model files to governing agentic behavior.

---

## 🔁 Model Lifecycle & Security Touchpoints

| Phase            | Key Risks                           | Security Activities                       |
|------------------|--------------------------------------|--------------------------------------------|
| Training         | Data leakage, poisoning              | Validation, secure sourcing                |
| Serialization    | Malicious code in model files        | ClamAV, PickleScan, ModelScan              |
| Deployment       | API exposure, inference misuse       | Auth control, Fortify, SAST tools          |
| Inference        | Prompt injection, model drift        | Input filtering, audit logging             |
| Agentic Use      | Autonomy, hallucination, jailbreaks  | Governance via MCP, logging, testing       |
| A2A Execution    | Unchecked escalation or logic loops  | Delegated policy, tool use boundaries      |

---

## 📦 Repo Structure (coming soon)

- `/scanners`: model security tools (PickleScan, ClamAV, etc.)
- `/governance`: MCP, prompt control, context protocol
- `/threat-modeling`: how model TM differs from product TM
- `/examples`: scan walkthroughs, jailbreak testing, etc.

---

## 👥 Who is this for?

- Security Architects & Engineers
- AI/ML Engineers building secure systems
- CISOs & Risk Analysts needing ML governance

