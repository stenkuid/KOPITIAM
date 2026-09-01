# PRD — Website #4: Kopitiam

### Cafe untuk Nongkrong, Bekerja, dan Menikmati Kopi

**Platform:** Astro + Cloudflare  
**Project Type:** Local Cafe / Lifestyle Website  
**Status:** PRD v1.0  

---

# 1. Product Overview

**Kopitiam** adalah cafe yang menawarkan tempat nyaman untuk bekerja, bersantai, dan berkumpul bersama teman.

Produk utama:

* Kopi.
* Minuman non-kopi.
* Cemilan.
* Casual cafe experience.

Nilai utama bisnis bukan hanya makanan dan minuman, tetapi **suasana**.

Website harus menjual pengalaman:

> **Datang untuk kopi, betah karena suasananya.**

Website berfungsi sebagai:

* Digital storefront.
* Menu showcase.
* Brand experience.
* Local discovery channel.
* Informasi lokasi.
* Media untuk meningkatkan kunjungan cafe.

---

# 2. Business Goal

## Primary Goal

Meningkatkan jumlah kunjungan pelanggan ke cafe melalui website.

## Secondary Goals

* Membuat Kopitiam mudah ditemukan melalui Google.
* Menampilkan menu.
* Memperlihatkan suasana cafe.
* Menarik pelanggan yang membutuhkan tempat bekerja.
* Menarik pelanggan yang ingin nongkrong.
* Membangun brand personality.
* Mendorong pelanggan menyimpan atau membagikan lokasi.

---

# 3. Target Customer

## Primary

Usia ±18–35 tahun:

* Mahasiswa.
* Freelancer.
* Remote worker.
* Content creator.
* Young professionals.
* Pasangan muda.
* Komunitas kecil.

## Secondary

* Orang yang ingin meeting informal.
* Teman yang mencari tempat nongkrong.
* Pengunjung yang mencari cafe untuk sore/malam.

---

# 4. Customer Jobs To Be Done

Customer datang ke Kopitiam untuk:

### Work

> "Saya butuh tempat nyaman untuk menyelesaikan pekerjaan."

### Study

> "Saya ingin belajar tanpa merasa terlalu formal."

### Hangout

> "Saya mau nongkrong dengan teman."

### Coffee

> "Saya ingin minum kopi yang enak."

### Relax

> "Saya cuma ingin duduk santai."

Website harus mengakomodasi seluruh kebutuhan tersebut.

---

# 5. Brand Positioning

### Positioning

> **Kopitiam — tempat untuk duduk lebih lama.**

Kopitiam bukan sekadar coffee shop.

Brand promise:

**Good drinks + comfortable space + good company.**

---

# 6. Brand Personality

* Warm.
* Relaxed.
* Social.
* Creative.
* Cozy.
* Modern.
* Welcoming.

Tone of voice:

**Casual, warm, conversational.**

Contoh:

> **Kerja sebentar, ngobrol lama.**

> **Satu meja. Satu kopi. Banyak cerita.**

> **Datang sendiri juga boleh.**

Hindari copy yang terlalu corporate.

---

# 7. Unique Selling Proposition

### Comfortable Workspace

Tempat yang nyaman untuk bekerja atau belajar.

### Warm Atmosphere

Suasana hangat dan relaxing.

### Coffee & Non-Coffee

Pilihan minuman untuk berbagai preferensi.

### Snacks

Cemilan yang cocok menemani pekerjaan atau nongkrong.

### Social Space

Cocok untuk bertemu teman.

---

# 8. Website Objective

Dalam beberapa detik pengguna harus mengetahui:

1. Kopitiam adalah cafe.
2. Tempatnya nyaman.
3. Cocok untuk kerja dan nongkrong.
4. Ada kopi dan non-kopi.
5. Lokasinya di mana.
6. Jam bukanya kapan.

Primary CTA:

**Visit Us**

Secondary:

**View Menu**

---

# 9. Architecture Decision

## Recommended

**Astro Static + Cloudflare Pages**

Tidak membutuhkan database.

Alasan:

* Menu statis.
* Informasi cafe statis.
* Tidak membutuhkan login.
* Tidak membutuhkan booking pada tahap awal.
* Tidak membutuhkan backend.

---

# 10. Technology Stack

* Astro.
* TypeScript.
* Native CSS.
* Minimal JavaScript.
* Cloudflare Pages.

Optional:

