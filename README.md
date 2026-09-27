# Awesome-Emergency-Alerting

# Top Emergency Alerting Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Mass Notification, Crisis Communication, Incident Response & Public Warning Systems*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Emergency Alerting**. These tools help organizations, government agencies, and public safety teams send mass notifications, manage critical events, and coordinate multi-channel emergency communications across SMS, email, voice, push, and broadcast channels.

**Examples** include Everbridge, AlertMedia, OnSolve, Rave Mobile Safety, BlackBerry AtHoc, Regroup, Omnilert, Singlewire InformaCast, Hyper-Reach, and Preparis (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom alerting workflows, and transparent crisis communication — ideal for organizations that need full control over their emergency notification infrastructure without per-contact SaaS fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Everbridge](https://www.everbridge.com/)**
  The leading critical event management platform. Provides mass notification, incident management, and risk intelligence with multi-channel delivery (SMS, voice, email, push, desktop alerts). Used by enterprises and government agencies worldwide.

- **[AlertMedia](https://www.alertmedia.com/)**
  Emergency communication and threat intelligence platform. Provides two-way messaging, employee safety check-ins, and multi-channel alerting with a focus on ease of use.

- **[OnSolve](https://www.onsolve.com/)**
  Critical communication and risk intelligence platform. Combines mass notification, incident management, and threat intelligence into a unified system for enterprise and government.

- **[Rave Mobile Safety](https://www.ravemobilesafety.com/)**
  Public safety and emergency notification platform. Provides mass notification, panic button apps, and 911 integration for campuses, healthcare, and government agencies.

- **[BlackBerry AtHoc](https://www.blackberry.com/)**
  Secure crisis communication platform for government and defense. Provides mass notification, accountability, and interoperable alerting with FedRAMP authorization.

- **[Regroup](https://www.regroup.com/)**
  Mass notification and emergency communication platform. Provides SMS, voice, email, and push alerting for universities, healthcare, and enterprises.

- **[Omnilert](https://www.omnilert.com/)**
  Emergency notification and mass communication platform. Provides multi-channel alerting, threat detection, and integrated emergency response.

- **[Singlewire InformaCast](https://www.singlewire.com/)**
  Emergency notification and mass communication platform with deep Cisco integration. Provides IP speaker, desktop, and mobile alerting for campuses and enterprises.

- **[Hyper-Reach](https://www.hyper-reach.com/)**
  Mass notification platform for government agencies and public safety. Provides emergency alerts, weather warnings, and community notifications.

- **[Preparis](https://www.preparis.com/)**
  Emergency notification and crisis management platform. Provides mass notification, incident management, and business continuity planning.

## Open-Source GitHub Projects

- **[Resgrid Core](https://github.com/Resgrid/Core)**
  The most complete open-source emergency management platform. Powers Resgrid.com with hosted and self-hosted options. Features **Computer Aided Dispatch** (manual and automatic), personnel management with certifications and roles, unit support with AVL and logging, duty shift system with swap/trade support, learning management, inventory tracking, document storage, department linking for mutual aid, and a built-in **messaging and notification system** for targeted and dynamic communications to personnel. Native mobile apps for Personnel, Units, Stations, and Commanders. **Apache 2.0**. ~131 stars .

- **[EAS Station](https://hub.docker.com/r/kr8mer/eas-station)**
  Comprehensive open-source Emergency Alert System (EAS) software stack designed for broadcasters, emergency communications professionals, and public safety organizations. Replaces legacy EAS hardware with a flexible, containerized platform. Features **CAP (Common Alerting Protocol) feed ingestion** from NOAA, IPAWS, and other public alert sources, **SAME (Specific Area Message Encoding) tone generation and relay**, audio synthesis and relay control, multi-channel output to web dashboards, LED signs, GPIO, MQTT, and radio gateways. Integrated PostgreSQL + PostGIS database for geospatial alert storage. Docker Compose deployment. Runs on Raspberry Pi-class devices and standard Linux servers .

- **[Emergency Notification System](https://github.com/inwall-ch/emergency-notification-system)**
  Laravel-based emergency notification system for sending SMS, email, and Telegram alerts. Users can upload contacts via CSV, create message templates, and send notifications to all recipients with one button. Integrates with Twilio (SMS), Google SMTP (email), and Telegram. Tracks delivery status per user. PHP/Laravel stack. ~4 stars .

- **[SteeperMold Emergency Notification System](https://github.com/SteeperMold/Emergency-Notification-System)**
  Scalable, fault-tolerant SMS notification system designed for **million-recipient scale**. Microservices architecture with React frontend, Go API service, Kafka message queue, PostgreSQL for status tracking, and S3 for file storage. Features delivery guarantees (at-least-once), retry logic via Rebalancer service, Twilio callback processing for delivery confirmation, and horizontal scaling. Tested at **1,000,000 recipients**. Docker Compose deployment with Grafana monitoring. **Open source** .

- **[Brgy.Tanod-S.O.S](https://github.com/MiB1968/Brgy.Tanod-S.O.S)**
  Offline-first, PWA-first SOS alert system for Philippine barangays. Connects citizens directly to local responders with reliable performance in low-connectivity and typhoon-prone areas. Features floating SOS button with long-press activation, real-time responder tracking with live location and heatmap, **offline-first SOS with queued alerts and auto-sync**, multi-channel fallback (Firebase + Twilio SMS during outages), and **AI Guardian Mode** with voice-activated SOS in Tagalog/English powered by local WebLLM (privacy-first, works offline). React 19, TypeScript, Firebase, Twilio, Leaflet maps. PWA + Capacitor-ready. **Open source** .

- **[mowas-pwb](https://github.com/joergschultzelutter/mowas-pwb)**
  MOWAS Personal Warning Beacon — MeetKATWARN's open-source sibling. Sends emergency broadcasts from Germany's Modular Warning System to email and every messenger supported by Apprise (Telegram, Signal, etc.). Monitors static lat/lon coordinates for MOWAS events. Supports dynamic position monitoring via APRS for licensed ham radio operators. Users specify minimal warning level for alerts. Emergency alerts can be sent to specific clients with high priority. Automatically switches to shorter emergency intervals during active alerts. Optional OpenAI/Google PaLM summarization for verbose German warning text. Automatic translation to native language. Runs on Raspberry Pi .

- **[FOSS Warn](https://github.com/nucleus-ffm/foss_warn)**
  Open-source emergency and weather alert app. Monitors warnings from multiple government sources including Germany's NINA and BIWAPP, and provides worldwide disaster alerts via alerts.kde.org. Based on OASIS Common Alerting Protocol (CAP). Client infrastructure shipped with KDE Gear. Supports self-hosted and KDE infrastructure push notifications via UnifiedPush. Part of the broader KDE emergency alerting ecosystem .

- **[Scribe](https://github.com/nocomp/scribe)**
  Open-source hospital crisis management platform. Multi-site, multi-language architecture with GDPR and French HDS compliance. Each facility runs independent SCRIBE instance with local database — patient data never leaves the facility. Master collector aggregates only non-nominative indicators (incidents, capacity tension, transfer counts). FastAPI backend, SQLite per instance, Leaflet maps with ambulance routing, optional AI (French government LLM). Docker or direct Python deployment. **Open source** .

- **[OpsKnight](https://github.com/opsknight-labs/OpsKnight)**
  Complete open-source platform for on-call management, incident response, and status pages. While focused on DevOps/SRE workflows, its **notification and escalation engine** can be adapted for emergency alerting. Features Slack ChatOps integration, native inbound parsers (Prometheus, Datadog, Nagios, Icinga), RBAC-governed schedules, and encrypted integration secrets. Next.js application with PostgreSQL backend. Helm charts for Kubernetes deployment. **Open source** .

### Additional Strong Open-Source Options

- **Notification Infrastructure**: **Novu** (20k+ GitHub stars, self-hosted notification infrastructure with SMS, email, push, chat, and in-app channels; workflow engine with digest and batching; TypeScript-first) .
- **Self-Hosted Push**: **ntfy** (HTTP-based pub-sub push notifications, UnifiedPush distributor, supports iOS via relay), **Gotify** (lightweight Go-based push server with Android app), **Apprise** (Python library supporting 100+ notification services) .
- **Incident Management**: **OpsKnight** (on-call + incident response + status pages), **incident-response-bot** (Slack-based incident reporting with automated channel creation) .
- **Broadcast EAS**: **EAS Station** (CAP/SAME ingestion, audio synthesis, multi-channel output) .

**Frameworks for building custom systems**: Combine **Resgrid Core** for the complete emergency management and dispatch platform, **EAS Station** for broadcast-level alerting with CAP/SAME, **SteeperMold Emergency Notification System** for million-scale SMS delivery, **Novu** for multi-channel notification routing, and **ntfy** or **Gotify** for self-hosted push. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Emergency alerting platforms handle life-critical communications; ensure proper testing, redundancy, and compliance with local emergency communication regulations before production deployment.
- Self-hosted open-source solutions require proper security hardening, network isolation, and regular maintenance. For mission-critical emergency use, consider hybrid approaches with commercial backup systems.

---

**Made for emergency managers, public safety professionals, campus security teams, and crisis communication specialists.**
Let's make emergency alerting more open, resilient, and accessible.
