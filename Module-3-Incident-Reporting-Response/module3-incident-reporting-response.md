# Module 3: Incident Reporting & Response

## Immediate Steps After a Suspected Breach and the Value of "Near-Miss" Reporting

---

### 📘 Module Information

| Detail | Description |
|---|---|
| **Module** | 3 of 3 — Incident Reporting & Response |
| **Course** | Data Security for Accounting Students |
| **Program** | DBA201 — SY 2025–2026, 2nd Semester |
| **Modality** | Online |
| **Duration** | 90–120 minutes |
| **Target Learners** | Accounting Students |

---

### 🎯 Intended Learning Outcomes (ILOs)

By the end of this module, learners will be able to:

1. **Identify** signs of a potential data breach
2. **Follow** established reporting procedures
3. **Explain** the importance of reporting "near-miss" incidents
4. **Support** containment and recovery efforts appropriately

---

### 📚 Knowledge Framework

| Type | Focus |
|---|---|
| **Declarative Knowledge** | Incident Reporting & Response — Immediate steps to take after a suspected breach and the value of "near-miss" reporting |
| **Functional Knowledge** | Knowledge of incident response protocols and the importance of timely reporting |

---

## Part 1: Understanding Data Breaches in Accounting

### 1.1 What Is a Data Breach?

A **data breach** is any incident where confidential, protected, or sensitive information is accessed, disclosed, altered, or destroyed without authorization.


### 1.2 Breach vs. Incident vs. Near-Miss

Understanding the difference is critical for proper reporting:

| Term | Definition | Example |
|---|---|---|
| **Data Breach** | Confirmed unauthorized access to or disclosure of sensitive data | Attacker downloads 200 client tax returns from compromised QuickBooks account |
| **Security Incident** | Any event that threatens the confidentiality, integrity, or availability of data — may or may not result in a breach | Employee's laptop is stolen but full-disk encryption was enabled — data may not be exposed |
| **Near-Miss** | An event that *could have* resulted in a breach but was prevented or did not materialize | Phishing email targeting the payroll team was caught by the spam filter before anyone clicked |

> ⚠️ **Key Insight:** Near-misses are NOT "nothing happened" events. They are **early warning signals** that reveal vulnerabilities before attackers exploit them.

---

## Part 2: Identifying Signs of a Potential Data Breach

### 2.1 The 12 Warning Signs Every Accountant Must Know

#### Category A: Account & Access Anomalies

| # | Warning Sign | What It Looks Like |
|---|---|---|
| 1 | **Unexpected password reset emails** | You receive a "password changed" notification for QuickBooks, email, or cloud storage — but you didn't request it |
| 2 | **Locked out of your account** | Your credentials no longer work despite not changing them |
| 3 | **Unfamiliar login locations** | Microsoft 365 shows a login from a city or country you've never been to |
| 4 | **MFA prompts you didn't trigger** | Your authenticator app or SMS sends a code you didn't request |
| 5 | **New admin accounts appear** | An unknown user with admin privileges appears in your firm's cloud platform |

#### Category B: System & File Anomalies

| # | Warning Sign | What It Looks Like |
|---|---|---|
| 6 | **Files modified without explanation** | A financial statement's "last modified" date changed overnight — but no one was working |
| 7 | **Missing or deleted files** | Client folders or tax documents disappear from shared drives |
| 8 | **Unusual file sharing activity** | Sharing permissions changed to "Anyone with the link" on sensitive folders |
| 9 | **Unexpected software installed** | New programs, browser extensions, or remote access tools appear on your work device |

#### Category C: Communication & Behavioral Anomalies

| # | Warning Sign | What It Looks Like |
|---|---|---|
| 10 | **Clients report suspicious contact** | A client says they received an email "from your firm" requesting bank details — but your firm didn't send it |
| 11 | **Unusual outbound emails** | Your sent folder shows emails you didn't write, or colleagues report receiving strange messages from your account |
| 12 | **Unexplained financial transactions** | Vendor payments redirected to unfamiliar bank accounts (Business Email Compromise — BEC) |