* Cloudflare Web Analytics.
* Cloudflare Images/R2 untuk image management jika diperlukan.

Avoid:

* Heavy animation framework.
* Complex booking system.
* CMS besar.
* Client-side state management.

---

# 11. Sitemap

```text
/
├── /menu
├── /about
├── /workspace
├── /location
├── /contact
├── /faq
├── /robots.txt
└── /sitemap-index.xml
```

---

# 12. Homepage Structure

Urutan:

1. Navbar.
2. Hero.
3. Atmosphere Introduction.
4. Menu Highlights.
5. Work With Us.
6. Cafe Gallery.
7. Why Kopitiam.
8. Snacks & Drinks.
9. Testimonials.
10. Location.
11. FAQ.
12. Final CTA.
13. Footer.

---

# 13. Navbar

Logo:

**KOPITIAM**

Navigation:

* Home.
* Menu.
* Workspace.
* About.
* Location.

CTA:

**Visit Us**

Navbar desktop sederhana.

Mobile menggunakan hamburger menu.

---

# 14. Hero

Hero harus menjual **mood**, bukan sekadar makanan.

### Headline

> **Your Table for Coffee, Work & Good Company.**

Supporting copy:

> Tempat nyaman untuk menyelesaikan pekerjaan, ngobrol bersama teman, atau sekadar menikmati kopi dengan tenang.

CTA:

**Explore Menu**

Secondary:

**Find Us**

---

# 15. Hero Visual

Visual utama:

* Interior cafe.
* Warm lighting.
* Coffee on table.
* Laptop.
* Friends chatting.
* Natural environment.

Komposisi harus terasa editorial.

Avoid:

* Generic stock coffee photo.
* Excessive gradients.
* Overloaded UI.

Hero sebaiknya menggunakan satu foto utama yang sangat kuat.

---

# 16. Design Direction

## Concept

**Warm Modern Kopitiam × Contemporary Coffee Space**

Visual:

* Warm.
* Earthy.
* Calm.
* Editorial.
* Premium but approachable.

Bukan:

* Ultra-minimal sterile cafe.
* Generic startup SaaS.
* Neon cyberpunk.
* Excessively rustic coffee shop.

---

# 17. Suggested Color Palette

### Coffee Brown

`#4A3024`

### Warm Cream

`#F4EBDD`

### Dark Charcoal

`#25221F`

### Terracotta

`#B9684B`

### Sage

`#7B8768`

### Soft White

`#FFFDF8`

Primary background:

Warm Cream.

Primary text:

Dark Charcoal.

Accent:

Terracotta.

---

# 18. Typography

Heading:

* Editorial.
* Bold.
* Slightly expressive.

Body:

* Clean sans-serif.

Optional combination:

**Serif display + Sans-serif body**

Maximum 2 font families.

Typography harus menjadi bagian dari atmosphere.

---

# 19. Atmosphere Introduction

Headline:

> **Stay Awhile.**

Copy:

> Kopitiam dibuat untuk hari-hari ketika kamu butuh tempat untuk fokus, bertemu teman, atau sekadar menikmati waktu tanpa terburu-buru.

Visual:

* Interior detail.
* Table setup.
* Coffee cup.
* Warm lamp.

---

# 20. Menu Highlights

Headline:

> **Something for Every Mood**

Kategori:

### Coffee

* Espresso.
* Americano.
* Cafe Latte.
* Cappuccino.
* Signature Coffee.

### Non-Coffee

* Chocolate.
* Matcha.
* Tea.
* Lemon-based drinks.
* Other signature beverages.

### Snacks

* Fries.
* Toast.
* Pastry.
* Light bites.
* Sharing snacks.

Menu contoh harus dianggap sebagai placeholder sampai menu aktual tersedia.

---

# 21. Menu Card

Card:

* Image.
* Product name.
* Description.
* Price.
* Optional category badge.

Contoh:

### Kopitiam Latte

Espresso dengan steamed milk dan rasa yang smooth.

### Signature Chocolate

Minuman cokelat creamy untuk yang tidak minum kopi.

### Kopitiam Fries

Cemilan crispy untuk menemani ngobrol.

Harga tidak boleh dibuat sebagai data nyata jika belum diberikan.

---

# 22. Full Menu Page

`/menu`

Struktur:

### Coffee

Menu kopi.

### Non-Coffee

Menu non-kopi.

### Snacks

Cemilan.

Optional:

### Seasonal

