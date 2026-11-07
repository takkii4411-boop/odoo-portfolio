# Odoo Development Portfolio

![Odoo](https://img.shields.io/badge/Odoo-16%20%E2%80%A2%2017%20%E2%80%A2%2018%20%E2%80%A2%2019-blueviolet) ![Modules](https://img.shields.io/badge/Custom%20Modules-75%2B-blue) ![Frontend](https://img.shields.io/badge/Owl-4.x-orange) ![License](https://img.shields.io/badge/License-LGPL--3-green)

> Production-grade **Odoo ERP development** — 75+ custom modules delivered across **Odoo 16, 17, 18 and 19** for products & client implementations: an enterprise **AI-powered PIM platform**, a **sugar-factory ERP with Odoo↔Tally connector**, statutory **POS compliance**, sector ERPs (pet-store, hospital) and a reusable **OWL widget library**.

---

## Featured Work

### 1. ODOOPIM — AI-Powered Product Information Management (Odoo 18, 25 modules)
Akeneo-style enterprise PIM built natively in Odoo: families, attributes, categories, **channelization & localization**, approval workflows, **AI enrichment + AI translation + embedded AI chatbot**, Excel/CSV bulk product-variant import, marketplace connectors (Shopify/Amazon/Magento/…), n8n connector, and a suite of custom OWL voice-of-product widgets.

🔗 **Source & docs**: [odoopim-ai-suite](https://github.com/takkii4411-boop/odoopim-ai-suite)

| Overview | Import Wizard | Connectors |
|---|---|---|
| ![PIM Overview](https://raw.githubusercontent.com/takkii4411-boop/odoopim-ai-suite/main/product_management/static/description/overview.png) | ![Import](https://raw.githubusercontent.com/takkii4411-boop/odoopim-ai-suite/main/import_product_variants_app/static/description/main_screenshot.png) | ![n8n](https://raw.githubusercontent.com/takkii4411-boop/odoopim-ai-suite/main/odoo_pim_connector/static/description/odoo_n8n_pim.png) |

### 2. TG Sugar ERP — Sugar Factory + Odoo↔Tally Connector (Odoo 19, 9 modules)
Factory-grade customizations: **Tally XML export with configurable field mapping**, tender purchase management, broker allotment portals, party-sale flows, legacy invoice data capture, and scheduled encrypted **database backups** (S3/Dropbox/Google Drive/Nextcloud/OneDrive/FTP/SFTP).

🔗 **Source & docs**: [tg-sugar-erp](https://github.com/takkii4411-boop/tg-sugar-erp)

| Tally Mapping | Tender Booking | Backup Engine |
|---|---|---|
| ![Tally](https://raw.githubusercontent.com/takkii4411-boop/tg-sugar-erp/main/odoo_tally_connector/static/description/1.png) | ![Tender](https://raw.githubusercontent.com/takkii4411-boop/tg-sugar-erp/main/tender_booking/static/description/auction.png) | ![Backup](https://raw.githubusercontent.com/takkii4411-boop/tg-sugar-erp/main/auto_database_backup/static/description/assets/icons/feature.png) |

### 3. Adaptive ERP Suite — Estimation-Centric Sales Pipeline (Odoo 19, 12 modules)
Complete estimation family (CRM→Sale→Project→Documents→Reports) to run a **pre-sales estimation pipeline**, plus targeted MRP, inventory, purchase-report and sales customizations.

🔗 **Source & docs**: [adaptive-erp-suite](https://github.com/takkii4411-boop/adaptive-erp-suite)

### 4. Six Paws — Pet Store ERP (Odoo 19, 4 modules)
Pet profiles master-data, **customer portal for pets**, pet-aware product customization and **pet-driven product filtering in Sale Orders**.

🔗 **Source & docs**: [six-paws-pet-store](https://github.com/takkii4411-boop/six-paws-pet-store)

### 5. POS Customizations (Odoo 17, 2 modules)
- **Pos SC/PWD HMRC** — statutory Senior-Citizen/Person-With-Disability discount engine computing discount on **net-of-VAT price**, with POS session login, audit trail, e-journal & compliance reporting suite.
- **Pos Voice Agent** — voice assistant for POS: wake-word trigger + fuzzy product search (rapidfuzz).

🔗 **Source & docs**: [odoo-pos-customizations](https://github.com/takkii4411-boop/odoo-pos-customizations)

### 6. Ranthox OWL Widgets (Odoo 16→19, ~20 modules)
Reusable frontend library: **inline Excel editor**, **webcam capture fields**, **x2many live search bars**, ported across 4 Odoo versions with sale-order usage modules.

🔗 **Source & docs**: [ranthox-owl-widgets](https://github.com/takkii4411-boop/ranthox-owl-widgets)

### 7. Practice Implementations (Odoo 18/19, 5 modules)
Hospital PMS, doctor appointments with wizard+QWeb PDF reports, patient management, stock record keeping, task tracker.

🔗 **Source & docs**: [odoo-practice-projects](https://github.com/takkii4411-boop/odoo-practice-projects)

---

## Capability Matrix

| Area | Delivered |
|---|---|
| **Custom app development** | ODOOPIM PIM, Adaptive estimation suite, TG sugar ERP, Six Paws |
| **3rd-party ERP integration** | Odoo↔Tally (XML), n8n, marketplace connectors (Shopify/Amazon/Magento/eBay/Flipkart/Shopware/Walmart) |
| **AI features in Odoo** | Chatbot (document loader), AI attribute enrichment, AI translation |
| **Bank of UI/OWL work** | Excel editor, image capture, x2many search, split views, category trees, kanban/list switchers, charts |
| **Compliance & security** | SC/PWD POS discount engine, audit trails, concurrent login restriction, approval workflows |
| **Ops modules** | Multi-destination DB backups, menu hiding, datetime masking |
| **Reports** | QWeb PDFs, paper formats, purchase/sales reports, e-journal/annex/e-sales POS reports |
| **Bulk data ops** | Excel/CSV import of products-variants (with images & attributes), legacy invoice capture |

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Odoo](https://img.shields.io/badge/Odoo-16+-714B67?logo=odoo&logoColor=white) ![OWL](https://img.shields.io/badge/Owl.js-JS%20framework-F7DF1E?logo=javascript&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![XML/QWeb](https://img.shields.io/badge/XML%2FQWeb-views%20%26%20reports-orange) ![JS](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&logoColor=black) ![CSS/SCSS](https://img.shields.io/badge/SCSS-CC6699?logo=sass&logoColor=white) ![rapidfuzz](https://img.shields.io/badge/rapidfuzz-fuzzy%20matching-blue) ![n8n](https://img.shields.io/badge/n8n-automation-EA4B71?logo=n8n&logoColor=white)

## Work Domains Covered

Hospital management • Retail POS • Sugar manufacturing • Pet e-commerce • PIM/product content • Accounting (Tally) • Tendering & brokerage • Construction/manufacturing estimation

---

*Client names are partially redacted/rebranded in open-source copies. A walk-through on any module, or a private demo of the ODOOPIM instance, is available on request.*

**Contact**: takkii4411@gmail.com
