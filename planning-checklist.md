## The Planning Checklist

Before launching any crowd-sourced civic data effort, work through these questions with your team. They are not sequential; the tensions between them are features, not bugs.

### Before You Start
- [ ] What specific question are we answering? (Not "document everything" but "what happened, where, when?")
- [ ] Does someone already collect this data? Can we join them instead?
- [ ] Who are the domain experts and legal advocates already in this space?
- [ ] What is our "minimum viable deployment" and how do we iterate?

### Speed
- [ ] What is the simplest submission channel that works in our threat environment?
- [ ] How much verification can we do at the speed we need?
- [ ] Have we defined the minimum viable data point (fields, geography, time window)?
- [ ] Do we have a tiered publication model (raw vs. verified, clearly labeled)?

### Safety
- [ ] Who are our adversaries and what are their capabilities?
- [ ] What is the MINIMUM data we need to collect?
- [ ] Are we stripping metadata at point of ingestion?
- [ ] Have we reduced location precision to what our analysis actually needs?
- [ ] What happens when a contributor or organizer is compromised?
- [ ] Have we pre-established backup communication channels?
- [ ] What are our legal exposures in relevant jurisdictions?
- [ ] Could this data harm the people it describes?

### Trust & Verification
- [ ] Which verification model fits our speed and consequence tolerance?
- [ ] How do we detect bot flooding and false reports?
- [ ] Do we have multi-source corroboration requirements?
- [ ] Are we accounting for geographic, demographic, survivorship, reporting, and platform biases?

### Resiliency
- [ ] Does our data live on infrastructure we control?
- [ ] How distributed is our architecture?
- [ ] What is our plan for internet shutdowns?
- [ ] How do we handle platform content moderation being weaponized against us?
- [ ] What is our plan for infiltration and trust gaming?

### After Collection
- [ ] Who benefits from this data? Who controls access?
- [ ] What are our retention policies?
- [ ] How do we publish responsibly (aggregate, anonymize, delay)?
- [ ] What legal obligations does this data create?

### Exit Planning
- [ ] Orderly wind-down: Who inherits the data?
- [ ] Forced shutdown: What gets preserved vs. destroyed?
- [ ] Organizer compromise: Who has backup credentials? What's the succession plan?


---

## Quick-Start Decision Matrix

**How much time do you have?**

| Timeframe | Approach |
|-----------|----------|
| Hours | Deploy Ushahidi Crowdmap, set up a verified Signal group, define 3-5 structured fields |
| Days | Stand up a KoBoToolbox survey, train 10-20 trusted monitors, establish verification protocols |
| Weeks | Build a full platform with tiered verification, independent archiving, and distributed infrastructure |
| Ongoing | Establish organizational structure, legal framework, succession planning, and long-term data governance |

**What's your threat level?**

| Threat Level | Security Posture |
|-------------|-----------------|
| Low (public accountability) | Standard web forms, organizational accounts, basic access controls |
| Medium (potential legal exposure) | Encrypted channels, metadata stripping, role-based access, legal counsel |
| High (state-level adversary) | SecureDrop/Tor-based submission, air-gapped archives, compartmentalized knowledge, operational pseudonyms |

---