Menu khusus yang tersedia terbatas.

Gunakan filter hanya jika jumlah menu sudah cukup banyak.

Jika menu sedikit, jangan menggunakan filter JavaScript.

---

# 23. Workspace Section

Ini menjadi differentiator utama.

Headline:

> **Bring Your Work. We'll Bring The Coffee.**

Copy:

> Butuh tempat untuk menyelesaikan pekerjaan? Ambil meja, pesan minuman, buka laptop, dan nikmati suasana yang bikin fokus lebih mudah.

Tampilkan:

* Comfortable tables.
* Wi-Fi jika tersedia.
* Power outlets jika tersedia.
* Quiet corners.
* Comfortable seating.

Jangan mengklaim Wi-Fi/outlet jika belum tersedia.

---

# 24. Workspace Information

Buat quick facts:

### Wi-Fi

**Available** jika memang tersedia.

### Power Outlet

**Available** jika memang tersedia.

### Seating

Individual + group seating.

### Atmosphere

Warm and relaxed.

### Suitable For

* Work.
* Study.
* Casual meeting.
* Hangout.

---

# 25. Workspace Etiquette

Jika cafe memang menargetkan remote workers, dapat ditampilkan:

> **Work comfortably, respect the space.**

Contoh:

* Gunakan headphone untuk meeting.
* Jaga volume percakapan.
* Berikan ruang untuk customer lain.
* Jangan memenuhi meja besar sendirian ketika cafe ramai.

Section ini opsional dan hanya digunakan jika sesuai personality brand.

---

# 26. Cafe Gallery

Gallery menjadi elemen penting.

Grid:

* Interior wide shot.
* Coffee close-up.
* Workspace.
* Friends.
* Food.
* Exterior/storefront.

Desktop:

Asymmetrical grid.

Mobile:

Simple vertical grid.

Tidak perlu carousel berat.

---

# 27. Why Kopitiam

Headline:

> **More Than Just Coffee.**

Benefit:

### Comfortable

Tempat untuk duduk lama tanpa terasa terburu-buru.

### Warm

Atmosphere yang membuat pelanggan merasa welcome.

### Flexible

Cocok untuk kerja, belajar, ngobrol, maupun me-time.

### Tasty

Minuman dan cemilan untuk menemani aktivitas.

---

# 28. Social Proof

Jika tersedia:

* Customer testimonials.
* Google rating.
* Customer photos.
* Instagram mentions.

Contoh layout:

> **"Tempatnya nyaman banget buat kerja beberapa jam. Kopinya juga enak."**

Nama customer hanya ditampilkan dengan izin.

Google rating hanya ditampilkan berdasarkan data aktual.

---

# 29. Instagram / Social Section

Headline:

> **See You Around**

Tampilkan visual social content jika tersedia.

CTA:

**Follow Kopitiam**

Jangan embed social media feed berat secara real-time.

Lebih baik gunakan curated images yang mengarah ke social profile.

---

# 30. Location Section

Headline:

> **Come Find Your Table.**

Informasi:

* Address.
* Opening hours.
* Phone.
* Google Maps.
* Parking information jika tersedia.

CTA:

**Get Directions**

Location harus mudah ditemukan dari mobile.

---

# 31. Contact Section

Informasi:

* WhatsApp.
* Phone.
* Email.
* Social media.

Untuk inquiry:

**Ask Us Anything**

CTA:

**Chat With Us**

---

# 32. Reservation

Reservation **tidak menjadi fitur wajib Phase 1**.

Jika cafe tidak menerima reservation:

Jangan menampilkan CTA booking.

Jika reservation diperlukan nantinya, dapat ditambahkan:

* Reservation form.
* WhatsApp booking.
* External reservation provider.

Architecture harus tetap dapat diperluas tanpa mengubah homepage secara besar.

---

# 33. FAQ

Contoh:

### Apakah Kopitiam cocok untuk bekerja?

Ya, selama fasilitas tersebut tersedia.

### Apakah tersedia Wi-Fi?

Jawaban berdasarkan kondisi cafe sebenarnya.

### Apakah tersedia power outlet?

Jawaban berdasarkan kondisi aktual.

### Apakah boleh meeting?

Jelaskan kebijakan cafe.

### Apakah ada makanan selain snack?

Jawab berdasarkan menu aktual.

### Apakah bisa reservasi?

Jawab berdasarkan kebijakan cafe.

---

# 34. Local SEO

