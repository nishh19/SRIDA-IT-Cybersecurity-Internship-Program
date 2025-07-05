# Data Classification Template: ShopVita

| Data Type             | Classification | Access Control | Encryption | Retention |
|------------------------|----------------|----------------|------------|-----------|
| Name + Email           | PII – High     | RBAC           | Yes        | 5 Years   |
| Payment Info (last 4)  | PCI – High     | Restricted     | Yes        | 1 Year    |
| Product Reviews        | Public         | Open           | No         | Unlimited |
| Internal Orders        | Internal       | Staff Only     | Optional   | 7 Years   |

---

### Notes:
- Follows ISO 27001:2022 (A.5.12 – Classification of Information)  
- Can be integrated into DLP tools and access policies  