### 2.2 The "Something Feels Wrong" Rule

> If something feels unusual, unexpected, or "off" — **report it immediately**. You do NOT need to confirm it's a breach before reporting. That's the incident response team's job.

**The cost of a false alarm:** A few minutes of investigation.
**The cost of delayed reporting:** ₱500,000–₱5,000,000 in fines, client lawsuits, CPA license at risk.

---

## Part 3: The Incident Response Framework

### 3.1 The 6-Phase Incident Response Lifecycle

Based on **NIST SP 800-61 Rev. 2** (Computer Security Incident Handling Guide):

```
┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│ 1. PREPARE   │───▶│ 2. IDENTIFY  │───▶│ 3. CONTAIN   │
│              │    │              │    │              │
│ Plans, tools │    │ Detect the   │    │ Stop the     │
│ training     │    │ incident     │    │ bleeding     │
└──────────────┘    └──────────────┘    └──────────────┘
                                              │
┌──────────────┐    ┌──────────────┐    ┌─────▼────────┐
│ 6. LESSONS   │◀───│ 5. RECOVER   │◀───│ 4. ERADICATE │
│   LEARNED    │    │              │    │              │
│ Improve for  │    │ Restore      │    │ Remove the   │
│ next time    │    │ operations   │    │ threat       │
└──────────────┘    └──────────────┘    └──────────────┘
```

### 3.2 Your Role in Each Phase (As an Accountant)

#### Phase 1: PREPARE (Before Any Incident)

| Action | Your Responsibility |
|---|---|
| Know your firm's incident response plan | Read it. Know where it is. Know who to call. |
| Save emergency contacts | IT Security team, Data Protection Officer (DPO), firm partner |
| Enable security features | MFA on all accounts, full-disk encryption, auto-lock screen |
| Attend security training | Complete all required modules — including this one |
| Know your data | Understand what sensitive data you handle and where it's stored |

#### Phase 2: IDENTIFY (Detect & Report)

This is where **you** are most critical. Accountants are often the **first to notice** something wrong.

**Immediate steps when you suspect a breach:**

```
STEP 1: STOP what you're doing
   └─▶ Do NOT try to "fix it yourself"
   └─▶ Do NOT delete evidence
   └─▶ Do NOT shut down your computer (unless instructed)

STEP 2: DOCUMENT what you observed
   └─▶ What happened? (exact description)
   └─▶ When did you notice it? (date, time)
   └─▶ What system/account is affected?
   └─▶ What data may be exposed?
   └─▶ Screenshot if possible

STEP 3: REPORT immediately
   └─▶ Call/message your IT Security team
   └─▶ Notify your direct supervisor
   └─▶ Use the firm's incident reporting channel/form
   └─▶ Do NOT wait until you're "sure" — report suspicions

STEP 4: PRESERVE evidence
   └─▶ Do NOT delete emails, files, or logs
   └─▶ Do NOT clear browser history
   └─▶ Save any suspicious emails as attachments
   └─▶ Note any error messages exactly as shown
```

#### Phase 3: CONTAIN (Stop the Spread)

| Action | Who Does It | Your Role |
|---|---|---|
| Isolate affected systems | IT Security | Disconnect from Wi-Fi/network if instructed |
| Disable compromised accounts | IT Security | Change YOUR passwords if instructed |
| Block malicious IPs/domains | IT Security | Do not access suspicious links |
| Preserve forensic evidence | IT Security | Do NOT modify or delete anything |

#### Phase 4: ERADICATE (Remove the Threat)

| Action | Who Does It | Your Role |
|---|---|---|
| Remove malware | IT Security | Allow IT to scan your device |
| Patch vulnerabilities | IT Security | Install updates when instructed |
| Reset all credentials | IT Security + You | Create new, strong passwords + re-enable MFA |
| Revoke unauthorized access | IT Security | Verify your own access is restored correctly |