Keyword cluster:

* cafe [kota].
* cafe nyaman [kota].
* cafe untuk kerja [kota].
* cafe untuk nongkrong [kota].
* coffee shop [kota].
* cafe WiFi [kota] jika tersedia.
* tempat nongkrong [kota].

Lokasi aktual harus digunakan untuk keyword final.

---

# 35. Metadata

Homepage:

**Kopitiam — Coffee, Work & Good Company**

Local:

**Kopitiam — Cafe Nyaman untuk Kerja & Nongkrong di [City]**

Meta description:

> Kopitiam adalah tempat nyaman untuk menikmati kopi, cemilan, bekerja, belajar, dan nongkrong bersama teman. Lihat menu dan lokasi kami.

---

# 36. Structured Data

Gunakan:

**Cafe / Restaurant / LocalBusiness** yang paling sesuai dengan klasifikasi bisnis aktual.

Properties:

* name.
* address.
* telephone.
* openingHours.
* image.
* servesCuisine.
* priceRange.
* url.
* sameAs.

---

# 37. Open Graph

Implement:

* `og:title`.
* `og:description`.
* `og:image`.
* `og:type`.
* `og:url`.

OG image:

Interior cafe dengan warm lighting atau signature coffee.

---

# 38. Image Strategy

Image adalah salah satu aset conversion terpenting.

Prioritas:

1. Hero interior.
2. Coffee.
3. Workspace.
4. Customers.
5. Food.
6. Exterior.

Gunakan foto asli cafe jika tersedia.

Format:

* AVIF.
* WebP.
* Responsive images.
* Explicit dimensions.
* Lazy loading non-critical.

---

# 39. Mobile UX

Mobile priority:

* Menu mudah ditemukan.
* Location mudah ditemukan.
* CTA Visit Us jelas.
* Gallery tetap menarik.
* Text tidak terlalu panjang.
* Menu cards mudah dibaca.

Optional mobile sticky CTA:

**Get Directions**

atau

**Visit Kopitiam**

---

# 40. Animation

Animation harus subtle.

Allowed:

* Image hover.
* Fade-in.
* Button transitions.
* Navigation transition.

Avoid:

* Floating coffee cups.
* Animated steam everywhere.
* Parallax-heavy sections.
* Video background.
* Complex scroll choreography.

Atmosphere harus berasal dari **photography + typography + layout**, bukan animation.

---

# 41. Accessibility

Requirements:

* Semantic HTML.
* Correct heading hierarchy.
* Keyboard navigation.
* Focus states.
* Image alt text.
* Color contrast.
* Accessible mobile menu.
* Reduced motion support.

---

# 42. Performance

Target:

**Performance ≥90**

**SEO ≥95**

**Accessibility ≥90**

Core Web Vitals:

* LCP ≤2.5s.
* CLS ≤0.1.
* INP ≤200ms.

Gallery harus dioptimalkan dengan ketat.

---

# 43. Cloudflare Architecture

```text
Astro
   ↓
Static Build
   ↓
Cloudflare Pages
```

Tidak ada database.

Tidak ada backend.

Tidak ada Worker runtime pada Phase 1.

---

# 44. Bundle Policy

Harus:

* Static generation.
* Minimal JS.
* Native CSS.
* No heavy slider.
* No animation library.
* No UI framework jika tidak diperlukan.
* Remove unused packages.

Jika Worker ditambahkan nantinya, bundle compressed harus tetap berada di bawah batas Cloudflare yang berlaku.

---

# 45. Recommended Project Structure

```text
src/
├── components/
│   ├── Navbar.astro
│   ├── Button.astro
│   ├── MenuCard.astro
│   ├── GalleryItem.astro
│   ├── InfoCard.astro
│   ├── FAQItem.astro
│   └── Footer.astro
│
├── sections/
│   ├── Hero.astro
│   ├── Atmosphere.astro
│   ├── MenuHighlights.astro
│   ├── Workspace.astro
│   ├── Gallery.astro
│   ├── WhyKopitiam.astro
│   ├── SocialProof.astro
│   ├── SocialSection.astro
│   ├── Location.astro
│   ├── FAQ.astro
│   └── FinalCTA.astro
│
├── layouts/
│   └── BaseLayout.astro
│
├── pages/
│   ├── index.astro
│   ├── menu.astro
│   ├── workspace.astro
│   ├── about.astro
│   ├── location.astro
│   ├── contact.astro
│   ├── faq.astro
│   ├── robots.txt.ts
│   └── sitemap-index.xml.ts
│
├── data/
│   ├── business.ts
│   ├── menu.ts
│   └── faq.ts
│
├── styles/
│   └── global.css
│
└── assets/
```

