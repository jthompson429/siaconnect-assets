# 📁 SIAConnect Assets Repository

This repository contains configuration files, templates, Power Automate flows, and reference assets used in the development of the **SIAConnect** internal support assistant.

---

## 📂 Folder Structure Overview

### `assets/`
- Contains brand-aligned banners, logos, and imagery used in adaptive cards and presentations.

### `adaptive-cards/`
- JSON files for adaptive cards used in SIAConnect.
- Subfolders separate by function, e.g., request confirmations or search results.

### `dataverse/`
- All content-related data for Dataverse tables, organized by feature.
- Includes cleaned data, schema guides, import templates, and markdown-converted content.

### `flows/`
- Exported `.zip` packages of Power Automate flows.
- Grouped by the feature they support (e.g., SharePoint search, unit conversion).

### `templates/`
- Word and PowerPoint templates aligned with Glory brand guidelines.
- Includes demo decks and downloadable service bulletin templates.

### `topics/`
- YAML/JSON definitions for Copilot Studio adaptive dialog topics.
- Designed to give SIAConnect a consistent tone, user flow, and trigger logic.

### `notes/`
- Documentation for development planning, roadmap ideas, style guides, and exec feedback.

---

## ✅ Purpose

SIAConnect was created to:
- Replace the Bamboo SharePoint Knowledge Base web part
- Create, track, and assist with documentation requests (via Jira)
- Integrate search and guidance tools for Service, Engineering, and Field Technicians

---

## 🔐 Security & Compliance Notes
- All user interactions occur within Microsoft Teams or SharePoint (SIA), authenticated via Azure AD.
- No external/public access is enabled or planned.
- All data structures (e.g., KBData, Error Codes) reside in secure Dataverse environments.
- Branding, tone, and usage logs align with Responsible AI Practices.

---

## 🤝 Contributions

This project is developed and maintained by a solo developer. If internal contributors are added:
- Please follow the naming conventions and structure above.
- Coordinate flow and schema changes in `notes/roadmap.md`.

---

## 📌 Contact

- For documentation or development questions, please contact the project owner directly.