# ☁️ LIGHTCLOUD — Minecraft & VPS Hosting Website

<p align="center">
  <img src="og-image.png" alt="LightCloud" width="640">
</p>

<h3 align="center">Hi, we're LightCloud | Power Your World</h3>

<p align="center">
  Minecraft Hosting • US VPS Plans • Discord Ticket Support • Live Status
</p>

<p align="center">
  <a href="https://lightcloud-gray.vercel.app/"><img src="https://img.shields.io/badge/WEBSITE-LIVE-34d399?style=for-the-badge&logo=vercel&logoColor=white" alt="Website"></a>
  <a href="https://discord.gg/fwXGrVaDeS"><img src="https://img.shields.io/badge/DISCORD-JOIN-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://lightcloud.fitfillo.qzz.io/"><img src="https://img.shields.io/badge/DASHBOARD-OPEN-3b8cff?style=for-the-badge&logo=serverfault&logoColor=white" alt="Dashboard"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/THREE.JS-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js">
  <img src="https://img.shields.io/badge/VERCEL-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
</p>

---

## 🚀 Overview

The official website of **LightCloud**: fast, affordable **Minecraft hosting** and **US VPS** plans, built as a lightweight multi-page site with plain HTML, CSS and JavaScript. No build step, no framework.

A dark, cinematic design with a frosted-glass floating menu, a glowing animated logo, live service status and a simple Discord ticket flow for orders.

---

## ✨ Features

- 🌌 **Cinematic design:** dark eclipse hero background, glowing animated logo, blue glass cards.
- 🧭 **Glass floating menu:** icon dock for Home, Plans, Terms, Payment, Dashboard and Discord.
- 💸 **Plans page:** 11 Minecraft plans and 7 US VPS plans (10% off) with RAM filters and a comparison table.
- 🟢 **Live status:** status pill and section that check the website, dashboard and Discord from the visitor's browser.
- 💳 **Payment page:** UPI QR code, a "Pay with UPI app" button and step-by-step ticket instructions.
- 🎫 **Discord tickets:** every Buy Now and Order button opens the Discord invite.
- 📜 **Terms & Policy:** terms of service, acceptable use, payments and refunds, privacy, uptime and support.
- 👥 **Team section:** owners and developers with avatars and role tags.
- 🔗 **Link previews:** Open Graph image and description for Discord and WhatsApp.
- 📱 **100% responsive:** built mobile first.

---

## 💰 Plans

### ⚡ Light Cloud (Minecraft, Ryzen 7)

| Plan | RAM | CPU | Disk | Price |
|------|-----|-----|------|-------|
| MINI | 1GB | 1 vCPU | 10GB NVMe | ₹10 |
| STARTER | 2GB | 150 | 15GB NVMe | ₹20 |
| BASIC | 4GB | 200 | 25GB NVMe | ₹40 |
| PLUS | 6GB | 250 | 40GB NVMe | ₹70 |
| PRO | 8GB | 300 | 50GB NVMe | ₹130 |
| ULTRA | 12GB | 350 | 70GB NVMe | ₹160 |
| ADVANCED | 16GB | 400 | 90GB NVMe | ₹200 |
| TITAN | 24GB | 450 | 120GB NVMe | ₹250 |
| EXTREME | 32GB | 500 | 160GB NVMe | ₹450 |
| GOD | 48GB | 600 | 200GB NVMe | ₹590 |
| GOD PLUS | 64GB | 800 | 250GB NVMe | ₹699 |

### 🇺🇸 US VPS (10% OFF)

| Plan | RAM | CPU | Disk | Price |
|------|-----|-----|------|-------|
| MINI VPS | 2GB | 1 vCPU | 15GB NVMe | ~~₹60~~ ₹54 |
| STARTER VPS | 4GB | 2 vCPU | 25GB NVMe | ~~₹120~~ ₹108 |
| POWER VPS | 8GB | 4 vCPU | 50GB NVMe | ~~₹240~~ ₹216 |
| PRO VPS | 16GB | 6 vCPU | 100GB NVMe | ~~₹480~~ ₹432 |
| ULTRA VPS | 32GB | 8 vCPU | 200GB NVMe | ~~₹960~~ ₹864 |
| TITAN VPS | 64GB | 12 vCPU | 400GB NVMe | ~~₹1,920~~ ₹1,728 |
| AURA ELITE VPS | 128GB | 16 vCPU | 800GB NVMe | ~~₹3,840~~ ₹3,456 |

All plans include DDoS protection and 24/7 hosting. Minecraft plans also include AetherPanel; VPS plans include full root / SSH access.

---

## 🛠️ Tech Stack

- **Core:** HTML5, CSS3, vanilla JavaScript
- **3D Graphics:** [Three.js](https://threejs.org/) (starfield and pixel moon on inner pages)
- **Hosting:** [Vercel](https://vercel.com/) via GitHub
- **Design:** glassmorphism, CSS animations, inline SVG icons
- **Status checks:** browser `fetch` pings (no backend needed)

---

## 📂 Project Structure

```
lightcloud/
├── index.html      # Home: hero, features, live status, team
├── plans.html      # Minecraft + US VPS plans, filters, compare table
├── payment.html    # UPI QR + create-ticket steps
├── terms.html      # Terms, privacy, refunds, support
├── og-image.png    # Link preview image (Discord / WhatsApp)
├── vercel.json     # Clean URLs: /plans, /terms, /payment
└── README.md
```

---

## ✏️ Editing

| What | Where |
|------|-------|
| Minecraft plans | `PLANS` array in `plans.html` (and the preview cards in `index.html`) |
| VPS plans | `VPS` array in `plans.html` |
| Features | `FEATURES` array in `index.html` |
| Status / uptime | `UPTIME` and `SERVICES` in `index.html` |
| Policy text | `SECTIONS` array in `terms.html` |
| Discord / dashboard links | search for `discord.gg/fwXGrVaDeS` and `lightcloud.fitfillo.qzz.io` |

---

## 🌐 Deploy (Vercel)

1. Put all files at the **top level** of the GitHub repo.
2. Import the repo in [Vercel](https://vercel.com/) (framework: **Other**, no build command).
3. Deploy, then connect your custom domain under **Settings → Domains**.
4. Update the `og:url` and `og:image` links in each page to your final domain.

> ⚠️ File names must be exactly `index.html`, `plans.html`, `terms.html` and `payment.html`, otherwise Vercel shows a 404.

---

## 👥 Team

| Name | Role |
|------|------|
| **@notedingerproyt** | Founder & Owner |
| **zyroxplayyt** | Co-Owner • Panel Dev • Support Helper |
| **Cʀɪᴍsᴏɴ@Pᴀʀᴅᴏɴ </>** | Developer • Web Dev • Bot Dev |

---

## 🔗 Links

- 🌐 Website: https://lightcloud-gray.vercel.app/
- 🎛️ Dashboard: https://lightcloud.fitfillo.qzz.io/
- 💬 Discord: https://discord.gg/fwXGrVaDeS

<p align="center">☁️⚡ <b>LIGHT CLOUD — POWER YOUR WORLD</b> ⚡☁️</p>