---

# 46. Data Architecture

### Menu

```text
menuItem
├── slug
├── name
├── category
├── description
├── price
├── image
├── featured
└── available
```

### Business

```text
business
├── name
├── address
├── phone
├── whatsapp
├── email
├── openingHours
├── mapsUrl
└── socialLinks
```

### Facilities

```text
facilities
├── wifi
├── powerOutlet
├── workspace
├── parking
└── reservation
```

Dengan data-driven architecture, perubahan fasilitas tidak membutuhkan perubahan component.

---

# 47. Analytics

Gunakan:

**Cloudflare Web Analytics**

Track:

```text
view_menu
click_menu_item
click_direction
click_contact
click_social
```

Tujuan utama analytics:

Mengetahui apakah website benar-benar menghasilkan kunjungan.

---

# 48. Security

Static website memiliki attack surface rendah.

Jika contact form digunakan:

* Validate input.
* Rate limiting.
* Spam protection.
* Cloudflare Turnstile bila dibutuhkan.
* Jangan menyimpan data pelanggan tanpa kebutuhan.

---

# 49. Out of Scope

Tidak termasuk:

* Online ordering.
* Online payment.
* Customer account.
* Loyalty system.
* Table reservation system.
* Delivery system.
* Admin dashboard.
* CMS.
* Database.
* Real-time Instagram feed.
* Heavy social media embeds.

---

# 50. Future Expansion

## Phase 2

* Reservation.
* Event booking.
* Private room booking.
* Menu ordering.
* Promotional landing pages.

## Phase 3

Jika booking/order berkembang:

* Cloudflare Workers.
* D1.
* Admin dashboard.
* Reservation management.

---

# 51. Acceptance Criteria

## Brand

* [ ] Kopitiam terasa warm.
* [ ] Visual memiliki atmosphere kuat.
* [ ] Website tidak terasa seperti coffee shop template.
* [ ] Brand personality konsisten.

## Experience

* [ ] Pengunjung memahami cafe cocok untuk work/hangout.
* [ ] Gallery memperlihatkan ambience.
* [ ] Menu mudah ditemukan.
* [ ] Location mudah ditemukan.

## Conversion

* [ ] Visit Us CTA jelas.
* [ ] Get Directions tersedia.
* [ ] Contact mudah.
* [ ] Menu accessible dari hero/navbar.

## SEO

* [ ] LocalBusiness schema.
* [ ] Metadata.
* [ ] Canonical.
* [ ] Sitemap.
* [ ] Robots.
* [ ] Open Graph.
* [ ] Local keywords.

## Performance

* [ ] Lighthouse Performance ≥90.
* [ ] SEO ≥95.
* [ ] Accessibility ≥90.
* [ ] Core Web Vitals optimized.
* [ ] Images optimized.

## Technical

* [ ] Astro build successful.
* [ ] Cloudflare Pages compatible.
* [ ] Minimal JS.
* [ ] No unnecessary dependencies.
* [ ] No broken links.
* [ ] No console errors.

---

# 52. Implementation Blueprint

## Website Goal

Membangun website cafe yang menjual **pengalaman Kopitiam**, bukan hanya daftar menu.

Core idea:

> **Coffee, work, friends, and time well spent.**

## Architecture

**Astro Static + Cloudflare Pages**

## Sitemap

```text
/
├── /menu
├── /workspace
├── /about
├── /location
├── /contact
├── /faq
├── /robots.txt
└── /sitemap-index.xml
```

## Design Direction

**Warm Modern Kopitiam × Contemporary Coffee Space**

## Core Components

* Navbar.
* Hero.
* Atmosphere section.
* Menu cards.
* Workspace section.
* Gallery.
* Social proof.
* Location.
* FAQ.
* Final CTA.
* Footer.

## Technical Requirements

* Astro.
* TypeScript.
* Static generation.
* Minimal JavaScript.
* Optimized photography.
* Data-driven menu.
* Local SEO.
* Cafe/LocalBusiness schema.
* Sitemap.
* Robots.
* Open Graph.
* Cloudflare Pages.

---

# 53. Antigravity Execution Plan

## Prompt 1 — Analysis

