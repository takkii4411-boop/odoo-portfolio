# Odoo Development Portfolio

![Odoo](https://img.shields.io/badge/Odoo-16%20%E2%80%A2%2017%20%E2%80%A2%2018%20%E2%80%A2%2019-blueviolet) ![Modules](https://img.shields.io/badge/Modules%20Showcased-77-blue) ![Frontend](https://img.shields.io/badge/Owl-4.x-orange) ![License](https://img.shields.io/badge/License-LGPL--3-green)

> Production-grade **Odoo ERP development** across **Odoo 16, 17, 18 and 19** — **77 modules showcased**, of which **15+ authored personally** (Hospital PMS + practice suite from scratch, core OWL widget library, POS SC/PWD discount engine, pet-store modules). The larger suites (ODOOPIM PIM, TG Sugar, Adaptive ERP) are team builds where my contribution was the **ODOOPIM widget suite, selected modules and heavy debugging** — attributed honestly per module in each repo.

---

## Featured Work

### 1. ODOOPIM — AI-Powered Product Information Management (Odoo 18, 25 modules)
Akeneo-style enterprise PIM (Navabrind ODOOPIM platform). **My contribution: the UI widget suite** — split-screen attribute views, jsTree category hierarchy, attribute field widgets and the PIM control panel — plus client-driven debugging & small enhancements. AI layer, channelization, approvals, imports & connectors are team modules (bundled for context).

🔗 **Source & docs**: [odoopim-ai-suite](https://github.com/takkii4411-boop/odoopim-ai-suite)

| Overview | Import Wizard | Connectors |
|---|---|---|
| ![PIM Overview](https://raw.githubusercontent.com/takkii4411-boop/odoopim-ai-suite/main/product_management/static/description/overview.png) | ![Import](https://raw.githubusercontent.com/takkii4411-boop/odoopim-ai-suite/main/import_product_variants_app/static/description/main_screenshot.png) | ![n8n](https://raw.githubusercontent.com/takkii4411-boop/odoopim-ai-suite/main/odoo_pim_connector/static/description/odoo_n8n_pim.png) |

### 2. TG Sugar ERP — Sugar Factory + Odoo↔Tally Connector (Odoo 19, 9 modules)
Sugar-factory suite: **Tally XML export**, tender purchase management, broker allotment portals, party-sale flows and scheduled **DB backups**. **My role across this suite: debugging & support** (bug fixing, QA, small patches) — a delivery-context repo.

🔗 **Source & docs**: [tg-sugar-erp](https://github.com/takkii4411-boop/tg-sugar-erp)

| Tally Mapping | Tender Booking | Backup Engine |
|---|---|---|
| ![Tally](https://raw.githubusercontent.com/takkii4411-boop/tg-sugar-erp/main/odoo_tally_connector/static/description/1.png) | ![Tender](https://raw.githubusercontent.com/takkii4411-boop/tg-sugar-erp/main/tender_booking/static/description/auction.png) | ![Backup](https://raw.githubusercontent.com/takkii4411-boop/tg-sugar-erp/main/auto_database_backup/static/description/assets/icons/feature.png) |

### 3. Adaptive ERP Suite — Estimation-Centric Sales Pipeline (Odoo 19, 12 modules)
Team-built estimation family (CRM→Sale→Project→Documents→Reports) with MRP, inventory, purchase-report and sales customizations. **My role: small enhancements, fixes & debugging** (MRP/inventory tweaks, chatter positioning, wizard close-warning, report adjustments).

🔗 **Source & docs**: [adaptive-erp-suite](https://github.com/takkii4411-boop/adaptive-erp-suite)

### 4. Six Paws — Pet Store ERP (Odoo 19, 4 modules)
Co-built pet-ERP: **pet profiles master-data (mine)** and **pet-driven product filtering in Sale Orders (mine)**, plus team modules for the **customer pet portal** and **pet-aware product customization**.

🔗 **Source & docs**: [six-paws-pet-store](https://github.com/takkii4411-boop/six-paws-pet-store)

### 5. POS Customizations (Odoo 17, 2 modules)
Modifications & feature additions on the existing POS (built over the Softhealer retail suite base):
- **Pos SC/PWD HMRC (mine)** — added a statutory Senior-Citizen/Person-With-Disability discount engine computing discount on **net-of-VAT price**, POS session login, audit trail, e-journal & compliance reporting suite (heavy JS/XML work + debugging).
- **Pos Voice Agent (team module; my role: debugging)** — wake-word trigger + fuzzy product search (rapidfuzz).

🔗 **Source & docs**: [odoo-pos-customizations](https://github.com/takkii4411-boop/odoo-pos-customizations)

### 6. Ranthox OWL Widgets (Odoo 16→19, ~20 modules)
Personally authored the **3 core widgets**: **inline Excel editor**, **webcam capture fields**, **x2many live search bars** — the team maintained the 4-version ports (16/17/18/19) and sale-order usage modules.

🔗 **Source & docs**: [ranthox-owl-widgets](https://github.com/takkii4411-boop/ranthox-owl-widgets)

### 7. Hospital Management System — Built From Scratch + Practice Implementations (Odoo 18/19, 5 modules)
**Hospital PMS — first application built completely from scratch** (models, security, sequences, wizard flows, QWeb PDF reports, records portals): hospital patient/doctor/appointment management, stock material records, task tracker.

🔗 **Source & docs**: [odoo-practice-projects](https://github.com/takkii4411-boop/odoo-practice-projects)

---

## Capability Matrix

| Area | Delivered |
|---|---|
| **Custom app development** | Hospital PMS (from scratch) + practice apps, Six Paws pet modules, POS SC/PWD discount engine, ODOOPIM widget suite, core OWL widget library |
| **3rd-party ERP integration** | Odoo↔Tally (XML) — debugging scope; n8n + marketplace connectors (Shopify/Amazon/Magento/eBay/Flipkart/Shopware/Walmart) — team context |
| **AI features in Odoo** | Platform AI layer exposure (chatbot, enrichment, translation) — widget integration & debugging |
| **Bank of UI/OWL work** | Excel editor, image capture, x2many search, split views, category trees, control panel — core widgets authored |
| **Compliance & security** | SC/PWD POS discount engine, audit trails |
| **Support & debugging** | Tally exports, tender/broker flows, DB backup configs, suite-wide QA/fixes across team builds |
| **Reports** | QWeb PDFs, paper formats, purchase/sales reports, e-journal/annex/e-sales POS reports |
| **Bulk data ops** | Excel/CSV import of products-variants (with images & attributes), legacy invoice capture |

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Odoo](https://img.shields.io/badge/Odoo-16+-714B67?logo=odoo&logoColor=white) ![OWL](https://img.shields.io/badge/Owl.js-JS%20framework-F7DF1E?logo=javascript&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![XML/QWeb](https://img.shields.io/badge/XML%2FQWeb-views%20%26%20reports-orange) ![JS](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&logoColor=black) ![CSS/SCSS](https://img.shields.io/badge/SCSS-CC6699?logo=sass&logoColor=white) ![rapidfuzz](https://img.shields.io/badge/rapidfuzz-fuzzy%20matching-blue) ![n8n](https://img.shields.io/badge/n8n-automation-EA4B71?logo=n8n&logoColor=white)

## Work Domains Covered

Hospital management • Retail POS • Sugar manufacturing • Pet e-commerce • PIM/product content • Accounting (Tally) • Tendering & brokerage • Construction/manufacturing estimation

---

*Client names are partially redacted/rebranded in open-source copies. A walk-through on any module, or a private demo of the ODOOPIM instance, is available on request.*

**Contact**: takkii4411@gmail.com
