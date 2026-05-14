# Succession Planning for Civic Data Efforts

The efforts that survive aren't run by heroes. They're run by people who made themselves replaceable on purpose.

---

## ⚠️ Before You Read Further: Secure This Document

This document tells someone where your data lives, who has the keys, and how your operation is structured. In the wrong hands, it is a map for dismantling everything you built.

**This document must be:**
- Stored encrypted, not in plain text on a shared drive or email thread
- Accessible to a small, explicitly named group of trusted individuals only
- Stored in at least two independent locations so one person's absence doesn't lock everyone out
- Never printed unless that copy is controlled and can be destroyed

**Recommended storage:**
- [CryptPad](https://cryptpad.fr) -zero-knowledge encrypted, no account required for contributors, self-hostable
- A password manager with shared vault access (Bitwarden, 1Password Teams)
- An encrypted local file (VeraCrypt) with copies held by two people in separate locations

**Who has access to this document right now?**

| Name | Contact (secure channel) | Date Given Access |
|------|--------------------------|-------------------|
| | | |
| | | |
| | | |

Review this list every time someone joins or leaves the core team. Revoke access when someone exits -not later, immediately.

---

Sustainability is the silent killer of civic tech. Most efforts don't end because the mission failed -they end because the people carrying them burned out, moved on, or faced pressure they couldn't absorb alone. This document helps you plan for that before it happens.

Fill this out **before** you need it. Once you're in a forced shutdown or crisis moment, you won't have time to think clearly about what should be preserved and what should be destroyed.

---

## Part 1: Know What You Have

Before you can hand anything off, you need to know what exists.

### Data Assets

| Asset | Location | Format | Sensitivity Level | Retention Decision |
|-------|----------|--------|------------------|--------------------|
| Raw submissions | | | | Keep / Aggregate / Destroy |
| Verified dataset | | | | Keep / Aggregate / Destroy |
| Contact lists | | | | Keep / Aggregate / Destroy |
| Contributor records | | | | Keep / Aggregate / Destroy |
| Internal communications | | | | Keep / Aggregate / Destroy |
| Published reports | | | | Keep / Aggregate / Destroy |

**Sensitivity levels:** Public / Internal Only / Restricted / Destroy on Exit

### Infrastructure & Accounts

| Service | URL / Location | Who Has Access | Credentials Stored Where |
|---------|---------------|----------------|--------------------------|
| Data storage | | | |
| Submission platform | | | |
| Communication channel | | | |
| Domain / hosting | | | |
| Archiving system | | | |
| Payment / funding account | | | |

---

## Part 2: Know Who Carries What

Single points of failure are the enemy. For each critical function, there should be at least two people who can do it.

### Role Map

| Function | Primary | Backup | Backup Knows They're Backup? |
|----------|---------|--------|------------------------------|
| Data access & admin | | | Yes / No |
| Contributor communication | | | Yes / No |
| Security & credentials | | | Yes / No |
| Public communications | | | Yes / No |
| Legal / institutional contact | | | Yes / No |
| Funding / financial | | | Yes / No |

**If any row has no backup, that's your highest risk item. Fix it first.**

### Credential Inventory

Do not store passwords here. This is a map of *where* credentials live, not what they are.

| System | Credential Type | Stored In | Who Can Access |
|--------|----------------|-----------|----------------|
| | Password | Password manager / Signal note / Physical key | |
| | API key | | |
| | Signing key | | |
| | 2FA recovery codes | | |

---

## Part 3: Plan for Three Scenarios

### Scenario A: Orderly Wind-Down
*Mission accomplished, funding exhausted, or planned transition.*

- [ ] Data retention decisions made and documented (see Part 1)
- [ ] Community trust transfer plan: who is the next trusted contact for contributors?
- [ ] Public acknowledgment plan: how does the community know the effort ended and why?
- [ ] Archival handoff: does data go to a long-term institutional steward?
- [ ] Who inherits the institutional knowledge? Is there a debrief or handoff document?

**Designated successor or steward organization:**
`_______________________________________________`

**Timeline for wind-down:**
`_______________________________________________`

---

### Scenario B: Forced Shutdown
*Legal action, platform takedown, political pressure, or sudden external threat.*

This scenario requires decisions made **in advance** because you may have hours, not days.

**Pre-decided answers to the hard questions:**

What gets preserved?
`_______________________________________________`

What gets destroyed immediately?
`_______________________________________________`

Who makes the call to activate this plan?
`_______________________________________________`

Who else needs to be notified, and in what order?

| Person / Organization | Contact Method | Time Limit to Notify |
|-----------------------|---------------|----------------------|
| | | |
| | | |
| | | |

Where does the data go if you lose your primary infrastructure?
`_______________________________________________`

Do you have a legal contact pre-established? Name / org:
`_______________________________________________`

---

### Scenario C: Organizer Attrition
*Key people burn out, leave, or are unavailable -the most common failure mode.*

**Signs to watch for (assign someone to watch for these):**
- One person is handling more than two critical functions
- Response times from core team are slipping
- Someone hasn't taken a real break in [X weeks — define your threshold]
- A contributor or organizer has gone quiet without explanation

**Your rotation plan:**

How often do you actively check in on team capacity?
`_______________________________________________`

Who is responsible for noticing when someone is carrying too much?
`_______________________________________________`

What's the process for someone to step back without the effort collapsing?
`_______________________________________________`

**Don't be the last person standing. Make yourself replaceable on purpose.**

---

## Part 4: What Community Trust Looks Like

Data is not the only thing worth preserving. Contributors trusted you. That trust doesn't automatically transfer.

- Who are your most trusted contributors, and do they know who to contact if you're gone?
- Is there a way for contributors to find the successor effort without your personal involvement?
- If the effort ends, do contributors know what happened to their data?

Document your community handoff plan:
`_______________________________________________`

---

## Part 5: Review Schedule

This document is useless if it's out of date when you need it.

| Review Trigger | Action |
|----------------|--------|
| New person joins core team | Update role map and credential access |
| Person leaves core team | Rotate credentials, update role map |
| Platform or infrastructure change | Update asset inventory |
| Every [X months — define it] | Full review of all sections |
| After any security incident | Review and update threat assumptions |

**Last reviewed:**
`_______________________________________________`

**Reviewed by:**
`_______________________________________________`

**Next scheduled review:**
`_______________________________________________`

---

## Quick Reference: When Something Goes Wrong

If you're reading this under pressure, start here.

1. **Someone was arrested or compromised** → Rotate all credentials they had access to. Notify backup contacts via pre-established secure channel. Do not use potentially compromised infrastructure.

2. **Platform deleted your data or account** → Activate backup archive. Notify contributors via secondary channel. Do not rebuild on the same platform without understanding why it happened.

3. **Legal order or pressure received** → Contact pre-established legal contact before responding to anything. Do not delete data under pressure without legal guidance — this can create liability.

4. **Key organizer is suddenly unavailable** → Backup for their role activates. No heroics, no single person absorbs everything. The plan exists for this reason.

5. **You're burned out and can't continue** → You planned for this. Hand the role map to your backup. This is not failure -this is the plan working.

---

