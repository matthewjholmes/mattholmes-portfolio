---
layout: page
icon: fas fa-code
order: 2
---

Here’s a selection of projects I’ve built to solve problems, explore new technologies, and sharpen my skills. These range from personal tools to collaborative efforts, with a focus on learning, resilience, and thoughtful design.

---
<div class="d-flex justify-content-between align-items-baseline flex-wrap mb-2">
  <h2 id="runa">Runa</h2>
  <em class="text-end" style="font-size: 1.25rem;">Book-based encryption</em>
</div>

An encryption app with a suite of tools that uses published books as the code references. Offers one-time pad–style, arbitrary code-word, and matrix-based encryption models. Designed for use even without a computer, Runa parses and indexes a source text to encode and decode messages using accurate page, line, and word references.

- Parses PDFs with pagination normalization (including detection of Roman numerals, forwards, indices, etc.).
- Indexes for consistent, performant message encryption and decryption.
- Explores codebook security models and low-tech cryptography.

[Runa web application](https://runa.run)<br>
[Runa on GitHub](https://github.com/matthew-j-holmes/runa)

---
<div class="d-flex justify-content-between align-items-baseline flex-wrap mb-2">
  <h2 id="overhead">Overhead Flight Controller</h2>
  <em class="text-end" style="font-size: 1.25rem;">Raspberry Pi Airspace Display</em>
</div>


A custom Raspberry Pi dashboard that displays real-time air traffic overhead using OpenSky Network data. Aircraft metadata is correlated via external APIs and rendered on an e-ink screen for an always-on glanceable readout.

- Aggregates flight data (type, origin, destination, altitude, etc.)
- Outputs to InkyWHAT e-ink display
- Designed for headless Raspberry Pi deployment
- GPS receiver integration in progress

[Overhead Flight Controller on GitHub](https://github.com/matthew-j-holmes/overhead-flight-controller)

---
<div class="d-flex justify-content-between align-items-baseline flex-wrap mb-2">
  <h2 id="server">Home Server</h2>
  <em class="text-end" style="font-size: 1.25rem;">Hardened Ubuntu on Repurposed iMac</em>
</div>

I converted a 2011 iMac into a secure, resilient home server running Ubuntu Server. It hosts dynamic and static sites, databases, and and internal tools with Docker, and includes automated backups, firewall rules, and private remote access via Tailscale.

- Docker-based deployment of web services
- Reverse proxy with HTTPS via Nginx + Let’s Encrypt
- Local and cloud backups, DNS failover, SSH hardening
- Private access via Tailscale mesh VPN

[View Configuration Notes](https://github.com/matthew-j-holmes/home-server)

---
<div class="d-flex justify-content-between align-items-baseline flex-wrap mb-2">
  <h2 id="komodo">Komodo</h2>
  <em class="text-end" style="font-size: 1.25rem;">Harm Reduction Timer App (Team Project)</em>
</div>

Komodo supports users engaging in high-risk activities by sending emergency alerts if they don’t check in. It uses a countdown timer, geolocation, and Twilio integration to notify a designated contact if the user is unresponsive.

- Twilio SMS alerts
- Redis-based session and timer tracking
- Map-based UI with geolocation
- Developed collaboratively with a small team

[Komodo on GitHub](https://github.com/matthew-j-holmes/komodo)

---
<div class="d-flex justify-content-between align-items-baseline flex-wrap mb-2">
  <h2 id="dogoodr">DoGoodr</h2>
  <em class="text-end" style="font-size: 1.25rem;">Volunteer Event Matching (Team Project)</em>
</div>

DoGoodr connects nonprofits with potential volunteers through a filterable, tag-based event discovery platform. I designed and implemented the backend database and API powering the listings, search, and user interactions.

- REST API design and implementation
- Event search by tag, date, and organization
- Built and delivered as a collaborative capstone project

[DoGoodr on GitHub](https://github.com/matthew-j-holmes/dogoodr)

---

Have questions about any of these? [Email me](mailto:matthewjustinholmes@gmail.com) or [reach out on GitHub](https://github.com/matthew-j-holmes).