> You are a senior full-stack engineer. Analyze the Kopitiam cafe website PRD before writing production code. Determine the Astro static architecture, reusable component system, menu data model, facility data model, SEO structure, image strategy, responsive behavior, and implementation checklist. Do not invent features or infrastructure not required by the PRD.

Output:

* Architecture choice.
* Component plan.
* Data model.
* SEO plan.
* Image plan.
* Implementation checklist.

---

## Prompt 2 — Build

> You are a senior full-stack engineer. Build the Kopitiam cafe website according to the provided PRD. Use Astro static generation, reusable components, data-driven menu content, optimized responsive photography, minimal client-side JavaScript, semantic HTML, and Cloudflare Pages compatibility. The visual experience must feel warm, editorial, comfortable, and premium while remaining approachable. Do not add unnecessary dependencies, features, animations, or backend systems.

Implement:

* Homepage.
* Menu.
* Workspace.
* About.
* Location.
* Contact.
* FAQ.
* Gallery.
* Local SEO.
* Structured data.
* Responsive design.

---

## Prompt 3 — Optimization

> You are a senior full-stack engineer preparing the Kopitiam website for production. Audit the complete implementation for build reliability, performance, accessibility, SEO, image optimization, responsive behavior, broken links, JavaScript usage, dependency size, and Cloudflare Pages compatibility. Fix all issues without changing the product requirements or adding unnecessary features.

Check:

### Build

* Production build.
* Type checking.
* Broken links.
* Console errors.

### Performance

* LCP.
* CLS.
* INP.
* Image sizes.
* JS payload.
* CSS payload.
* Bundle analysis.

### SEO

* Metadata.
* Canonical.
* LocalBusiness schema.
* Sitemap.
* Robots.
* Open Graph.

### UX

* Mobile navigation.
* Menu discovery.
* Location CTA.
* Gallery responsiveness.
* Accessibility.

### Cloudflare

* Static output.
* Pages compatibility.
* Dependency audit.
* No unnecessary Worker runtime.

Output:

**Deployment-ready Astro project.**

---

# 54. Final Product Definition

Kopitiam v1 bukan sekadar website untuk mengatakan:

**"Kami menjual kopi."**

Website harus menyampaikan:

> **"Ini tempat yang ingin kamu datangi, duduki, dan nikmati waktumu."**

Customer journey:

**See Atmosphere → Imagine Yourself There → Explore Menu → Check Location → Visit**

Prioritas:

**Atmosphere > Experience > Menu > Location > Trust > SEO > Performance**

**Database:** Tidak diperlukan.

**Backend:** Tidak diperlukan.

**Framework:** Astro.

**Hosting:** Cloudflare Pages.

**Primary CTA:** Visit Us.

**Secondary CTA:** View Menu.

**Core Message:**
**"Datang untuk kopi, betah karena suasananya."**

---

# AI DEVELOPMENT & DESIGN CONTROL PROTOCOL

## Project Protocol

This document defines the mandatory operating rules for all AI agents working on this project.

All instructions in this file must be read and followed before modifying any project file.

The primary purpose of this protocol is to preserve approved design states, prevent unintended redesigns, control AI modifications, and provide a predictable command system for development.

---

# 1. CORE PRINCIPLE

The AI agent must treat the existing approved project state as valuable and protected.

The AI must NEVER assume that an existing implementation should be improved, modernized, refactored, redesigned, simplified, or replaced unless the user explicitly requests it.

When the user's request is narrow, the modification must remain narrow.

The AI must preserve:

- Existing approved layouts
- Existing visual hierarchy
- Existing typography
- Existing spacing
- Existing colors
- Existing images
- Existing responsive behavior
- Existing interactions
- Existing functionality

unless explicitly instructed otherwise.

---

# 2. PROTOCOL PRIORITY

When interpreting instructions, use the following priority order:

1. Explicit user instruction
2. Active protocol command
3. Locked component rules
4. Approved checkpoint rules
5. Existing project implementation
6. General design or coding preferences

The AI must not override a higher-priority instruction with a lower-priority assumption.

---

# 3. BEFORE EVERY MODIFICATION

Before modifying any file, the AI must:

1. Read this `PROTOCOL.md`.
2. Identify the active protocol command.
3. Identify the exact component or files that need modification.
4. Check whether the target component is locked.
5. Preserve all unrelated components.
6. Avoid modifying files that are outside the requested scope.

