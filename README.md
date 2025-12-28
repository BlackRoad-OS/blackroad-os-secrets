# BlackRoad OS Secrets — Private Repository

**⚠️ PRIVATE REPOSITORY — DO NOT MAKE PUBLIC**

**Entity:** BlackRoad OS, Inc.
**Type:** Delaware C-Corporation
**Founder/CEO:** Alexa Louise Amundson
**Purpose:** Secure storage for corporate documents, credentials, API keys, and sensitive information

---

## 🔒 Security Notice

This repository contains:
- ✅ Official incorporation documents
- ✅ Stock certificates and tax filings
- ✅ API keys and credentials
- ✅ Private keys and certificates
- ✅ Attorney-client privileged materials

**DO NOT:**
- ❌ Make this repository public
- ❌ Share access without authorization
- ❌ Clone to public machines
- ❌ Include in public documentation

**Access Control:**
- 🔐 Alexa Louise Amundson (Owner)
- 🔐 Authorized team members only
- 🔐 2FA required for all access

---

## 📂 Repository Structure

```
blackroad-os-secrets/
├── corporate/
│   └── incorporation/          → Atlas incorporation documents (18 PDFs)
├── credentials/
│   ├── api-keys/               → API keys by service
│   ├── ssh-keys/               → SSH keys for servers
│   └── certificates/           → SSL/TLS certificates
├── legal/
│   ├── contracts/              → Legal agreements
│   ├── nda/                    → Non-disclosure agreements
│   └── patents/                → Patent filings
├── financial/
│   ├── banking/                → Bank account information
│   ├── tax/                    → Tax returns and filings
│   └── payroll/                → Payroll information
└── backups/
    └── encrypted/              → Encrypted backups of critical data
```

---

## 📋 Corporate Documents Inventory

### Location: `/corporate/incorporation/`

All documents from **Atlas by Stripe** formation service (November 2024):

| Document | Size | Purpose |
|----------|------|---------|
| **Approved Certificate of Incorporation** | 1.7MB | State-filed incorporation certificate |
| **Bylaws** | 142KB | Corporate bylaws and operating rules |
| **Common Stock Certificate** | 37KB | Founder stock certificate |
| **Section 83(b) Election** | 29KB | Tax election (CRITICAL - filed with IRS) |
| **CIIAA** | 107KB | IP assignment agreement |
| **RSPA** | 107KB | Restricted Stock Purchase Agreement |
| **Indemnification Agreement** | 94KB | Director/officer protection |
| **CP 575 Letter** | 20KB | IRS EIN confirmation |
| **SS-4** | 907KB | EIN application |
| **Form 8821** | 767KB | Tax information authorization |
| **Initial Board Action** | 63KB | First board meeting minutes |
| **Incorporator Consent** | 32KB | Sole incorporator consent |
| **Secretary Certificate** | 30KB | Bylaws certification |
| **Stock Assignment** | 33KB | Stock assignment document |
| **Joint Escrow Instructions** | 47KB | Stock escrow agreement |
| **Stockholder Consent** | 38KB | Indemnification approval |
| **BrokerCheck Credentials** | 287KB | BrokerCheck for CarPool |
| **Signed Certificate** | 34KB | Signed incorporation documents |

**Total:** 18 documents, 4.5MB

---

## 🔐 Critical Documents (Keep Forever)

### Must Never Lose:
1. ✅ Certificate of Incorporation — Legal proof company exists
2. ✅ Bylaws — Operating rules
3. ✅ Stock Certificate — Proof of ownership (100%)
4. ✅ Section 83(b) Election — Tax savings (FILED WITH IRS!)
5. ✅ CP 575 Letter — Federal Tax ID (EIN)

### Very Important:
6. ✅ RSPA — Founder stock agreement
7. ✅ CIIAA — IP assignment (critical for fundraising)
8. ✅ Indemnification Agreement — Legal protection
9. ✅ Board Actions — Corporate records

---

## 💾 Backup Strategy

### Current Backups:
- ✅ **GitHub (Private):** This repository (blackroad-os-secrets)
- ✅ **Local:** `/Users/alexa/blackroad-os-carpool/corporate/`
- [ ] **Cloud Encrypted:** Google Drive (encrypted folder)
- [ ] **Safe Deposit Box:** Physical copies of critical docs
- [ ] **Attorney Files:** Copies with corporate attorney

### Backup Schedule:
- **Daily:** Automatic GitHub backup (on commit)
- **Weekly:** Verify all backups accessible
- **Monthly:** Test document restoration
- **Annually:** Update safe deposit box

---

## 🔑 Credentials Management

### API Keys Location: `/credentials/api-keys/`

