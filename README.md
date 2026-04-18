# Crowd-Sourced-Truth
When official narratives don't match what communities are seeing on the ground, grassroots organizations turn to crowd-sourced data to fill the gaps. But good intentions alone don't produce reliable data. This repo provides resources to plan and execute a community driven data collection effort.


# Crowd-Sourced Truth: Resource Guide

**A companion to the talk "Crowd-Sourced Truth: A Framework for Community Data Collection in Hostile Environments"**

---

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

## Open Source Repos & Tools

### Crisis Mapping & Data Collection
| Project | What It Does | Link |
|---------|-------------|------|
| **Ushahidi Platform** | Crowdsourced crisis mapping via SMS, web, email, social media | github.com/ushahidi |
| **PYBOSSA** | Crowdsourcing framework for data that can't be processed by machines alone | github.com/Scifabric/pybossa |
| **Shareabouts** | Location-aware crowdsourcing for community input | github.com/openplans/shareabouts |
| **HOT Tasking Manager** | Humanitarian OpenStreetMap Team's task management for volunteer mapping | github.com/hotosm/tasking-manager |
| **KoBoToolbox** | Open-source data collection for challenging environments | github.com/kobotoolbox |
| **ODK (Open Data Kit)** | Mobile data collection for offline-capable field surveys | github.com/getodk |

### OSINT & Verification
| Project | What It Does | Link |
|---------|-------------|------|
| **Bellingcat Investigation Toolkit** | Curated tools for open-source investigations | bellingcat.gitbook.io/toolkit |
| **Bellingcat GitHub** | Open-source tools built by Bellingcat | github.com/bellingcat |
| **awesome-osint** | Massive curated list of OSINT tools and resources | github.com/jivoi/awesome-osint |
| **Verification Handbook** | Guides for verifying digital content (multiple editions) | verificationhandbook.com |

### Secure Communication & Submission
| Project | What It Does | Link |
|---------|-------------|------|
| **SecureDrop** | Whistleblower submission system (on-premises, Tor-based) | github.com/freedomofpress/securedrop |
| **Signal Protocol** | End-to-end encrypted messaging protocol | github.com/signalapp |
| **OnionShare** | Secure file sharing, hosting, and chat via Tor | github.com/onionshare/onionshare |
| **Briar** | Peer-to-peer encrypted messaging that works without internet | briarproject.org |

### Archiving & Preservation
| Project | What It Does | Link |
|---------|-------------|------|
| **Mnemonic (Syrian/Ukrainian/Yemeni/Sudanese Archives)** | Conflict documentation and digital evidence preservation | mnemonic.org |
| **Wayback Machine / Internet Archive** | Web archiving | archive.org |
| **Webrecorder** | High-fidelity web archiving tools | webrecorder.net |
| **youtube-dl / yt-dlp** | Download and preserve video content | github.com/yt-dlp/yt-dlp |

### Metadata & Privacy
| Project | What It Does | Link |
|---------|-------------|------|
| **ExifTool** | Read, write, and strip metadata from files | exiftool.org |
| **MAT2** | Metadata removal tool | gitlab.com/mat2 |
| **Tails OS** | Portable operating system for privacy and anonymity | tails.net |
| **Tor Browser** | Anonymous web browsing | torproject.org |

### Civic Tech & Data Governance
| Project | What It Does | Link |
|---------|-------------|------|
| **awesome-civic-tech** | Curated list of civic tech projects and tools | github.com/awesomelistsio/awesome-civic-tech |
| **CivicStack** | Repository of open-source civic tools from many countries | github.com/CivicStack/civicstack |
| **Open Civic Data** | Standards for civic data interoperability | github.com/opencivicdata |

---

## People & Organizations to Follow

### Organizations
| Organization | Focus | Where to Find Them |
|-------------|-------|-------------------|
| **Bellingcat** | Open-source investigations, OSINT methodology | bellingcat.com / Discord community |
| **Mnemonic** | Digital evidence preservation for conflict zones | mnemonic.org |
| **Witness** | Video as evidence for human rights | witness.org |
| **Access Now** | Digital rights, emergency response for activists | accessnow.org |
| **EFF (Electronic Frontier Foundation)** | Digital rights, surveillance self-defense | eff.org / ssd.eff.org |
| **Tactical Tech** | Privacy, digital security for activists | tacticaltech.org |
| **Freedom of the Press Foundation** | SecureDrop, press freedom tools | freedom.press |
| **Centre for Information Resilience** | Open-source monitoring, Ukraine Map | info-res.org |
| **Humanitarian OpenStreetMap Team** | Crisis mapping and volunteer coordination | hotosm.org |
| **Human Rights Center, UC Berkeley** | Berkeley Protocol, digital evidence standards | humanrights.berkeley.edu |
| **Citizen Lab (U of Toronto)** | Surveillance, spyware, internet censorship research | citizenlab.ca |
| **Data & Society** | Research on data-driven social impacts | datasociety.net |

