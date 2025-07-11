# 🖨️ Printeth

**Printeth** is a work in progress of a full-stack digital gallery and e-commerce system for handmade and AI-generated artwork. Built with the MERN stack (MongoDB Atlas, Express, React, Node.js), it features a modern admin interface, dynamic gallery display, analytics powered by Python, and optional integration with Print-on-Demand (POD) services for physical fulfillment.

> *“The truest poetry is the most feigning.” — William Shakespeare*  
> Printeth celebrates both the hand-crafted and the computational — illusions that speak truth.

---

## 🎯 Project Purpose

Printeth is a creative-tech experiment and portfolio project that:

- Showcases and sells your artwork (AI + handmade)
- Tracks what viewers click, skip, and buy
- Uses data science to uncover visual trends and style performance
- Optionally integrates with POD platforms to fulfill physical orders

---

## 🧱 Tech Stack

| Layer        | Tech              | Description                                |
|--------------|-------------------|--------------------------------------------|
| **Database** | MongoDB Atlas     | Cloud-hosted database for artworks & views |
| **Backend**  | Node.js + Express | REST API for gallery, uploads, purchases   |
| **Frontend** | React             | Public gallery + admin upload interface    |
| **Analytics**| Python (pandas)   | Visual trend analysis + performance stats  |
| **POD (opt)**| Printful, Gelato  | Optional: fulfill orders via webhook/API   |

---

## 🧩 Features

### 🖼️ Artwork Gallery
- Browse by type (Handmade, AI)
- Filter by tag or popularity
- Lightbox preview
- Simulated or real purchases

### 🔐 Admin Dashboard
- Upload artwork (image + metadata)
- Tag and type management
- View/edit existing pieces
- React-based, secure, local-first

### 📊 Analytics & Insights
- Views and "buy" click tracking
- Handmade vs AI performance stats
- Tag, resolution, and time-of-day trend analysis
- Data pulled into Python for deeper visual exploration

### 🖨️ POD Integration (Optional)
- Export metadata + images to Printful or Gelato
- Webhook or CSV-based order triggers
- Ready for automated physical 
