# Aventra Tours 🌍

A travel and tourism website focused on exploring the beautiful destinations of Pakistan.

---

## 🗺️ Featured Destinations

- **Faisal Mosque** — Islamabad
- **Daman-e-Koh** — Islamabad
- **Khanpur Dam** — KPK
- **Swat Valley** — KPK
- **Chitral** — KPK
- **Badshahi Mosque** — Lahore
- **Minar-e-Pakistan** — Lahore
- **Fairy Meadows** — Gilgit-Baltistan
- **Naran Kaghan** — KPK
- **Murree** — Punjab
- **Mohenjo Daro** — Sindh
- **Lake View Park** — Islamabad

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (Bootstrap 5)
- JavaScript
- Font Awesome Icons

---

## 📁 Project Structure

```
public/
├── index.html
├── assets/
│   ├── css/
│   ├── js/
│   ├── img/
│   └── video/
└── vendors/
```

---

## 🔍 SEO Implementation

Yahan sari SEO techniques listed hain jo is site par apply ki gayi hain.

---

### 1. 🏷️ Core Meta Tags

| Tag | Value |
|-----|-------|
| `<title>` | Aventra Tours \| Pakistan Travel Agency – Tour Packages, Northern Areas & Holiday Deals |
| `meta description` | 160 characters, main keywords included |
| `meta keywords` | 12 targeted keywords |
| `meta author` | Aventra Tours |
| `meta robots` | `index, follow, max-snippet:-1, max-image-preview:large, max-video-preview:-1` |
| `canonical` | `https://www.aventratours.com/` |
| `lang` attribute | `en-PK` (Pakistan-specific) |

---

### 2. 🌐 Open Graph (Facebook / WhatsApp)

Social sharing ke liye complete OG tags:

```html
<meta property="og:type" content="website">
<meta property="og:url" content="https://www.aventratours.com/">
<meta property="og:title" content="Aventra Tours | Pakistan Travel Agency – Best Tour Packages 2026">
<meta property="og:description" content="...">
<meta property="og:image" content="https://www.aventratours.com/assets/img/gallery/share.png">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta property="og:image:alt" content="Aventra Tours - Pakistan Travel Agency">
<meta property="og:locale" content="en_PK">
<meta property="og:site_name" content="Aventra Tours">
```

---

### 3. 🐦 Twitter Card

```html
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="...">
<meta name="twitter:description" content="...">
<meta name="twitter:image" content="https://www.aventratours.com/assets/img/gallery/share.png">
<meta name="twitter:site" content="@aventratours">
<meta name="twitter:creator" content="@aventratours">
```

---

### 4. 📍 Local SEO / Geo Tags

```html
<meta name="geo.region" content="PK-PB">
<meta name="geo.placename" content="Rawalpindi, Pakistan">
<meta name="geo.position" content="33.5651;73.0169">
<meta name="ICBM" content="33.5651, 73.0169">
```

---

### 5. 📊 JSON-LD Structured Data (Schema.org)

3 alag schemas implement kiye gaye hain:

#### ✅ TravelAgency Schema
```json
{
  "@type": "TravelAgency",
  "name": "Aventra Tours",
  "address": { "streetAddress": "Office No. 8, First Floor, Mian Plaza, Chandni Chowk", "addressLocality": "Rawalpindi" },
  "telephone": "+92-310-5199783",
  "email": "aventrapakistan@gmail.com",
  "areaServed": "Pakistan",
  "priceRange": "PKR 10,000 – PKR 50,000",
  "hasOfferCatalog": { ... }
}
```

#### ✅ FAQPage Schema
6 long-tail questions ke sath — Google "People Also Ask" me show hone ke liye:
- Best places to visit in Pakistan in summer
- 3-day trip to Swat Valley cost
- How to travel to Fairy Meadows Pakistan
- Budget trip to northern areas Pakistan cost
- Family & honeymoon packages
- Top tourist places in Swat Valley

