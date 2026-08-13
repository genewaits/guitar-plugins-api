# 🎸 Tone Lord API Specification

Welcome to the **Tone Lord API** — the ultimate, slightly arrogant REST API contract designed for bedroom shredders and true tone chasers who traded heavy, expensive tube amplifiers for digital bedroom perfection. 

This project demonstrates the core principles of API-First development, proper REST architecture, and clean data modeling for an online catalog of guitar VST/AU plugins and audio effects.

## 🔗 Live Documentation
👉👉 **View Interactive API Documentation on Bump.sh** (https://bump.sh/waits/doc/tone-lord-api)**

---

## 🛠️ Tech Stack & Standards
* **Specification:** OpenAPI 3.0.3 (OAS3)
* **Format:** YAML
* **Architecture Style:** RESTful API
* **Design Philosophy:** API-First / Design-First

---

## 📖 Business Logic & Key Features

* **Complete CRUD Blueprint:** Contains detailed paths for exploring the full catalog (`GET /plugins`), viewing specific gear configurations (`GET /plugins/{id}`), and modifying entries (`POST /plugins`).
* **Advanced Data Modeling:** Demonstrates nested object arrays representing real-world virtual gear stacks (including dedicated lists for virtual amplifiers, cabinets, and stompboxes).
* **Granular Filtering:** Built-in support for query parameters to easily filter the catalog by manufacturer (`brand`) or software type (`category`).
* **Role-Based Security Simulator:** Features a simulated `Bearer Token (JWT)` authentication layer. Public users have read-only access to discover tones, while write operations (`POST`) are restricted to verified `AdminToken` holders.
* **Robust Error Handling:** Explicitly documents edge-case responses, including `401 Unauthorized`, `403 Forbidden`, and `404 Not Found` statuses.
