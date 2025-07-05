# Vendor Risk Assessment Checklist: ShopVita

| Risk Item                                | Status   | Remarks                                 |
|------------------------------------------|----------|------------------------------------------|
| NDA Signed                               | ✅ Yes   | Documented in vendor agreements          |
| Unique Access Credentials                | ❌ No    | Shared logins currently in use           |
| MFA Enabled                              | ❌ No    | Not implemented                          |
| Security Policy Shared                   | ⚠️ Partial| Generic, not ISO-aligned                 |
| SLA includes breach reporting clause     | ❌ No    | Needs revision                           |
| Encryption of shared data                | ✅ Yes   | TLS in transit, but endpoint unclear     |

---

## Recommendation

- Implement MFA and unique logins  
- Add breach notification clause to SLA  
- Review vendor contracts quarterly  
