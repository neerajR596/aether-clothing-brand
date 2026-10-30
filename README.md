# AETHER & CO. — Haute Couture & Modern Silhouette

[![MERN Stack](https://img.shields.io/badge/Stack-MERN-gold.svg)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Bundler-Vite_6-646CFF.svg)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind_CSS_3.4-38B2AC.svg)](https://tailwindcss.com/)

An immersive, soothing high-fashion luxury clothing e-commerce web platform designed with high aesthetic restraint and tactile visual appeal. Built from scratch with the full **MERN stack** (MongoDB, Express, React 18, Node.js), featuring runway model photography, slide-over cart drawer, instant atelier search, guest/member multi-option checkout, user profile dossiers, and an executive administration suite.

---

## 📸 Visual Showcase & Previews

### 1. The Runway Editorial Showcase (Hero Experience)
> Deep obsidian theme (`#0d0d11`), Cormorant Garamond serif typography, and ambient lighting designed to keep clients immersed in exploring the garments.

```
+---------------------------------------------------------------------------------------+
|  COLLECTIONS   WOMEN   MEN   OUTERWEAR   OBJECTS     [ AETHER & CO. ]     🔍  ♡  👤  🛍️(2) |
+---------------------------------------------------------------------------------------+
|                                                                                       |
|                               SILENCE IN SILHOUETTE.                                  |
|                             Poetry in Pure Cashmere.                                  |
|                                                                                       |
|   Designed for those who understand luxury without loudness. Mastercrafted from        |
|          pure Grade-A Mongolian cashmere and 25-momme fluid mulberry silk.            |
|                                                                                       |
|                    [ EXPLORE COLLECTION ]     [ THE TRENCH ARCHIVE ]                  |
|                                                                                       |
+---------------------------------------------------------------------------------------+
```

### 2. High-Fashion Garment Product View
- Multi-angle high-resolution model photography.
- Dynamic swatch palette selection & size selectors.
- Instant slide-over cart with live quantity & total calculations.

### 3. Multi-Channel Luxury Checkout
- **Credit / Debit Cards:** Simulated card verification with 256-bit TLS indicators.
- **Digital Wallets:** Apple Pay & Google Pay.
- **Private Wire Transfer:** Direct invoice settlement for large acquisitions.
- **Cash on Delivery:** Direct courier payment at doorstep.
- Instant acquisition dossier with unique order ID and live tracking code (`AET-XXXXXX`).

### 4. Director Administration Console (`/admin`)
- Real-time revenue, catalogue size, and courier metrics.
- Complete CRUD controls: publish new haute couture pieces with custom sizes, materials, prices, and model photos.
- Order management: inspect client orders and change statuses (*Processing*, *Confirmed*, *Dispatched*, *Delivered*).

---

## 🛠️ Architecture & Tech Stack

| Layer | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | React 18, React Router v6, Lucide Icons | Responsive SPA with client state & context |
| **Styling** | Tailwind CSS, Cormorant Garamond & Plus Jakarta Sans | Custom luxury dark palette & typography |
| **Build Tool** | Vite 6 | Sub-second hot module reloading |
| **Backend API** | Node.js, Express.js (ES Modules) | RESTful API with token authentication |
| **Database** | MongoDB & Mongoose | Flexible schemas for Users, Products, and Orders |
| **State / Cache** | React Context (`AuthContext`, `CartContext`) | Local storage sync & instant cart updates |

---

## 🔑 Demo Access Credentials

| Account | Email | Password | Permissions |
| :--- | :--- | :--- | :--- |
| **Atelier Director (Admin)** | `admin@aether.luxury` | `adminpassword123` | Full access to `/admin` catalogue & orders |
| **Private Client** | `client@aether.luxury` | `password123` | Browse, cart, checkout, profile dossier |
