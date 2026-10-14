# Awesome-Board-Resolution-Governance-Management

## Top Board Resolution & Governance Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Board Portals, Resolution Workflows & Minute Automation*

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Board Resolution & Governance Management**. These tools enable corporate secretaries, board administrators, and governance teams to compile meeting logs into legal minutes, manage resolutions and voting workflows, and maintain audit-ready governance records.



**Examples** include Diligent Boards, OnBoard, Boardable, Govenda, Aprio, Azeus Convene, BoardEffect, Nasdaq Boardvantage, BoardPAC, and Passageways (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, cryptographic document integrity, and open governance workflows—ideal for corporate secretaries, associations, and developers seeking transparent, vendor-independent board management.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Diligent Boards](https://www.diligent.com/)**

  The dominant board portal platform with roughly 40% market share. Purpose-built for enterprise governance at public companies, large financial institutions, and complex multi-entity organizations. Features agenda and board book creation, secure document distribution, annotations, voting/e-signatures, minutes, action tracking, and AI summaries. Built on proprietary software stack—Diligent does not use third-party software like Adobe Acrobat at critical points, enabling better security and seven-day support . Trade-off: enterprise pricing, complexity, and platform breadth that smaller boards may not need .



- **[OnBoard (Passageways)](https://www.onboardmeetings.com/)**

  Second-largest board portal with roughly 20% market share. Cleaner, more intuitive interface than Diligent with strong document management and faster onboarding. Targets mid-market to enterprise segment at generally lower pricing. Acquired BoardEffect in 2023, expanding into nonprofit sector .



- **[Boardable](https://boardable.com/)**

  Transparent public pricing, simplified interface, and focus on smaller organizations. Covers agenda creation, document sharing, voting, and basic meeting management without enterprise governance overhead. Best for small to mid-size organizations wanting straightforward functionality .



- **[Govenda](https://govenda.com/)**

  Board management and online portal for boards of directors. Designed for mid-market to large organizations with focus on user experience and ROI.



- **[Aprio](https://www.aprio.com/)**

  Complete board portal helping organizations manage board meetings and board communication with optimal security and service.



- **[Azeus Convene](https://www.azeusconvene.com/)**

  Grown international presence, particularly in Asia-Pacific and Europe. Clean interface, paperless meeting features, and competitive pricing relative to Diligent. Strong for organizations with international boards requiring multi-language support and global data centers .



- **[BoardEffect](https://www.boardeffect.com/)**

  Now part of the OnBoard family. Purpose-built for mission-driven organizations: nonprofits, healthcare systems, higher education institutions, and associations. Feature set focuses on committee management, document workflows, and engagement tracking tailored to how nonprofit boards operate .



- **[Nasdaq Boardvantage](https://www.nasdaq.com/solutions/boardvantage)**

  For publicly traded companies already in the Nasdaq ecosystem. Board management with built-in compliance features. Nasdaq brand carries weight in financial services and with publicly listed companies .



- **[BoardPAC](https://www.boardpac.com/)**

  Board portal and paperless meeting software designed for board management process improvement, collaboration, and corporate governance.



- **[Passageways](https://www.passageways.com/)**

  Parent company of OnBoard, providing board management software for boards and leadership teams.



## Open-Source GitHub Projects



- **[EasyBoard](https://vibecode.law/showcase/easyboard-547268)**

  The first AI-native board management platform—open source and self-hosted. Built by a practising lawyer with zero engineering background, demonstrating practitioner-designed governance tooling. **Upload a document and the AI classifies it, extracts key data, and proposes next actions** (create a meeting, start a vote, assign a task)—with **human-in-the-loop approval queue** ensuring nothing executes without Secretary review. Features **7 document types recognized** (draft minutes, resolutions, financial reports, evidence/deliverables, meeting agendas, legal opinions, general documents), **full voting workflow** with 4 options and custom approval rules (unanimous, majority, two-thirds, quorum), **secret ballot** visible only to Secretary and voter, **minutes lifecycle with SHA-256 integrity hashes**, **per-document access control** for conflict-of-interest recusal, **4 role types** (Secretary, Board Member, Management, Observer), natural language command bar, and full audit trail. Built with Replit and Claude through 12 rounds of security auditing .



- **[Decidiq](https://github.com/ConductionNL/decidiq)**

  Universal decision-making platform for governance bodies, associations, corporate boards, and operational meetings (EUPL-1.2). Serves **5 governance domains**: legislative/democratic bodies, associations/NGOs, corporate governance, corporate operations, and citizen participation. Features **meeting management** with agendas, motions, amendments, voting, and minutes. **Configurable workflows per organization type** with decision tracking. Built as a **Nextcloud app** with OpenRegister integration. Features **AI Chat Companion (MCP Tools)** exposing 5 governance tools: list action items, list recent meetings, get meeting details, start meeting, add action items. **RBAC via OpenRegister**, **full change history audit trail** on all objects, WCAG AA accessibility (Dutch government requirement), and English/Dutch localization. Tech stack: Vue 2.7, PHP 8.1+, Nextcloud 28-33, OpenRegister (PostgreSQL JSON objects) .



- **[GovernanceOS](https://github.com/)**

  Open-source platform for managing a global portfolio of legal entities (MIT). **Built for compliance and legal teams at regulated financial institutions**. Features **entity registry** with parent/subsidiary hierarchy, **director management and tenure tracking**, **board meeting scheduling with quorum tracking and minutes**, **license expiry alerts**, **regulatory capital monitoring**, and **AI-powered Terms of Reference generator** producing jurisdiction-aware governance documents for 10 countries. **Nium uses this across 28 entities and all our licenses**. Ships with a **CLAUDE.md file**—clone the repo, open it in Claude Code, type "set this up for me" and Claude handles database, migrations, and seed data automatically .



- **[Loomio](https://github.com/loomio/loomio)**

  Collaborative decision-making tool for group discussions, proposals, and polls (AGPL-3.0, 2.5k+ GitHub stars). Helps teams make transparent decisions asynchronously with a clear record. Features **threaded discussions** designed for group deliberation, **proposals and multiple polling/voting methods** (including ranked choice and score voting), **time polls** for meeting scheduling, **email participation** for inbox-preferring members, **export of group history and data** (CSV/HTML/JSON), and **API integrations** for threads, polls, and memberships. Best for board or cooperative governance decisions with documented outcomes, remote team decision-making, and community consultations. Some enterprise features (SSO) may depend on deployment or product tier .



- **[Ackify](https://github.com/)**

  Self-hosted proof-of-read platform (MIT). Records **cryptographic acknowledgements** when users read or accept documents. Features **Ed25519 cryptographic signatures** for irrefutable per-user/per-document acknowledgements, **document checksum support** (SHA-256/512, MD5) for tamper detection, **flexible authentication** (OAuth2: Google/GitHub/GitLab/custom, MagicLink passwordless email), **one signature per user/document** enforced at database level, **immutable audit trail** built on PostgreSQL with triggers and timestamping, **expected signers management** with email reminders and sign status tracking, **public embeddable widgets** for Notion/Outline integration, and **admin dashboard** (Vue 3). Proves employee acknowledgement of security policies, codes of conduct, and training attestations for compliance audits. Note: focuses on proof-of-read acknowledgements rather than full legal e-signature workflows .



- **[Antragsgrün (Motion.Tools)](https://github.com/)**

  Web application for NGOs, political parties, and assemblies to collaboratively submit, discuss, and decide on motions, resolutions, and amendments (AGPL-3.0, actively maintained). Features **structured amendment workflow** allowing submission, discussion, and merging of accepted amendments, **voting workflows** including roll calls and configurable vote procedures, **speaking lists and full-screen projector views** for in-person assemblies, **export options** (PDF, spreadsheets, text templates), **user management with roles** and configurable submission policies, **security features** (CAPTCHA throttling, optional TOTP-based 2FA, SSO integrations), **WCAG AA accessibility**, and **Docker-friendly deployment**. Designed for congresses with large numbers of motions and amendments, policy document adoption, and managing speaking order and roll calls during assemblies. Requires PHP >=8.1 and MySQL/MariaDB .



### Additional Strong Open-Source Options



- **[Archive Agenda & Minutes](https://wordpress.org/plugins/archive-agenda-minutes/)** — WordPress plugin (GPL v2+) for managing and organizing meeting agendas and minutes directly within a WordPress site. Features meeting creation, customizable templates, AJAX-powered year filtering, and shortcode display. **Note**: Not tested with latest 3 major WordPress releases—may have compatibility issues .

- **[zorak1103/notebook](https://hub.docker.com/r/zorak1103/notebook)** — Meeting and Notes Management Application with Tailscale integration and optional LLM-powered summaries. Features internationalization (German, English, French, Spanish), meeting management, notes system with automatic numbering and manual reordering, full-text search, LLM integration (OpenAI, Anthropic, Ollama, LM Studio, vLLM), and single binary with embedded frontend .

- **[Probo](https://github.com/getprobo/probo)** — Open-source GRC platform for engineers (MIT). Covers full GRC lifecycle including **document management** with versioned documents, approval quorums, electronic signatures, and PDF export. **270+ MCP tools** expose every entity for AI agent integration. **Immutable audit logs**, policy-based RBAC, and evidence chains. Self-hostable with Docker. Includes **n8n community node** for no-code automation .

- Community **n8n** workflows for board meeting scheduling automation and resolution tracking alerts.



**Frameworks for building custom systems**: Combine **EasyBoard** for AI-powered document classification and voting workflows with **Decidiq** for full decision-making lifecycle management, **GovernanceOS** for multi-entity governance and regulatory tracking, **Ackify** for cryptographic document acknowledgements, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade board resolution management platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Board governance systems handling corporate records must comply with applicable corporate law, securities regulations, and data protection requirements.

- **Open-source board portals are early-stage but promising.** EasyBoard and GovernanceOS are recent projects (2026) built by practitioners—EasyBoard by a lawyer, GovernanceOS by a fintech operator. They demonstrate the art of the possible but require security hardening and production validation before board use. Decidiq is more mature with Nextcloud integration and WCAG AA accessibility .

- **Cryptographic integrity matters for governance records.** EasyBoard uses SHA-256 integrity hashes for minutes , Ackify uses Ed25519 signatures for document acknowledgements , and Probo provides immutable audit logs . These features provide tamper-evidence that paper-based governance cannot match.

- **AI-assisted governance requires human oversight.** EasyBoard's human-in-the-loop approval queue ensures nothing executes without Secretary review . AI can classify documents, extract data, and propose actions—but board decisions and legal minutes remain human responsibilities.

- Self-hosted open-source solutions require proper security hardening, database administration, and ongoing maintenance. Board materials are highly confidential—access controls, encryption, and audit trails are essential.



---



**Made for corporate secretaries, board administrators, governance professionals, and developers building transparent board management solutions.**

Let's make Board Resolution & Governance Management more open, data-driven, and cryptographically verifiable.
