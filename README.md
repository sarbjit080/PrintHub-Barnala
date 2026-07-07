# 🖨️ PrintHub Barnala - Online Printing & Live Admin Portal

An automated, serverless web application designed for **PrintHub Barnala** (located near the Bus Stand, Barnala, Punjab). This system allows local customers to seamlessly upload order details and drop their print files directly via WhatsApp, while providing store operators with a secure, real-time live synchronization queue management dashboard.

---

## 🚀 Key Features

* **Instant Document Order Form:** Customers can submit their name, phone number, print configurations (Black & White, Color, Passport Photos, Lamination Work), copy count, and specific instructions.
* **Smart File Name Tracking:** Captures and pushes the exact selected file attachment name directly to the database for seamless matching inside the operator's chat layout.
* **Secure Staff Master Terminal:** A hidden, protected admin panel accessed directly from the footer credentials trigger, tracking statistics (Total, Pending, Completed, Cancelled).
* **Live Database Synchronization:** Powered by Firebase Realtime Database to instantly listen to inbound client print streams without needing to refresh the page.
* **One-Click WhatsApp Billing & Status Alerts:** Shortcuts to instantly forward complete structural text payloads to the shop's active WhatsApp business line (+91 9653602820) or dispatch instant pickup alerts back to the client.

---

## 🛠️ Tech Stack & Frameworks

* **Frontend:** HTML5, Tailwind CSS (via CDN), FontAwesome Icons v6.4.0 (via Cloud CDN).
* **Database & Auth backend:** Google Firebase Realtime Database & Firebase Authentication Engine (v12.15.0 Modules).
* **Communication Routing:** WhatsApp Business API Cloud Gateway Links (`wa.me`).

---

## 📂 Deployment Configuration Checklist

When migrating or hosting this system live (e.g., via Linux environments like InfinityFree), ensure the structural rules below are carefully followed to avoid server execution blocks:

1. **Root Directory Placement:** The home script file must be named strictly in lowercase as `index.html` and uploaded directly inside the public-facing application directory folder (e.g., `/htdocs/`). Sitting outside this architecture triggers a `403 Forbidden` block.
2. **Firebase Credential Setup:** Make sure your configuration key variables inside the core `<script type="module">` tag accurately align with your active console keys (`printhub-barnala-1`).
3. **Admin User Generation:** Ensure your authorized operational email and master password configurations are manually generated inside your Firebase Authentication project dashboard panel before verifying logins.

---

## 📜 How the Print Workflow Operates


