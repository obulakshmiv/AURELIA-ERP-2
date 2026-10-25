# AURELIA ERP · Enterprise Smart Manufacturing Platform

### Unified Smart Manufacturing MES + SAP S/4HANA Edition with Built-in AI Engines

Aurelia ERP is a comprehensive, production-grade Smart Manufacturing and Enterprise Resource Planning (ERP) platform designed by merging high-precision shop-floor execution (**DESAT INFO TECH Smart Manufacturing MES**) with enterprise-wide resource planning (**SAP S/4HANA Enterprise Modules**).

---

## 🚀 Quick Launch (Instant Browser Execution)

You can launch the complete enterprise platform with zero setup:
1. Double-click **`launch-aurelia-erp.bat`**
2. Or open **`aurelia-manufacturing-erp.html`** (or `index.html`) directly in any modern web browser (Edge, Chrome, Firefox).

* Default Admin Demo Account: **`admin`** / **`desat123`**
* All simulated personas use demo password: **`desat123`**

---

## 👥 20 Specialized Enterprise Roles & Personas

Click the **`👥 20 Roles`** button in the top navigation bar to inspect and switch between personas instantly:

| # | Role Title | Department | SAP / MES Focus | Key Persona | Username |
|---|------------|------------|-----------------|-------------|----------|
| 1 | **Managing Director / General Manager** | Executive | Strategic P&L, MD Approvals (>₹1 Cr) | Arvind Narayan | `md` |
| 2 | **Production Planning Manager (SAP PP)** | Production | `MD04` MRP II, `CO01` Work Orders, MPS | Varun Krish | `planner` |
| 3 | **Plant Operations Manager** | Production | Shop floor pacing, MES throughput | Rithika Anand | `opsmanager` |
| 4 | **Shop Floor & Line Supervisor** | Production | `CO11N` confirmations, shift output | Harini Dev | `linesupervisor` |
| 5 | **Assembly & CNC Lead Operator** | Production | Shop floor execution, PCB assembly | Kiran Das | `assembly` |
| 6 | **Quality Assurance Head (SAP QM)** | Quality | `QA32` Inspection Lots, UD, 8D CAPA | Rohan Pillai | `quality` |
| 7 | **AI Vision & Metrology Inspector** | Quality | Computer Vision Inspection, Quarantine | Sanjay Rao | `qauditor` |
| 8 | **Procurement Manager (SAP MM)** | Supply Chain | `ME21N` POs, `MIGO`, 3-Way Match | Pooja Nair | `procmanager` |
| 9 | **Supplier Quality Specialist** | Supply Chain | Vendor PPM scorecards, RMA gating | Sowmya Das | `supplierquality` |
| 10 | **Plant Maintenance Head (SAP PM)** | Maintenance | `IW31` Work Orders, FLOC, MTBF/MTTR | Aditya Menon | `maintenance` |
| 11 | **IoT Automation & AAFI Specialist** | Maintenance | Sensor anomaly telemetry, AAFI loop | Kabir Joshi | `it` |
| 12 | **Extended Warehouse Manager (SAP EWM)** | Warehouse | `MB52` Bins, 101/261 movements | Tara Krishnan | `warehouse` |
| 13 | **Inventory Controller & MRP Analyst** | Warehouse | Safety stock, lead-time shortages | Nandita Paul | `invcontroller` |
| 14 | **Sales & Distribution Manager (SAP SD)** | Commercial | `VA01` Sales Orders, `CO09` ATP check | Nila Raman | `sales` |
| 15 | **Finance & Controlling Director (FICO)**| Finance | `FB50` G/L, Indian GST (CGST/SGST/IGST)| Kavya Raman | `finance` |
| 16 | **Product Cost Analyst (CO-PC)** | Finance | Product Cost Component Split, variance | Anjali Shah | `costanalyst` |
| 17 | **Workforce & Shift Planner** | Governance | Skills Matrix (L0-L3), shift balancing | Suresh Kumar | `workforceplan` |
| 18 | **Environmental, Safety & Carbon Lead** | Governance | Energy tariffs, kWh/unit, CO2 emissions | Zoya Thomas | `security` |
| 19 | **Enterprise Risk & Compliance Lead** | Governance | Anomaly detection, price change control | Sneha George | `compliance` |
| 20 | **SAP S/4HANA Systems Administrator** | Governance | RBAC permissions, T-Code routing | Akash Pillai | `sysadmin` |

---

## 🌟 15+ Core & Enterprise Modules

