# 🧩 Projects & Features

A selection of key tools and systems developed as part of the Sombrero pipeline — focused on automation, integration, and creative workflow optimization across multiple DCCs.

---

## 🌀 Synctool Refactor
Refactor and modular redesign of **Synctool**, the synchronization system between ShotGrid, Deadline, and internal servers.  
Introduced dynamic entities, unified payload structure, and dependency management across multiple contexts.  
**Focus:** stability, cleaner architecture, and granular logging.  

**Tags:** `python` `api` `shotgrid` `deadline` `pipeline`

---

## 📦 Delivery System
Automation of the *playlist → render → publish* pipeline.  
Connected PDG (Houdini) with Nuke job generation through Deadline, handling dependencies and batch publishing to ShotGrid.  
**Result:** fully hands-off delivery process for client reels and review versions, with tracked dependencies and batch metadata.

**Tags:** `pdg` `nuke` `shotgrid` `automation` `delivery`

---

## 🧠 Bid Loader
Tool for importing and structuring **bids** and budgeting data directly into ShotGrid or toolsets.  
Simplified resource planning and task tracking for VFX projects.

**Tags:** `shotgrid` `data` `planning`

---

## 🎬 Blender Submitter & Compositor Helper
Blender addon integrating Deadline submission with compositor automation.  
Automatically checks “Use Nodes”, adds File Output nodes, and embeds project metadata.  
**Impact:** eliminated manual setup errors and standardized render submissions.

**Tags:** `blender` `addon` `deadline` `automation`

---

## 🧾 Report Notes & Report Tool
Two complementary modules:  
- **Report Notes in ShotGrid:** extracts and formats artist notes for review reports.  
- **Report Tool:** standalone interface for generating daily PDF/HTML reports.  
**Focus:** technical visibility and communication between departments.

**Tags:** `reporting` `shotgrid` `pipeline`

---

## ☁️ S3 Syncs & Backup Crawler
Utilities for syncing local storage with S3 buckets, plus a crawler for automated backups.  
**Result:** redundancy, reliability, and traceable publishing of versioned assets.

**Tags:** `aws` `s3` `backup` `sync`

---

## 🧮 Rotating Logs
Implementation of a rotating logging system with timestamps and configurable levels.  
Used across multiple internal tools (Synctool, Daemons, Toolsets).  
**Goal:** maintain clean, manageable logs and avoid accumulation on long-running processes.

**Tags:** `logging` `python` `automation`

---

## 🧭 Showpath Tool & Tracker Cache
- **Showpath Tool:** retrieves and validates production paths across platforms.  
- **Tracker Cache:** caches ShotGrid or local queries, reducing latency for dependent tools.  
**Result:** faster workflows, fewer redundant queries, improved stability.

**Tags:** `python` `shotgrid` `tools` `cache`

---

## 🖼️ Slates, Contact Sheet & Publish Canvas
- **Slates:** automated title cards with metadata and studio branding.  
- **Contact Sheet:** automatic frame collage for quick visual review.  
- **Publish Canvas:** visual dashboard for version publication control.  
**Focus:** clarity and presentation in review and delivery processes.

**Tags:** `nuke` `rendering` `design` `automation`

---

## 🌐 Frontend, APIs & ShotGrid Daemon
Development of lightweight web frontends and API endpoints to trigger Synctool, Delivery, and reporting actions.  
The **ShotGrid Daemon** keeps versions, thumbnails, and status synchronized between the database and storage.  
**Stack:** Vue.js, Python (Flask/FastAPI), ShotGrid API, WebSockets.

**Tags:** `web` `vue` `api` `flask` `fastapi` `shotgrid`

---

## 🧰 DCC Integrations
Continuous development and maintenance of deep integrations for:
- **Nuke:** HS Write node, Delivery templates, automatic versioning.  
- **Houdini:** PDG job creation and procedural dependency management.  
- **Blender:** custom addons, UI panels, File Output automation.  
**Goal:** unify publishing and versioning across all DCCs.

**Tags:** `nuke` `houdini` `blender` `integration` `pipeline`

---

> These tools collectively form the backbone of Sombrero’s automated publishing ecosystem — connecting creative tools, databases, and delivery systems into a cohesive, artist-friendly workflow.