The AI must NOT begin a broad redesign simply because a requested change affects part of the page.

---

# 4. MINIMAL CHANGE PRINCIPLE

The AI must make the smallest reasonable modification necessary to fulfill the user's request.

The AI must NOT:

- Rewrite unrelated components.
- Refactor unrelated code.
- Change the design system.
- Replace existing layouts without permission.
- Change typography without permission.
- Change spacing without permission.
- Replace images without permission.
- Change colors without permission.
- Modify responsive behavior outside the requested scope.
- Remove functionality unless explicitly requested.

If a requested modification can be completed by changing one component, the AI must not rewrite the entire page.

---

# 5. DESIGN PRESERVATION RULE

Existing design is considered protected by default.

The AI must NOT interpret requests such as:

- "Improve this"
- "Make this better"
- "Fix this"
- "Add this feature"

as permission to redesign unrelated sections.

If the request does not explicitly request redesign, preserve the existing visual appearance.

---

# 6. EXACT RESTORATION RULE

When restoring a previous state, the AI must restore the exact known implementation.

The AI must NOT:

- Recreate the design from memory.
- Generate a similar design.
- Approximate the previous layout.
- Improve the previous version.
- Modernize the previous version.
- Combine the previous design with the current design.

Restoration means restoring the previous code state as accurately as possible.

The AI must always prefer:

1. Git history
2. Git commit
3. Git diff
4. Existing backup
5. Explicit checkpoint reference

The AI must never guess the previous implementation if an exact source is available.

---

# 7. PROTOCOL COMMAND SYSTEM

Commands beginning with `/` are protocol commands.

Protocol commands must be interpreted according to this document.

The AI must execute the command according to its definition.

The AI must not reinterpret the meaning of a protocol command.

---

# 8. /REVERSE

## Purpose

Undo the latest unapproved modification.

## Execution Rules

When `/REVERSE` is activated:

1. Identify the latest modification made for the current task.
2. Identify all files affected by that modification.
3. Restore those files to their exact state before that modification.
4. Preserve all older approved changes.
5. Do not redesign anything.
6. Do not generate an alternative implementation.
7. Do not improve the restored version.
8. Do not modify unrelated files.

The AI must treat `/REVERSE` as:

"Restore the exact previous state."

The AI must NOT interpret `/REVERSE` as:

"Create something similar to the previous design."

After restoration, stop modifying the project unless the user provides another instruction.

---

# 9. /CHECKPOINT [NAME]

## Purpose

Create a named approved state.

Example:

`/CHECKPOINT homepage-v1`

When activated:

1. Identify the current project state.
2. Record the checkpoint name.
3. Record the relevant files associated with the checkpoint.
4. Record the purpose of the checkpoint.
5. Treat this state as an approved reference.

A checkpoint should preferably correspond to a Git commit whenever possible.

---

# 10. /RESTORE [NAME]

## Purpose

Restore a previously approved checkpoint.

Example:

`/RESTORE homepage-v1`

When activated:

1. Locate the exact checkpoint.
2. Identify its associated files or Git commit.
3. Restore the exact code state.
4. Do not reinterpret the design.
5. Do not merge the checkpoint with experimental changes unless explicitly requested.

The checkpoint is the source of truth.

---

# 11. /LOCK [COMPONENT]

## Purpose

Protect an approved component from modification.

Example:

`/LOCK HERO`

When a component is locked, the AI must NOT modify:

- Layout
- HTML structure
- CSS styling
- Typography
- Spacing
- Colors
- Images
- Animations
- Responsive behavior
- Component logic

unless explicitly instructed.

Example:

`/LOCK HERO`

means the Hero section must remain unchanged.

---

# 12. /UNLOCK [COMPONENT]

## Purpose

Remove protection from a previously locked component.

Example:

`/UNLOCK HERO`

Only after this command may the AI freely modify the specified component according to the user's instructions.

Unlocking one component does not unlock other components.

---

# 13. /STRICT

## Purpose

Enable strict modification mode.

When `/STRICT` is active:

- Modify only explicitly requested components.
- Modify only files required to complete the request.
- Do not refactor unrelated code.
- Do not redesign unrelated sections.
- Do not optimize unrelated components.
- Do not modify the design system.
- Do not make "helpful" visual changes.
- Preserve all existing behavior unless explicitly instructed otherwise.

The AI must prioritize precision over creativity.

---

# 14. /DESIGN-ONLY

