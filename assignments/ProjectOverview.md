
# Lloyd's Beach Bar – Final Report  
_Vito Strahinjić_

## Table of Contents  
1. Introduction  
2. Target Users & UX Design  
3. Project Development Overview  
4. Features & Technologies  
5.  Design Principles Used – CRAP
6. Hosting & Performance  
7. Final Thoughts  

---

## 1. Introduction

Lloyd's Beach Bar website was designed to replace traditional printed menus and offer a more engaging digital experience for guests at the bar. Visitors access the site by scanning a **QR code** on their table, landing on a clean and welcoming homepage.

The goal: **Make browsing the drink menu easy and fun**, while also allowing space for events, games, blog content, and multilingual support.

The landing page greets users with beachy visuals, short text prompts, and a CTA:
> _"Ready for a Round?" – View Our Menu_

The website was made to reflect the actual vibe of the bar: chill, vibrant, and social.  

---

## 2. Target Users & UX Design

To guide the design, I created 3 key **user personas**, based on typical visitor demographics:

### 🧑‍🎓 Alex – The Social Student (Age 22)
- Wants discounts, games, and fun UI
- Tech-savvy, visits with friends
- Motivated by interactive features and shareable offers

### 👩 Mia – The Curious Weekender (Age 43)
- Looking for info on drinks, ambiance, and events
- Likes simple games for small rewards
- Needs clear navigation and visuals

### 👴 Robert – The Relaxed Senior (Age 68)
- Focused on simplicity and readability
- Not interested in games, just clear pricing and seating info
- Needs large text, minimal interactions

These personas shaped the navigation and page structure — the site is built to be **fast, intuitive, and accessible**, even for low-tech users.

---

## 3. Project Development Overview

Instead of using a starter template, I began the build **from scratch over the holidays**, implementing:

- A fully responsive layout using **Tailwind CSS**
- Custom animations and transitions
- Mobile-first design principles

### Key Milestones  
- 🧭 Created sitemap based on card sorting & user journeys  
- 🛠️ Built reusable components in **Next.js**  
- 🌍 Integrated internationalization (EN/HR)  
- 🍹 Designed a flexible Sanity schema for product management  

All content, menus, and posts are editable via **Sanity CMS**, allowing staff to manage updates without touching the code.

---

## 4. Features & Technologies

### ✨ Core Features
- Interactive drinks menu
- Blog with dynamic posts
- Events & gallery sections
- Language toggle (EN/CRO)
- Login system (for private content)

### 🔧 Technologies Used
- **Next.js 15** (App Router)
- **Tailwind CSS** for styling
- **Sanity.io** for CMS & live data editing
- **Next-Intl** for localization
- **Netlify** for deployment

---

## 5. Design Principles Used – CRAP

To support intuitive and accessible user experience, the interface was designed with the **CRAP design principles** in mind:

#### Contrast
- Strong visual contrast between elements (e.g., white text on dark backgrounds, dark text on light cards) ensures readability across all user demographics.
- Interactive elements like buttons and links stand out clearly with bold colors and hover states.

#### Repetition
- Consistent styling of components (buttons, section headers, icons) helps users recognize recurring patterns and navigate with ease.
- Spacing, font sizes, and section layouts follow a consistent rhythm to reinforce familiarity.

#### Alignment
- All UI elements are neatly aligned using Tailwind’s grid and flexbox utilities, providing a clean and professional layout.
- Text, icons, and buttons are aligned to guide the eye smoothly through each section without confusion.

#### Proximity
- Related content (e.g., drink name + description + price) is grouped closely to indicate association.
- Adequate spacing is used to separate unrelated content blocks, reducing clutter and improving scan-ability.

> By applying these principles throughout the site, the interface becomes both functional and aesthetically pleasing — reinforcing trust and usability for every visitor, whether they’re a tech-savvy student or a retired tourist.


---

## 6. Hosting & Performance

The site is hosted on **Netlify**, with the official domain [lloyd.hr](https://lloyd.hr), provided through **CARNET** (for verified Croatian businesses).

### ✅ Deployment details:
- Production URL: [https://lloyd.hr](https://lloyd.hr)
- CMS studio is connected to Sanity for real-time content editing
- Uses ISR/SSG for fast loading

### 📊 Performance
- Optimized images via Next/Image
- Responsive layout built from mobile up
- Pagespeed tested (results included in attachments)

![Desktop performance](https://github.com/vstrah00/HCI-2024-25/blob/main/assignments/perf1.png?raw=true)

![Mobile performance](https://github.com/vstrah00/HCI-2024-25/blob/main/assignments/perf2.png?raw=true)
---

## 7. Final Thoughts

This project was built as a **real, production-grade website**, not a prototype. It is actively used by guests and updated by bar staff. Features like coupon-based games and the blog system are yet to be perfected, to give this web app life beyond just showing a menu.

I'm proud of how far the site came from a blank canvas — it's fast, clean, and supports real use cases from actual customers sitting by the sea.



