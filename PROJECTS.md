# Complete Engineering & Client Projects Catalog — Muheeb Bin Nadeem Khan

A structured directory of all open-source repositories, ByteX Solution flagship products, POS/ERP systems, MERN/AI applications, and client portals engineered by **Muheeb Bin Nadeem Khan**.

---

## 1. Flagship Products & SaaS Platforms

### 🧾 Invoice X — Multi-Tenant Business Management & Invoicing SaaS *(by ByteX Solution)*
- **Edition A (Full Multi-Tenant SaaS + Mobile + Super Admin):**
  - **Database (`PostgreSQL 15+ / Supabase RLS`)**: 33+ normalized tables, 5 reporting views, immutable triggers, Row Level Security, feature entitlements, and 56 invoice templates (6 Free + 50 Pro).
  - **Backend (`Node.js + Express + TypeScript`)**: `/v1` REST API, `Decimal.js` calculation engine, draft autosave & conflict detection, atomic finalization, Cloudflare R2 signed URLs, multi-page PDF rendering (`pdfkit`), background job scheduler, Vitest E2E suite.
  - **Admin Panel (`React + Vite + Tailwind + TypeScript`)**: ByteX Solution Super Admin panel for tenants, users, plans, entitlements, manual payments, templates, tickets, coupons, and audit logs.
  - **Mobile (`Flutter + Dart + Riverpod + SQLite`)**: Offline-first 30-screen Android app with SQLite autosave, debounced sync, conflict resolution, and PDF sharing.