Services requiring secure key storage:
- Clerk (authentication)
- Stripe (payments)
- Mapbox (maps)
- OpenAI, Anthropic, Google AI (AI models)
- Cloudflare (infrastructure)
- Railway (hosting)
- GitHub (automation)
- Vercel (deployments)

### Format:
```
/credentials/api-keys/
├── clerk.env
├── stripe.env
├── mapbox.env
├── ai-providers.env
└── infrastructure.env
```

---

## 📞 Emergency Access

### If Primary Access Lost:

1. **GitHub Account Recovery:**
   - Email: amundsonalexa@gmail.com
   - 2FA recovery codes: [Safe deposit box]

2. **Legal Documents:**
   - Attorney: [Corporate attorney name]
   - Atlas Support: support@stripe.com

3. **Banking:**
   - Business bank: [Bank name]
   - Account recovery: [Process]

4. **Cloudflare:**
   - Email: blackroad.systems@gmail.com
   - Recovery: 2FA backup codes

---

## 🏢 Corporate Information

```
Entity Name:     BlackRoad OS, Inc.
Entity Type:     Delaware C-Corporation
Formation Date:  November 2024
State File No.:  [From Certificate of Incorporation]
EIN:             [From CP 575 Letter]
Registered Agent: [From incorporation docs]

Founder/CEO:     Alexa Louise Amundson
Ownership:       100% (founder shares)

Registered Office:
[Delaware registered agent address]

Business Address:
[Operating address]
```

---

## 📅 Compliance Calendar

### Annual Requirements:

**Delaware:**
- **March 1:** Franchise Tax due (~$450 minimum)
- **December 31:** Annual board meeting

**Federal (IRS):**
- **April 15:** Corporate tax return (Form 1120)
- **Quarterly:** Estimated taxes (if profitable)
- **January 31:** 1099s for contractors

**Corporate Governance:**
- **Quarterly:** Board meetings (recommended)
- **Annually:** Update corporate records
- **Ongoing:** Maintain separate bank account

---

## 🚨 Security Protocols

### Access Protocols:
1. ✅ Never clone on public computers
2. ✅ Always use HTTPS (not SSH) for Git operations
3. ✅ Enable 2FA on all accounts
4. ✅ Rotate API keys every 90 days
5. ✅ Encrypt sensitive files before commit (if needed)

### Incident Response:
If this repository is compromised:
1. **Immediately** rotate all API keys
2. Contact legal counsel
3. Notify relevant parties (bank, Stripe, etc.)
4. Review GitHub audit logs
5. Change all passwords
6. Enable additional security measures

---

## 🔗 Related Repositories

**Public Repositories:**
- BlackRoad-OS/blackroad-os-carpool — Main product (CarPool)
- BlackRoad-OS/blackroad-os-operator — Infrastructure operations
- BlackRoad-OS/* — All other public repos

**Private Repositories:**
- BlackRoad-OS/blackroad-os-secrets — **THIS REPO** (sensitive documents)

**Connection:**
- CarPool references this repo for deployment credentials
- Operator uses API keys stored here
- Corporate docs stay ONLY in this private repo

---

## 📝 Usage Notes

### Adding New Documents:
```bash
cd /Users/alexa/blackroad-os-secrets

# Add document to appropriate folder
cp ~/path/to/document.pdf corporate/incorporation/

# Commit and push
git add .
git commit -m "Add: [Document name]"
git push origin main
```

### Retrieving Documents:
```bash
cd /Users/alexa/blackroad-os-secrets
git pull origin main
open corporate/incorporation/
```

### Sharing Access:
```bash
# Only authorize trusted team members
gh api repos/BlackRoad-OS/blackroad-os-secrets/collaborators/[username] -X PUT
```

---

## ⚠️ Legal Notice

All documents in this repository are:
- **Confidential** — Subject to attorney-client privilege where applicable
- **Proprietary** — Property of BlackRoad OS, Inc.
- **Protected** — Trade secrets and confidential business information
- **Private** — Not for public disclosure

Unauthorized access, use, or distribution may result in:
- Civil liability
- Criminal prosecution
- Breach of fiduciary duty

---

## 📚 Documentation

For more information, see:
- `corporate/incorporation/README.md` — Corporate document details
- `credentials/README.md` — Credential management guide
- `legal/README.md` — Legal document index
- `financial/README.md` — Financial records

---

**Repository Created:** December 28, 2024
**Last Updated:** December 28, 2024
**Status:** ✅ Active and secure
**Access:** 🔐 Private (Alexa only)

---

**Remember:** This is the most important repository for BlackRoad OS, Inc.
**Treat it accordingly.** 🔒
