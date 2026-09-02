# ShilpSetu

> AI-powered prototype for artisans: snap a photo, speak about your craft. AI enhances images, writes descriptions, crafts stories, suggests prices, and finds buyers. Bilingual (English/Hindi), end-to-end journey from workshop to marketplace. No tech skills needed.

---

## Overview

ShilpSetu is a mobile-first prototype built for the **Smart India Hackathon 2026** (PS 26090). It bridges the gap between traditional artisans and the digital marketplace by using AI to automate the entire product listing process—from photo enhancement to buyer matching.

The prototype follows **Meera Devi**, a bamboo weaver from Jaipur, as she lists her handwoven storage basket in a single continuous session.

---

## Features

- **AI‑Powered Photo Enhancement** – Remove background distractions, improve lighting, and center products automatically.
- **Voice‑Driven Product Entry** – Speak about your product; AI extracts details, writes descriptions, and generates a craft story.
- **Intelligent Pricing** – Input material costs and other expenses; AI suggests a competitive market price with range estimates.
- **Live Product Dashboard** – View your published products, track enquiries, orders, and income.
- **Buyer Matching** – AI finds relevant buyers based on product type, material, price, and buyer requirements.
- **Business Copilot** – Ask simple questions like "How is my business doing?" and get plain‑language insights.
- **Bilingual Interface** – Full English and Hindi support, with all user‑facing text (including dynamic content) translated.
- **End‑to‑End Journey** – From capturing a photo to going live and finding buyers, all in one flow.

---

## Tech Stack

- **React** (CDN) – UI components
- **Babel Standalone** – JSX compilation in the browser
- **CSS** – Custom styling with a warm, craft‑inspired design system
- **Images** – `before.png` (raw photo) and `after.png` (AI‑enhanced photo) used in the prototype

No build tools, bundlers, or server dependencies—just open the HTML file in a browser.

---

## Live Demo

The prototype is hosted on GitHub Pages:  
**[https://sahilahmadofficial.github.io/shilpsetu-prototype/](https://sahilahmadofficial.github.io/shilpsetu-prototype/)**  

---

## Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/sahilahmadofficial/shilpsetu-prototype.git
   ```
2. Navigate to the folder:
   ```bash
   cd shilpsetu-prototype
   ```
3. Open `index.html` in your browser.

No server or installation required.

---

## File Structure

```
shilpsetu-prototype/
├── index.html          # Main application (React + Babel)
├── before.png          # Raw product photo (camera capture)
├── after.png           # AI‑enhanced product photo
└── README.md           # This file
```

---

## How It Works (User Journey)

1. **Onboarding** – Choose language, role (Artisan), and set up profile.
2. **Add Product** – Take a photo or upload from gallery.
3. **AI Enhancement** – Photo is automatically improved (slider to compare before/after).
4. **Voice Description** – Speak about your product; AI transcribes and structures details.
5. **Craft Story** – Speak about your craft; AI generates a personal story.
6. **Pricing** – Enter costs; AI suggests a price and range.
7. **Review & Publish** – Review all AI‑generated content, edit if needed, and publish.
8. **Live Listing** – Product appears on the dashboard and in the "Products" tab.
9. **Buyer Matching** – AI suggests relevant buyers; send messages with AI‑generated replies.
10. **Business Copilot** – Ask questions about your business performance.

---

## Future Enhancements

- Real camera and voice recording APIs
- Backend with user authentication and persistent storage
- Integration with actual e‑commerce platforms
- More languages and regional crafts
- Analytics and sales forecasting

---

## Team

This project was developed for **Smart India Hackathon 2026** by Team ShilpSetu.

---

## License

MIT – feel free to use and adapt for your own projects.