1. **SAP PP (Production Planning & Detailed Scheduling)**: T-Code `MD04` / `CO01` — Master Production Schedule (MPS), live MRP II calculation engine (`MD01N`), Work Centers load balancing, Order Confirmation (`CO11N`), and TECO completion.
2. **SAP MM (Materials Management & Purchasing)**: T-Code `ME21N` / `MIGO` — Automated 3-Way Match (PO vs MIGO vs MIRO), Vendor 360° scorecard rating, and Moving Average Price (MAP) valuation.
3. **SAP QM (Quality Management)**: T-Code `QA32` — Inspection Lots across Lot Origins 01, 03, 04, 05, Quantitative spec limits (USL/LSL), Usage Decisions (UD-01, UD-02, UD-03), and 8D CAPA tracker.
4. **SAP PM / EAM (Plant Maintenance)**: T-Code `IW31` — Functional Locations (FLOC), MTBF (342h) and MTTR (2.4h) telemetry, PM work orders, and spare parts BOM (sBOM).
5. **SAP SD (Sales & Distribution)**: T-Code `VA01` — Real-time Available-to-Promise (ATP) checking (`CO09`), Customer Credit Exposure limits, picking, packing, and Post Goods Issue (PGI Movement Type 601).
6. **SAP FICO (Financials & Controlling)**: T-Code `FB50` — G/L double-entry balances, Product Cost Component Split (CO-PC), and automated Indian GST calculation (CGST+SGST / IGST).
7. **SAP EWM (Extended Warehouse Management)**: T-Code `MB52` — Multi-zone storage bins, inventory movement types (101, 201, 261, 311, 551).
8. **SAP DMC (Digital Manufacturing Cloud OEE)**: T-Code `OEE` — Overall Equipment Effectiveness = Availability (92.4%) × Performance (89.6%) × Quality (99.1%) = 82.0%, with Six Big Losses waterfall analysis.
9. **SAP T-Code Quick Navigation Bar**: Type any standard SAP T-Code (`MD04`, `MIGO`, `QA32`, `IW31`, `VA01`, `FB50`, `OEE`, `MB52`...) to navigate instantly.
10. **Factory Digital Twin**: 6-workstream SVG interactive layout with real-time what-if parameter sliders and bottleneck detection.
11. **Multi-Level Bill of Materials (BOM)**: Recursive tree with sub-assemblies, scrap allowance, and live cost roll-up.
12. **Global Batch Traceability (GBT)**: Multi-tier genealogy from supplier lot to finished serial number, warranty status, and one-click lot quarantine lock.
13. **Workforce Skills Matrix & Shift Roster**: Real-time qualification levels (0-3), certification expiry alerts, and replacement solver.
14. **Enterprise Risk Center & Governance**: Multi-category risk monitoring (Financial, Inventory, Production, Security, Supplier) with escalation to MD.
15. **SpreadsheetML Excel Export**: Live export of all analytics and tables into a Microsoft Excel workbook with one click.
16. **Universal In-Browser Content Editing**: Toggle "✎ Edit" mode to edit text or table cells directly in browser, saved automatically to localStorage.

---

## 🤖 Built-in AI Capabilities

Click the **`✨ AI Engines`** button in the top navigation bar to explore the active AI capabilities:

1. **✦ AI Operations Copilot (DESAT Copilot)**: Natural language manufacturing copilot answering questions on downtime, MRP, anomalies, cost margins, and SAP transactions.
2. **◎ AI Computer Vision Defect Inspector**: Image upload canvas with optical edge & defect classification, crack/surface defect identification, and 1-click batch quarantine lock.
3. **⚙ Predictive AI Maintenance Telemetry & Anomaly Engine**: Real-time sensor simulation (temp, vibration, current, hours) with automated health score degradation and predictive maintenance alerts.
4. **⟲ Autonomous Closed-Loop Response (AAFI)**: 8-stage closed-loop automation from anomaly detection to schedule re-balancing, spare parts checking, work order creation, and maintenance verification.
5. **▤ AI Predictive MRP & Demand Forecaster**: Automated lead time vs burn-rate analysis with alert flags for imminent stockouts.
6. **✚ AI Workforce Skill & Shift Optimizer**: Automated crew allocation matching operator certifications to line safety requirements.

---

## 📁 Repository Structure

```
AURELIA ERP/
├── launch-aurelia-erp.bat            # One-click launcher for Windows
├── aurelia-manufacturing-erp.html    # Master Enterprise Platform (Interactive Single-File)
├── index.html                        # Standard Web Entry Point
├── README.md                         # Complete System Documentation
├── backend/                          # Full Python FastAPI REST API Backend
│   ├── app/
│   │   ├── api/v1/                   # REST API routes
│   │   ├── core/                     # Auth, tenant context, database
│   │   ├── db/                       # Migrations & seed scripts
│   │   └── modules/                  # 19 Enterprise Modules (FastAPI + SQLAlchemy)
│   ├── Dockerfile
│   └── requirements.txt
├── frontend/                         # Cross-Platform Flutter Frontend (Web/Mobile/Desktop)
│   ├── lib/
│   │   ├── app/                      # Theme, Router
│   │   ├── core/                     # API client, Auth state
│   │   └── features/                 # Modular screens (Inventory, QM, PP, Sales...)
│   └── pubspec.yaml
└── docs/                             # Engineering & SAP Architecture Guides
    ├── SAP-DESAT-INTEGRATED-ARCHITECTURE.md
    ├── database-schema.md
    ├── api-specification.md
    └── architecture.md
```