### Key Researchers & Practitioners
| Person | Area | Affiliation |
|--------|------|-------------|
| **Eliot Higgins** | OSINT methodology, open-source investigations | Bellingcat founder |
| **Kate Starbird** | Crisis informatics, misinformation | University of Washington |
| **Leysia Palen** | Crisis informatics, collective intelligence | CU Boulder |
| **Hadi al Khatib** | Digital evidence preservation | Mnemonic / Syrian Archive |
| **Patrick Meier** | Crisis mapping, humanitarian technology | WeRobotics |
| **Latanya Sweeney** | Data privacy, re-identification research | Harvard |
| **Johanna Wild** | OSINT tool development | Bellingcat / Harvard Nieman Fellow |
| **Ory Okolloh** | Crowdsourced crisis response | Ushahidi co-founder |
| **Sam Gregory** | Video as evidence, deepfakes and human rights | Witness |
| **Eva Galperin** | Digital security, anti-stalkerware | EFF |

---

## Case Study Reading List

### Foundational Cases
- **Ushahidi & Kenya 2008**: "Open Source for Humanitarian Action" (Stanford Social Innovation Review)
- **Safecast & Fukushima 2011**: safecast.org/about - citizen radiation monitoring at scale
- **Bellingcat & MH17**: The multi-year investigation that traced the Buk missile to Russia's 53rd Brigade
- **Syrian Archive**: "Digital Memory, Evidence, and Social Media" (Sociologica, University of Bologna)

### Recent Cases
- **Ukraine OSINT 2022-present**: "How OSINT shaped reporting on the war in Ukraine" (Centre for Information Resilience)
- **Belarus 2020**: Golos ballot photo platform and the "first Telegram revolution" (Euromaidan Press)
- **Iran 2022**: Azadi Archive - 1M+ protest videos despite internet shutdowns (Atlantic Council)
- **US ICE tracking 2025**: Community rapid response networks and crowd-sourced enforcement monitoring

### Failure Cases
- **Boston Marathon Reddit investigation**: The canonical warning about crowd-sourced witch hunts
- **YouTube/Syria video deletions**: 200K+ conflict videos removed by automated moderation
- **Strava heatmap**: Fitness data exposing military installations worldwide
- **Bridgefy app**: Mesh networking app adopted in HK/Belarus protests lacked real security

---

## Academic & Framework References

### Standards & Protocols
- **Berkeley Protocol on Digital Open Source Investigations** (2020) - UC Berkeley HRC / UN OHCHR - First international standards for digital OSINT as legal evidence
- **CARE Principles for Indigenous Data Governance** (Carroll et al., 2020) - Collective Benefit, Authority to Control, Responsibility, Ethics
- **FAIR Data Principles** - Findable, Accessible, Interoperable, Reusable

### Key Research
- **Starbird et al.** - Misinformation dynamics during crisis events (rumor propagation faster than correction)
- **Sweeney (2000)** - Re-identification: 87% of Americans from ZIP + birthdate + gender
- **Fang et al. / Miao et al.** - Crowdsourcing under data poisoning attacks (adversarial robustness)
- **Wiggins et al. (2011)** - 18 mechanisms for citizen science data quality validation
- **Hargittai (2020)** - "Potential Biases in Big Data: Omitted Voices on Social Media" (Social Science Computer Review)

### Guides & Handbooks
- **EFF Surveillance Self-Defense** - ssd.eff.org - Practical digital security for activists
- **Tactical Tech Security in a Box** - securityinabox.org - Digital security tools and tactics
- **ICRC: The Mosaic Effect** - Revelation risks of combining humanitarian and social data
- **Verification Handbook** - verificationhandbook.com - Multiple editions on digital content verification

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

*"The death of truth is the ultimate victory of evil."*
