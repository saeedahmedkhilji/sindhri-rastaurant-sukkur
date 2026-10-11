# 👑 Sindhri Restaurant Sukkur — Official Online Portal

A luxury, high-performance website and digital ordering portal for **Sindhri Restaurant Sukkur**, built with modern HTML5, CSS3, vanilla JavaScript, and connected to **Supabase PostgreSQL backend**.

---

## 📌 Project Overview

- **Brand:** Sindhri Restaurant Sukkur
- **Heritage:** Serving Royal Sindhi Dishes, Live Charcoal Bar B.Q, and Indus River Specialties since 1985 / 2004
- **Owner Contact Number:** `03121786110` (Direct Helpline & WhatsApp Hotline)
- **Location:** Shikarpur Road / Sukkur Bypass, Sukkur, Sindh, Pakistan
- **Google Maps Location:** [Sindhri Restaurant Sukkur on Google Maps](https://maps.app.goo.gl/FSDA99xuzyKZUFZKA)
- **Backend Database:** Supabase (`https://iahskgtltdehpmpmhkdm.supabase.co`)

---

## 📂 File & Directory Architecture

```text
sindhri Restaurant Sukkur/
├── index.html                   # Luxury flagship landing page with Before/After sliders
├── menu.html                    # 17+ dish interactive digital menu with filters & cart
├── reservation.html             # VIP table & family hall reservation portal
├── gallery.html                 # Modern street & ambience gallery with lightbox
├── contact.html                 # Contact details, owner hotline, and Google Maps embed
├── favicon.svg                  # Vector gold monogram icon
├── css/
│   ├── style.css                # Master theme, typography, header, hero, footer
│   ├── components.css           # Dish cards, cart drawer, modals, sliders, buttons
│   └── responsive.css           # Mobile, tablet, and desktop media queries
├── js/
│   ├── config.js                # Supabase configuration, restaurant constants, owner info
│   ├── supabase-client.js       # Supabase client service with fail-safe local fallback
│   ├── menu-data.js             # Digitized 17+ dish master dataset with prices (PKR)
│   ├── cart.js                  # Shopping cart, checkout, and direct WhatsApp formatting
│   └── app.js                   # Navigation, interactive sliders, forms, modals, lightbox
├── database/
│   ├── schema.sql               # Supabase PostgreSQL schema with Row Level Security (RLS)
│   └── seed.sql                 # Sample dishes & verified Sukkur diner reviews
└── assets/
    ├── brand/
    │   ├── sindhri-logo-gold.jpg # Modern luxury gold foil embossed emblem
    │   └── sindhri-logo.svg      # Scalable vector logo with laurel wreath & monogram
    ├── images/
    │   ├── sindhri-hero-feast.jpg
    │   ├── sindhri-modern-street.jpg
    │   ├── restaurant-patio-heritage.jpg
    │   ├── dish-indus-fish.jpg
    │   ├── dish-seekh-kebabs.jpg
    │   ├── dish-karahi.jpg
    │   ├── dish-white-handi.jpg
    │   ├── dish-continental-rice.jpg
    │   ├── dish-soup-fry.jpg
    │   ├── dish-mitho-lolo.jpg
    │   ├── dish-mint-margarita.jpg
    │   ├── dish-karak-chai.jpg
    │   └── street-heritage-view.jpg
    └── raw/                     # Original photos & historical references
```

---

## ⚡ Supabase Backend Integration

The application connects to your Supabase project:
- **Project URL:** `https://iahskgtltdehpmpmhkdm.supabase.co`
- **Project Reference:** `iahskgtltdehpmpmhkdm`
- **Anon Public API Key:** Pre-configured in `js/config.js`

### How to Initialize the Database in Supabase:
1. Log in to [Supabase Dashboard](https://supabase.com/dashboard/project/iahskgtltdehpmpmhkdm).
2. Go to the **SQL Editor** on the left menu.
3. Open `database/schema.sql` from this folder, copy all contents, and click **Run**.
4. Next, open `database/seed.sql`, copy all contents, and click **Run**.
5. Your database tables (`menu_items`, `orders`, `reservations`, `customer_reviews`, `contact_inquiries`) and RLS policies are now live!

> **Note:** The website has built-in offline resiliency. Even before running the SQL scripts, the menu, shopping cart, reservations, and WhatsApp dispatch work seamlessly with local caching!

---

## 📲 Direct WhatsApp Ordering to Owner (`03121786110`)

When a customer checks out or reserves a table, the system automatically formats a complete itemized bill and dispatches it straight to the owner's WhatsApp number `03121786110`:

```text
*👑 SINDHRI RESTAURANT SUKKUR - NEW ORDER*
*Order Code:* #SR-492102
---------------------------------------
*Customer:* Asad Ali
*Phone:* 0312-XXXXXXX
*Order Type:* DELIVERY
*Delivery Address:* Minara Road, Sukkur
---------------------------------------
*ITEMS ORDERED:*
• 1x Special Indus River Palla Fish (Full Fish) = Rs 1,950
• 2x Melt-in-Mouth Chicken Reshmi Kebab (4 Skewers) = Rs 1,900
• 1x Authentic Sindhi Mitho Lolo = Rs 420
---------------------------------------
*Subtotal:* Rs 4,270
*Delivery Fee:* FREE
*TOTAL AMOUNT:* Rs 4,270
*Special Notes:* Medium spicy, send fresh mint chutney
---------------------------------------
_Sent via Sindhri Restaurant Sukkur Online Portal_
```

---

## 🌟 Key Features

1. **Brand Identity Evolution:**
   - Transformed the historic circular logo into a modern **3D embossed gold emblem** with laurel wreath branches and royal monogram `S`.
   - Included clean SVG vector graphics for razor-sharp rendering at all display resolutions.

2. **Modern Street Architecture Showcase:**
   - Interactive Before/After slider contrasting the historic Sukkur street view with the modern illuminated glass façade and open-air patio boulevard.

3. **Complete Digital Menu with Live Search & Filtering:**
   - Filter by: River Fish, Charcoal BBQ, Shinwari Karahi & Handi, Rice & Breads, Soups & Starters, Desserts & Drinks.
   - Real-time search bar with instant dish filtering.

4. **Cart Drawer & Checkout:**
   - Real-time price calculations with support for delivery, takeaway, or dine-in table ordering.

5. **VIP Table & Family Hall Booking:**
   - Allows guests to reserve Outdoor Ajrak Patio charpais or indoor AC family halls with instant WhatsApp verification.

6. **Fully Responsive:**
   - Optimized for desktop screens, laptops, tablets, and smartphones.
   - Includes floating action buttons for quick 1-tap call and WhatsApp chat.