#### Phase 5: RECOVER (Restore Operations)

| Action | Who Does It | Your Role |
|---|---|---|
| Restore data from backups | IT Security | Verify restored files are complete and accurate |
| Monitor for recurrence | IT Security | Report any further anomalies immediately |
| Resume normal operations | Management | Follow the timeline set by management |
| Notify affected clients | DPO / Management | Assist with client communication if requested |

#### Phase 6: LESSONS LEARNED (Improve)

| Action | Who Does It | Your Role |
|---|---|---|
| Post-incident review meeting | Entire team | Attend and contribute honestly |
| Update incident response plan | IT Security / Management | Suggest improvements based on your experience |
| Additional training | HR / IT Security | Complete any assigned follow-up training |
| Process improvements | Management | Adopt new procedures without resistance |

---

## Part 4: Reporting Procedures in Detail

### 4.1 The Reporting Chain

```
┌─────────────────────────────────────────────────────────┐
│                    YOU (Accountant)                       │
│         Detect something suspicious                      │
└─────────────────┬───────────────────────────────────────┘
                  │ IMMEDIATELY (within minutes)
                  ▼
┌─────────────────────────────────────────────────────────┐
│              IT Security Team / Helpdesk                  │
│         First responders — assess severity                │
└─────────────────┬───────────────────────────────────────┘
                  │ Within 1 hour
                  ▼
┌─────────────────────────────────────────────────────────┐
│         Data Protection Officer (DPO)                    │
│         Determines if NPC notification required           │
└─────────────────┬───────────────────────────────────────┘
                  │ Within 72 hours (if personal data breach)
                  ▼
┌─────────────────────────────────────────────────────────┐
│      National Privacy Commission (NPC)                   │
│      + Notification to affected individuals              │
└─────────────────────────────────────────────────────────┘
```

### 4.2 What to Include in Your Incident Report

Every report should contain:

| Field | Example |
|---|---|
| **Date & Time** | April 15, 2025, 2:35 PM |
| **Reporter Name** | Maria Santos, Staff Accountant |
| **Description** | Received MFA prompt I didn't trigger. Checked Microsoft 365 sign-in logs — shows login from Lagos, Nigeria at 2:30 PM. I was in Calamba at the time. |
| **Systems Affected** | Microsoft 365 (Outlook, OneDrive, SharePoint) |
| **Data Potentially Exposed** | Client tax returns (Q1 2025), payroll files, email correspondence with 15 clients |
| **Actions Taken** | Changed password immediately. Enabled MFA recovery. Did NOT access any files. Reported to IT Security via Teams. |
| **Evidence Preserved** | Screenshot of sign-in log showing foreign IP. Suspicious email saved as .eml attachment. |

### 4.3 Common Reporting Mistakes to Avoid

| ❌ Mistake | ✅ Correct Action |
|---|---|
| "I'll wait and see if it happens again" | Report immediately — every minute counts |
| "I'll try to fix it myself first" | Report first, then follow IT's instructions |
| "It's probably nothing" | Let the experts decide — your job is to report |
| "I don't want to cause trouble" | NOT reporting causes far more trouble |
| "I'll just change my password" | Change password AND report — the breach may be bigger than your account |
| Deleting the suspicious email | SAVE it as evidence — forward to IT Security |
| Shutting down the computer | Leave it on unless IT instructs otherwise — forensic evidence may be in memory |

---

## Part 5: Near-Miss Reporting — The Hidden Shield

### 5.1 What Is a Near-Miss?

A **near-miss** (also called a "close call") is a security event that **could have** resulted in a data breach but was prevented, detected early, or simply didn't materialize due to luck.

### 5.2 Near-Miss Examples in Accounting

