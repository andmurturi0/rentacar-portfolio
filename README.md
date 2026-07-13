<div align="center">

# Muli — Rent a Car

**Premium car rental platform built for the Kosovo market.**

A luxury-grade booking and fleet management system, designed and built end-to-end — from the scroll-driven landing experience to the admin analytics dashboard.

[View Live Demo →](#)

</div>

![Muli hero — scroll-driven video landing page](screenshots/hero.png)

---

## 🎯 Overview

Muli is a full-stack web platform for a premium car rental business in Kosovo. Customers browse the fleet through a cinematic, black-and-gold public site and reserve by direct contact, while the owner manages cars, bookings, and revenue through a dedicated Albanian-language admin panel. It replaces phone-and-notebook operations with a single system that handles the entire rental lifecycle — availability, conflict-free bookings, extensions, invoicing, and business analytics.

## ✨ Key Features

- **Scroll-driven video hero** — Apple-style frame-by-frame video scrubbing tied to scroll position, for a cinematic first impression
- **Mobile logo morph animation** — the brand mark fluidly transforms as the user scrolls, keeping the experience polished on every screen size
- **Full booking system with date-conflict detection** — overlapping reservations are impossible; availability is validated against the entire booking calendar
- **Booking extensions with audit trail** — return dates can be extended mid-rental, with every change tracked
- **Dynamic offer & discount pricing** — per-car promotional pricing with automatic discount badges on the public listing
- **Admin analytics dashboard** — revenue charts, fleet occupancy gauge, and top-performing cars at a glance
- **Multi-image galleries with carousel** — swipe-enabled image sliders with primary-image and custom ordering support
- **PDF invoice generation** — professional invoices produced directly from bookings
- **Albanian-language admin panel** — built for the actual operator, in their language
- **Fully responsive** — designed mobile-first, refined on desktop

## 🛠️ Tech Stack

![Laravel](https://img.shields.io/badge/Laravel_12-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Inertia.js](https://img.shields.io/badge/Inertia.js-9553E9?style=for-the-badge&logo=inertia&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase_(PostgreSQL)-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black)

## 📸 Screenshots

> 🎬 Demo video coming soon.

### Public Site

**Car listing — offer pricing, live filters, and availability badges**

![Car listing with offer pricing and filters](screenshots/makinat.png)

### Admin Panel

**Analytics dashboard — revenue trends, fleet occupancy, and top cars**

![Admin analytics dashboard](screenshots/dashboard.png)

**Fleet management — full CRUD with image galleries and quick status switching**

![Admin car management](screenshots/cars.png)

**Bookings — lifecycle management with conflict detection and extensions**

![Bookings management](screenshots/rezervimet.png)

## 🏗️ Architecture Highlights

- **Transaction-safe bookings** — booking creation, car status transitions, and extensions run atomically, so the fleet state can never drift out of sync with the calendar
- **Security-hardened** — license plates hidden from public view, admin routes behind authentication, rate limiting on sensitive endpoints, and hardened HTTP response headers
- **Service-layer architecture** — business rules (availability, pricing, status transitions) live in dedicated services, keeping controllers thin and the domain testable
- **Slug-based, SEO-friendly URLs** — every car gets a clean, human-readable public URL
- **Integer money handling** — all prices stored in cents and converted at the boundary, eliminating floating-point rounding errors
- **Cloud object storage** — car imagery served from S3-compatible object storage, keeping the app server stateless and deploy-friendly

> This repository is a portfolio showcase. The source code is private — if you'd like a walkthrough of the implementation, get in touch below.

## 👋 About the Developer

Full-stack developer and Computer Science student based in **Prishtina, Kosovo**, specializing in premium web platforms built with **Laravel + Vue**. I design and ship complete products — branding, UX, frontend, backend, and deployment.

- 🐙 GitHub: [your-github](#)
- ✉️ Email: [your-email](#)
- 🌐 Portfolio: [your-portfolio](#)

---

<div align="center">
<sub>© Muli Rent a Car · Designed & developed with care in Prishtina 🖤💛</sub>
</div>