- **Edition B (Standalone Invoicing, POS & Inventory App):**
  - **Live:** [invoicex.bytexsolution.com](https://invoicex.bytexsolution.com)
  - Invoices, Estimates/Quotations, Official Payment Receipts, Customer Ledger, Product Catalog, Built-in POS & Inventory Stock Management, Touch/Mouse Signature Drawing, PKR Amount-in-Words (`numberToWordsPKR`), PNG/PDF export, LocalStorage + optional Supabase / Neon PostgreSQL sync.

### 🍽️ Restaurant ERP & POS
- **Stack:** React 19, TypeScript, Express 5, WebSockets (`ws`), SQLite, Electron Desktop, Capacitor Android, Recharts
- **Scope:** Multi-surface Restaurant ERP & Point-of-Sale system with real-time WebSocket order/kitchen updates, transactional SQLite ledger, hardware integration, biometric attendance, payroll/accounting workflows, and desktop + Android shells.

### 📱 PAK Mobile x Accessories Aura
- **Stack:** Centralized MongoDB (`Mongoose + Decimal128`), Node.js + Express + TypeScript REST API, Next.js 14 Web Dashboard, Native Android Jetpack Compose App
- **Scope:** Production mobile shop Inventory, Sales, Purchase, Repair tracking, Customer ledger, QR codes, and Profit Management system syncing web and native Android in real time.

### 🔧 WorkshopFlow (`v1.6.0`)
- **Stack:** PHP 8, JSON/File Storage, PWA (Service Worker + Web Manifest), QR Scanner (`jsQR` + `QRCode.js`), Charts
- **Scope:** Role-based workshop management system (Owner/Admin, Manager, Staff) with QR attendance check-in/out, advances, expenses, payroll generation, and backup tools.

### 🛒 NOVENTRA SLUTIONS LLC Storefront
- **Stack:** Next.js 15, React 19, TypeScript, Tailwind CSS, Supabase PostgreSQL + Auth + Storage, Stripe Checkout & Webhooks, Nodemailer, Recharts
- **Scope:** Full-stack production e-commerce storefront targeting both Vercel and cPanel deployments.

---

## 2. MERN Stack & Artificial Intelligence Projects

| Project | Stack | Description | Link |
|---|---|---|---|
| **VitalNutri AI (`diet`)** | MongoDB, Express, React, Node.js, JWT, Mistral-7B, Recharts, jsPDF | AI Diet Management System with BMI/BMR/TDEE calculators, USDA food search, calorie deficit engine, water tracker, AI nutrition coach & PDF/CSV reports | [`Muheebbinnadeem/diet`](https://github.com/Muheebbinnadeem/diet) |
| **Document + Website RAG Chatbot** | Python, Streamlit, LangChain, Groq, Sentence Transformers, ChromaDB | Multi-format RAG chatbot ingesting PDF, DOCX, PPTX, Excel, CSV & live websites into Chroma vector store | Local Workspace (`RAG_project`) |
| **PGCAI (`Project-ai`)** | TypeScript, React, Vite, Supabase, AI | Punjab College AI Student & Teacher Portal deployed on Vercel | [`Project-ai`](https://github.com/Muheebbinnadeem/Project-ai) / [pgcai.vercel.app](https://pgcai.vercel.app) |
| **Leaf Doctor AI** | TypeScript, HTML5/CSS3, TensorFlow/TF.js, Python | AI-powered plant leaf disease image classification & instant diagnosis | [`leaf-doctor-ai`](https://github.com/Muheebbinnadeem/leaf-doctor-ai) / [Live](http://leafdet.muheebbinnadeem.site/) |
| **Am Ai — Study Companion** | PHP, MySQL, HTML5, CSS3, JavaScript | Web-based AI study companion with auth, chat & SQL persistence | Local Workspace (`htdocs/am`) |

---

## 3. Cybersecurity & Linux Systems Engineering

| Project | Stack | Description | Link |
|---|---|---|---|
| **FaceLock (`Kali Hello`)** | C (Native PAM `pam_facelock.so`), Python, GTK3, OpenCV (YuNet+SFace ONNX), `fprintd`, `AES-256-GCM` | Windows Hello Face Recognition, Fingerprint, System Password Switcher, Keyring Auto-Unlock & AES-256-GCM Encrypted Folder Vaults for Kali Linux | [`facelockbymuheeb`](https://github.com/Muheebbinnadeem/facelockbymuheeb) |
| **Windows 11 Pro (Dark Green) Theme** | CSS, GTK3, XFCE4, Shell | Complete Kali Linux XFCE desktop transformation with centered 125% taskbar, Start Menu, Quick Settings & Explorer | [`kali-windows-11-dark-green-theme`](https://github.com/Muheebbinnadeem/kali-windows-11-dark-green-theme) |
| **Network Packet Sniffer** | Python, Scapy | CodeAlpha Cybersecurity Task 1 — Live packet capture (IPs, ports, protocols) with Wireshark PCAP export | [`CodeAlpha-CyberSecurity-Task1`](https://github.com/Muheebbinnadeem/CodeAlpha-CyberSecurity-Task1) |
| **Phishing Awareness Trainer** | Python CLI | CodeAlpha Cybersecurity Task 2 — Interactive terminal phishing indicator training & quiz | [`CodeAlpha-Task2-Phishing-Awareness`](https://github.com/Muheebbinnadeem/CodeAlpha-Task2-Phishing-Awareness) |

---

## 4. Agency, E-Commerce & Client Web Portals (`htdocs/` & ByteX Portfolio)

| Project | Domain / Industry | Stack | Highlights |
|---|---|---|---|
| **ByteX Solution Platform** | IT Agency & Cloud | React, TypeScript, Vite, Tailwind, Supabase, Remotion | Agency storefront, Domain Search, Cloud Hosting/VPS catalog, LMS Courses, Blog, Reseller & Client Dashboards ([bytexsolution.com](https://bytexsolution.com)) |
| **3D Developer Portfolio** | Personal Portfolio | React, TypeScript, Three.js (`R3F`), GSAP | Interactive 3D WebGL portfolio experience |
| **GreenChip Travel & Tours** | Travel & Ticketing | Web & Booking Portal | International flight, hotel, tour & visa inquiry platform ([greenchiptravelandtours.com](https://greenchiptravelandtours.com)) |
| **Tiger Group of Companies** | Corporate Conglomerate | PHP, Custom CSS/JS, Admin CMS | Multi-sector corporate portal — Visit Visas, Umrah, Air Ticketing, Tours, Building & E-Stamp ([tigergroupofcompanies.com](http://tigergroupofcompanies.com)) |
| **Flytime Immigration Consultants** | Immigration & Study Abroad | PHP, Custom Admin & API | Study abroad, PR immigration, visit visas, tours & Umrah consultancy portal |
| **STEM Global Consultants** | Education Consultancy | PHP 8 Strict Types, PDO, Admin CMS | Study abroad admissions portal with dynamic country pages & lead submission |
| **Delta Systems Pvt Ltd** | Immigration & Visa | HTML5, CSS3, JS | Study abroad & visit visa corporate site — Gulberg, Lahore ([deltasystemspvtltd.com](https://deltasystemspvtltd.com/)) |
| **Accessories Aura (`aa` / `aa2`)** | E-Commerce | PHP, AJAX Cart, JSON Store, Admin CMS | Full online store with cart, deals, categories, orders, visits & SEO sitemap |
| **D'Samz & Co** | Luxury Jewellery | PHP, Custom CSS/JS, Admin CMS | Luxury jewellery e-commerce with bespoke orders, collection & story pages ([dsamzandco.com](https://dsamzandco.com)) |
| **Asif Trading Lahore** | Kitchen & Hardware B2B | PHP, Admin CMS, JSON Catalog | Importer storefront for Blum Austria slides & Wellmax kitchen hardware ([asiftrading.com.pk](https://asiftrading.com.pk)) |
| **AHK Store** | E-Commerce | PHP, JSON Catalog, Admin CMS | Online store with category filtering & order management |
| **Al-Nayyer Wood Work** | Woodwork & Interior | PHP, Custom JS/CSS, Admin CMS | Service showcase, gallery, uploads & inquiry management ([alnayyerwoodwork.com](https://alnayyerwoodwork.com)) |
| **Maaz Shaikh Portfolio** | Personal Branding | PHP, Responsive UI | Social Media Manager & Content Strategist portfolio + contact handler |
| **Student Registration Records** | Education Utility | PHP, HTML/CSS | Student record creation & registration management |