| # | Near-Miss Scenario | Why It Matters |
|---|---|---|
| 1 | Phishing email impersonating BIR was caught by spam filter — but 3 similar emails got through last month | The filter is working NOW, but the attack pattern is escalating |
| 2 | An accountant almost clicked a malicious link but noticed the URL was misspelled | Next time, they might not notice — training needs reinforcement |
| 3 | A shared Google Drive folder was accidentally set to "Anyone with the link" but was caught during a routine audit before anyone accessed it | The misconfiguration process needs a review — why did it happen? |
| 4 | A former employee's VPN access was found still active during quarterly review — but no unauthorized access was detected | The offboarding checklist has a gap that needs fixing |
| 5 | An accountant sent a client's tax return to the wrong email address but recalled the message within 30 seconds | Email DLP rules should prevent sending sensitive files to external addresses |
| 6 | A USB drive with client data was left in a coffee shop but was returned by an honest person | USB drives with client data should be encrypted — or banned entirely |
| 7 | A junior accountant shared payroll data via personal WhatsApp but a senior caught it and stopped it | Shadow IT awareness training needs reinforcement |

### 5.3 Why Near-Miss Reporting Is Critical

```
                    THE SAFETY PYRAMID
                    (Heinrich's Triangle)

                         /\
                        /  \
                       / 1  \        ← Major Breach
                      /______\          (Data exposed, fines, lawsuits)
                     /   10   \      ← Minor Incidents
                    /__________\        (Contained quickly, no data loss)
                   /    30      \    ← Near-Misses
                  /______________\      (Could have been a breach)
                 /     300       \   ← Unsafe Behaviors
                /________________\      (Shadow IT, weak passwords, no MFA)

    For every 1 major breach, there are approximately:
    • 10 minor incidents
    • 30 near-misses
    • 300 unsafe behaviors

    Near-misses are your EARLY WARNING SYSTEM.
    Reporting them PREVENTS the major breach at the top.
```

### 5.4 The Business Case for Near-Miss Reporting

| Benefit | Explanation |
|---|---|
| **Prevents future breaches** | Each near-miss reveals a vulnerability that can be fixed BEFORE it's exploited |
| **Reduces costs** | Fixing a near-miss costs ₱0 in fines. A breach costs ₱500K–₱5M+ |
| **Improves security culture** | When people report near-misses, it normalizes security awareness |
| **Satisfies compliance** | NPC and BSP expect organizations to have proactive risk identification |
| **Protects your career** | Reporting a near-miss shows diligence. Hiding one that becomes a breach shows negligence |

### 5.5 Creating a No-Blame Reporting Culture

For near-miss reporting to work, the organization must:

1. **Never punish** employees for reporting near-misses or their own mistakes
2. **Celebrate** reports as contributions to security (not failures)
3. **Act on** every report — if nothing changes, people stop reporting
4. **Share lessons** (anonymized) across the organization
5. **Make it easy** — simple form, multiple channels (email, chat, phone, anonymous)

> 💡 **The Golden Rule:** "If you see something, say something — and nothing bad will happen to you for saying it."

---

## Part 6: Supporting Containment & Recovery

### 6.1 Your Role During Active Incident Response

When a breach is confirmed and the incident response team is working:

#### DO:

- ✅ Follow all instructions from IT Security — immediately and exactly
- ✅ Stay available for questions — you may have critical context
- ✅ Change passwords when instructed (all accounts, not just the affected one)
- ✅ Verify your own files and data for unauthorized changes
- ✅ Document anything unusual you notice during recovery
- ✅ Be honest about what happened — even if you made a mistake
- ✅ Support colleagues who may be stressed or confused

#### DON'T:

- ❌ Investigate on your own — you may destroy evidence
- ❌ Discuss the breach on social media or with unauthorized people
- ❌ Access affected systems unless cleared by IT
- ❌ Blame colleagues — focus on fixing, not finger-pointing
- ❌ Assume "it's over" after initial containment — monitoring continues
- ❌ Ignore follow-up training or process changes

### 6.2 Client Communication During a Breach

