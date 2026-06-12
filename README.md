# Anil Paan | Live Wholesale Rates in Balangir

A modern PWA (Progressive Web App) for betel leaf wholesale market rates in Balangir, Odisha.

## 🌿 Features

- **Live Market Rates** — Real-time betel leaf pricing for retailers
- **Admin Dashboard** — Password-protected panel to update rates and products
- **PWA Ready** — Install as a Chrome app on desktop and mobile
- **Responsive Design** — Works seamlessly on all devices
- **UPI Payments** — Digital payment support
- **Firebase Backend** — Real-time Firestore database with authentication

## 📁 Project Structure

```
public/
├── index.html              # Customer homepage
├── admin.html              # Admin dashboard
├── manifest-customer.json  # PWA manifest for customer app
├── manifest-admin.json     # PWA manifest for admin app
├── styles.css              # Tailwind CSS styling
├── sw.js                   # Service Worker for offline support
├── robots.txt              # SEO robots configuration
└── sitemap.xml             # XML sitemap for search engines

firebase.json              # Firebase Hosting configuration
tailwind.config.js         # Tailwind CSS configuration
```

## 🚀 Getting Started

### Prerequisites
- Node.js 16+
- Firebase CLI (`npm install -g firebase-tools`)

### Installation

1. Clone the repository
```bash
git clone <your-github-repo-url>
cd anil-website
```

2. Install dependencies (if any)
```bash
npm install
```

3. Set up Firebase
```bash
firebase init
firebase deploy
```

### Running Locally

```bash
firebase serve
# Open http://localhost:5000
```

## 📱 PWA Installation

### Customer App
1. Visit https://anil-paan-wwebsite.web.app/
2. Click the **Install** button in the address bar
3. App installs as "Anil Paan" with betel leaf icon

Features:
- View all products with live rates
- Update betel leaf pricing
- Add new paan varieties
- Real-time Firestore sync

## 📊 SEO Optimization

- ✅ Proper `<title>` and meta description
- ✅ Keywords: "Anil Pan", "Anil Paan", "Betel Leaf Wholesale"
- ✅ XML sitemap at `/sitemap.xml`
- ✅ robots.txt configuration
- ✅ Google Search Console verified
- ✅ Schema markup ready

## 🌐 Deployment

Hosted on **Firebase Hosting**:
- Live URL: https://anil-paan-wwebsite.web.app/
- Auto-deployed on git push (if CI/CD configured)

### Manual Deploy
```bash
firebase deploy --only hosting
```

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Tailwind), JavaScript (Vanilla)
- **Backend:** Firebase Firestore
- **Auth:** Firebase Anonymous + Password
- **Hosting:** Firebase Hosting
- **PWA:** Service Worker (offline support)

## 📱 Contact

- **Phone:** +91 98612 81756
- **WhatsApp:** [Message us](https://wa.me/919861281756)
- **Location:** Balangir, Odisha, India

## 📝 License

All rights reserved © 2026 Anil Betel Leaf Wholesale