## Purpose

Allow visual modifications while protecting application functionality.

The AI may modify:

- Layout
- Typography
- Spacing
- Colors
- Visual hierarchy
- Animation
- Responsive styling

The AI must NOT modify:

- Business logic
- API integrations
- Routing
- Data structures
- Application logic

unless explicitly requested.

---

# 15. /CODE-ONLY

## Purpose

Modify functionality while preserving the visual design.

When `/CODE-ONLY` is active, the existing visual design must remain unchanged.

The AI must NOT modify:

- Layout
- Typography
- Colors
- Spacing
- Images
- Animation
- Visual hierarchy

unless explicitly requested.

---

# 16. /WA

## Purpose

Activate the WhatsApp Floating Action Button protocol.

When `/WA` is activated:

1. Add a floating WhatsApp contact button.
2. Position it appropriately without obstructing important UI.
3. Use fixed positioning.
4. Ensure responsive behavior.
5. Ensure mobile safe-area compatibility.
6. Ensure the button is touch-friendly.
7. Use the existing design language.
8. Do not redesign the page.
9. Do not modify unrelated sections.
10. Do not change existing layout structure.

The WhatsApp button must be implemented as an isolated component whenever practical.

---

# 17. /REMOVE-WA

Remove the WhatsApp floating button and all directly associated implementation.

Do not modify unrelated components.

---

# 18. /SCOPE [COMPONENT OR FILE]

## Purpose

Restrict all modifications to a specific scope.

Example:

`/SCOPE HERO`

or:

`/SCOPE src/components/Hero.astro`

When active:

The AI may only modify the specified component or file.

Any required modification outside the scope must first be identified and explained.

The AI must not silently modify files outside the active scope.

---

# 19. /FREEZE-DESIGN

## Purpose

Freeze the entire visual design.

When active, the AI may modify functionality but must preserve the exact visual appearance.

The AI must NOT change:

- Layout
- Typography
- Spacing
- Colors
- Images
- Animations
- Component positioning

unless explicitly instructed.

---

# 20. /EXPERIMENT

## Purpose

Allow experimental changes without treating them as approved.

Experimental changes must be considered temporary.

The AI must:

1. Avoid modifying locked components.
2. Avoid modifying unrelated files.
3. Keep changes isolated whenever possible.
4. Clearly identify experimental files.
5. Preserve the ability to reverse the experiment.

Experimental work must not automatically replace an approved checkpoint.

---

# 21. APPROVAL SYSTEM

A modification becomes an approved reference only when the user explicitly approves it.

Examples:

- `APPROVED`
- `/CHECKPOINT homepage-v2`
- "This version is approved."
- "Keep this design."

Until explicit approval is given, major design modifications should be considered experimental.

---

# 22. DO NOT GUESS RULE

If the AI does not know which previous version the user means, the AI must NOT invent or recreate a design.

The AI must:

1. Inspect Git history.
2. Inspect recent changes.
3. Inspect checkpoints.
4. Inspect available project history.

Only if no previous state exists should the AI ask the user for clarification.

The AI must never silently guess.

---

# 23. CHANGE REPORT

After completing a modification, the AI must provide a concise report containing:

### Modified

List modified files.

### Preserved

List important components intentionally left unchanged.

### Protocol

State which protocol commands were active.

### Reversal

Explain how the change can be reversed.

The report should remain concise.

---

# 24. STOP CONDITION

After successfully completing the requested task, the AI must stop.

The AI must NOT continue with:

- Additional redesign
- Optional improvements
- Unrequested refactoring
- Additional feature development
- Visual experimentation

unless explicitly requested.

Completion means completion.

---

# 25. DEFAULT SAFE MODE

If no explicit protocol command is provided, the AI must operate in:

`SAFE MODE`

SAFE MODE rules:

- Preserve existing design.
- Preserve existing functionality.
- Make minimal modifications.
- Do not redesign unrelated components.
- Do not refactor unrelated code.
- Do not replace approved implementation.
- Prefer isolated changes.
- Treat ambiguity as a reason to inspect project history, not as permission to guess.

---

# 26. FINAL OPERATING INSTRUCTION

The AI agent must follow this principle:

"Preserve first. Modify second. Never redesign without permission. Never guess a previous state when an exact state can be restored."

The existing project is the source of truth.

User-approved checkpoints are protected states.

Protocol commands must be followed literally.

Precision is more important than creativity.