If client data is involved, your firm must notify affected clients. As an accountant, you may be asked to:

| Task | Guidelines |
|---|---|
| **Identify affected clients** | Review which client files were in the compromised system |
| **Assess data exposure** | What specific data types were exposed? (TINs, bank accounts, financials) |
| **Draft communication** | Work with DPO/Legal — never communicate independently |
| **Answer client questions** | Be honest, empathetic, and factual. Don't speculate. |
| **Document everything** | Keep records of all client notifications and responses |

### 6.3 Recovery Checklist for Accountants

After a breach is contained, verify:

- [ ] All your passwords have been changed (unique, 12+ characters)
- [ ] MFA is re-enabled on all accounts
- [ ] Your devices have been scanned and cleared by IT
- [ ] Restored files are complete and unaltered
- [ ] Sharing permissions are correct (no "Everyone" or "Anyone with link")
- [ ] No unauthorized forwarding rules on your email
- [ ] Client data integrity is verified
- [ ] You've attended the post-incident review meeting
- [ ] You understand and follow any new procedures implemented

---

## Part 7: Philippine Legal Context

### 7.1 Data Privacy Act of 2012 (RA 10173)

| Requirement | Detail |
|---|---|
| **Breach notification to NPC** | Within **72 hours** of discovery |
| **Notification to affected individuals** | "Within a reasonable period" after NPC notification |
| **What triggers notification** | Breach involving sensitive personal information OR likely to cause harm |
| **Penalties for non-compliance** | Imprisonment: 1–6 years; Fines: ₱500,000–₱5,000,000 |

### 7.2 NPC Circular 16-03: Breach Notification

The National Privacy Commission requires:

1. **Nature of the breach** — what happened, what data was involved
2. **Date of the breach** — when it occurred and when it was discovered
3. **Scope** — number of affected individuals
4. **Measures taken** — containment, eradication, recovery steps
5. **Contact person** — DPO or authorized representative
6. **Recommendations** — what affected individuals should do to protect themselves

### 7.3 Professional Standards (PICPA)

| Standard | Implication for Breach Response |
|---|---|
| **Confidentiality** | You are personally obligated to protect client data — even during a breach |
| **Professional Competence** | You must know how to respond to incidents — ignorance is not a defense |
| **Due Care** | Delayed reporting or failure to follow procedures = professional negligence |
| **Integrity** | Honest, complete reporting — even if the breach was caused by your mistake |

> ⚖️ **Bottom Line:** As a CPA, you are **personally and professionally liable** for how you handle a data breach. Proper reporting protects your clients, your firm, AND your career.

---

## Part 8: Real-World Scenarios for Accounting Students

### Scenario A: The Phishing Tax Season

> It's April 14. Maria, a junior accountant, receives an email that appears to be from the BIR: "Your firm's eFPS filing has an error. Click here to correct it immediately." The email looks legitimate — BIR logo, correct formatting, urgent tone. Maria clicks the link and enters her eFPS credentials on what turns out to be a fake site.

**What should Maria do NOW?**

1. **STOP** — close the browser immediately
2. **DOCUMENT** — screenshot the email, note the URL, record the time
3. **REPORT** — call IT Security immediately, notify her supervisor
4. **CHANGE** — change her eFPS password from a different, secure device
5. **PRESERVE** — do NOT delete the phishing email

**What should the firm do?**

1. Reset all eFPS credentials
2. Check for unauthorized filings
3. Notify BIR if fraudulent returns were filed
4. Notify NPC if client data was accessed (within 72 hours)
5. Conduct post-incident review

---

### Scenario B: The Near-Miss That Saved the Firm

> During a routine quarterly access review, the IT team discovers that a freelance bookkeeper who left 4 months ago still has full access to the firm's SharePoint and QuickBooks Online. No unauthorized access was detected in the logs.

**This is a near-miss. Why report it?**

