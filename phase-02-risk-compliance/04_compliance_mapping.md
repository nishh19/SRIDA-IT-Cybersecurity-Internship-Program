# 🧾 Compliance Mapping Summary

| Framework       | Control / Clause          | Status         | Gap Summary                               |
|-----------------|---------------------------|----------------|--------------------------------------------|
| ISO 27001:2022  | A.5.30 – ICT Continuity    | Not Implemented| No BCP/DR tested                           |
| ISO 27001:2022  | A.5.36 – Legal Compliance  | Partial        | No legal register maintained               |
| GDPR            | Article 7 – Consent        | Not Compliant  | Consent not logged, no cookie banner       |
| DPDPA (India)   | Clause 8 – User Rights     | Not Aligned    | No mechanism for export/edit/delete        |
| PCI DSS v4.0    | Requirement 4 – TLS Config | Partial        | Weak ciphers in TLS; needs updating        |
| IT Act 2000     | Section 43A                | Not Compliant  | No formal privacy safeguards               |

---

## 🔧 Action Plan

- Maintain legal obligation register (A.5.36)  
- Upgrade TLS to v1.2+ with strong ciphers (PCI DSS v4.0)  
- Create a privacy policy with consent management (GDPR + DPDPA)  