#### ✅ BreadcrumbList Schema
```json
{
  "@type": "BreadcrumbList",
  "itemListElement": [
    { "position": 1, "name": "Home" },
    { "position": 2, "name": "Tour Packages Pakistan" },
    { "position": 3, "name": "Destinations" }
  ]
}
```

---

### 6. 🔑 Target Keywords

#### Core Keywords (Homepage)
- Pakistan travel agency
- Tour packages Pakistan
- Travel to Pakistan / Pakistan tourism
- Explore Pakistan
- Northern areas Pakistan tours
- Pakistan holiday packages

#### Destination Keywords (High Traffic)
- Faisal Mosque travel guide
- Daman-e-Koh viewpoint Islamabad
- Khanpur Dam water sports
- Swat Valley tourism
- Chitral travel guide
- Badshahi Mosque history
- Fairy Meadows camping

#### Commercial / Money Keywords
- Swat tour package price
- Hunza tour package 2026
- Pakistan honeymoon packages
- Family tour packages Pakistan
- Cheap travel deals Pakistan
- 3 days trip to Swat cost

#### Local SEO Keywords
- Islamabad travel agency
- Lahore tour packages
- Karachi to Swat tour
- Pakistan northern tours from Islamabad
- Rawalpindi travel agency

#### Long-Tail Keywords (Easy Ranking)
- best places to visit in Pakistan in summer
- top tourist places in Swat Valley
- how to travel to Fairy Meadows Pakistan
- budget trip to northern areas Pakistan
- things to do in Hunza Valley

---

### 7. 🖼️ Image SEO

- Sari images par descriptive `alt` text
- Navbar logo alt: `"Aventra Tours - Pakistan Travel Agency"`
- Destination images alt: location name + city (e.g. `"Faisal Mosque Islamabad"`)
- OG image absolute URL with width/height specified

---

### 8. 📝 On-Page SEO

| Element | Detail |
|---------|--------|
| `<h1>` | "Pakistan Travel Agency" + "Explore Pakistan – Your Journey Starts Here" |
| `<h2>` | "Popular Pakistan Places", "Explore Pakistan", "Best Hotels for Pakistan Tourists", "Top Pakistan Tour Packages" |
| `<h3>` | Destination names (Chitral, Fairy Meadows, Naran Kaghan, etc.) |
| Footer links | Keyword-rich anchor text (Swat Valley Tourism, Fairy Meadows Camping, etc.) |
| FAQ Section | Visible accordion with 6 long-tail Q&A on page |

---

### 9. ✅ SEO Checklist

- [x] Title tag optimized (60 chars)
- [x] Meta description (160 chars)
- [x] Canonical URL set
- [x] `lang="en-PK"` attribute
- [x] Open Graph tags complete
- [x] Twitter Card tags complete
- [x] JSON-LD TravelAgency schema
- [x] JSON-LD FAQPage schema (hidden in `<head>`, Google ke liye)
- [x] JSON-LD BreadcrumbList schema
- [x] Geo / Local SEO tags
- [x] Real contact info in schema & footer
- [x] Descriptive alt text on all images
- [x] H1, H2, H3 heading hierarchy
- [x] Keyword-rich footer links
- [x] Visible FAQ section on page
- [x] robots meta with max-snippet
- [ ] Google Search Console me submit karo
- [ ] XML Sitemap banao aur submit karo
- [ ] Google Business Profile banao (Rawalpindi listing)
- [ ] Backlinks build karo (travel blogs, directories)

---

### 📌 Next Steps (Remaining SEO Tasks)

1. **Google Search Console** — site verify karo aur sitemap submit karo
2. **XML Sitemap** — `sitemap.xml` banao aur `robots.txt` me add karo
3. **Google Business Profile** — Rawalpindi location ke liye listing banao
4. **Blog Pages** — har destination ke liye alag page banao (Swat, Fairy Meadows, Chitral, etc.)
5. **Page Speed** — images compress karo (WebP format use karo)
6. **Backlinks** — Pakistan travel blogs aur directories me site submit karo

---

## 👨‍💻 Developer

**Ihsan Anwar**  
GitHub: [@IHSAN-ANWAR](https://github.com/IHSAN-ANWAR)