1. The offboarding checklist has a **gap** — it didn't include cloud platform access revocation
2. The firm was **lucky** — the freelancer didn't access anything, but they could have
3. Fixing this now prevents a **future breach** when the next contractor leaves
4. It demonstrates the value of **quarterly access reviews**

**Action items:**

1. Revoke the freelancer's access immediately
2. Audit ALL former contractor/employee accounts
3. Update the offboarding checklist to include all cloud platforms
4. Implement automated access expiration for contractor accounts

---

### Scenario C: The Redirected Payment

> The firm's accounts payable clerk receives an email from what appears to be a long-time vendor: "We've changed our bank account. Please update our payment details and send this month's payment to the new account." The email comes from an address that's one letter different from the real vendor's email.

**Warning signs:**

- Bank account change request via email (social engineering)
- Email address is slightly different (typosquatting)
- Urgency — "send this month's payment"
- No phone verification requested

**Correct response:**

1. **DO NOT** update the bank details
2. **REPORT** to supervisor and IT Security immediately
3. **VERIFY** by calling the vendor at their known phone number (not the one in the email)
4. **DOCUMENT** the email as evidence of a BEC attempt
5. **REPORT** as a near-miss even if no payment was sent

---

## Part 9: Module Summary

| Topic | Key Takeaway |
|---|---|
| **Data Breach** | Unauthorized access to sensitive data — accountants are prime targets |
| **12 Warning Signs** | Account anomalies, file changes, client reports, unexpected transactions |
| **6-Phase Response** | Prepare → Identify → Contain → Eradicate → Recover → Lessons Learned |
| **Your #1 Job** | REPORT immediately — don't wait, don't investigate, don't fix it yourself |
| **Near-Misses** | Early warning signals — reporting them PREVENTS major breaches |
| **No-Blame Culture** | Reporting is celebrated, not punished |
| **Philippine Law** | NPC notification within 72 hours; fines up to ₱5M; personal CPA liability |
| **Recovery** | Verify passwords, MFA, file integrity, sharing permissions after every incident |

---

## Part 10: Key Terms Glossary

| Term | Definition |
|---|---|
| **Data Breach** | Unauthorized access to or disclosure of sensitive data |
| **Security Incident** | Any event threatening confidentiality, integrity, or availability of data |
| **Near-Miss** | Event that could have been a breach but was prevented or didn't materialize |
| **Incident Response Plan (IRP)** | Documented procedures for handling security incidents |
| **Containment** | Actions to stop a breach from spreading further |
| **Eradication** | Removing the root cause of the breach (malware, unauthorized access) |
| **DPO** | Data Protection Officer — responsible for privacy compliance |
| **NPC** | National Privacy Commission — Philippine data privacy regulator |
| **BEC** | Business Email Compromise — fraud via impersonated email |
| **Forensic Evidence** | Digital artifacts preserved for investigation (logs, emails, files) |
| **Heinrich's Triangle** | Safety model showing the ratio of near-misses to major incidents |
| **RA 10173** | Data Privacy Act of 2012 — Philippine data protection law |

---

## References

1. NIST SP 800-61 Rev. 2 — *Computer Security Incident Handling Guide*
2. NIST Cybersecurity Framework 2.0 — *Respond & Recover Functions*
3. Republic Act No. 10173 — *Data Privacy Act of 2012*
4. NPC Circular 16-03 — *Personal Data Breach Management*
5. Republic Act No. 10175 — *Cybercrime Prevention Act of 2012*
6. Verizon. (2023). *Data Breach Investigations Report (DBIR)*
7. SANS Institute. (2023). *Incident Handler's Handbook*
8. ISO/IEC 27035 — *Information Security Incident Management*
9. PICPA Code of Ethics for Professional Accountants
10. BSP Circular No. 982 — *Enhanced Guidelines on IT Risk Management*

---

*Module 3: Incident Reporting & Response · Data Security · SY 2025–2026 2nd Semester · For Accounting Students*
