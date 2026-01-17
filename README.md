# Udhayam TV Repair & Electronics Service Website

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://yourusername.github.io/udhayam-tv-repair-website/)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue)](https://pages.github.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A modern, animated, and fully responsive website for **Udhayam TV Repair & Electronics Service**, a trusted business since 1990 in Chennai.

## 🌟 Features

- **Modern & Animated Design**
  - Smooth animations and transitions
  - Floating elements and hover effects
  - Gradient color scheme with gold accents

- **35+ Years Experience Showcase**
  - "Since 1990" branding throughout
  - Animated statistics counters
  - Generational expertise highlighting

- **Complete Business Information**
  - Professional services showcase
  - 30+ common TV issues listed
  - Contact form with Formspree integration
  - Working hours and location

- **Mobile Responsive**
  - Fully responsive design
  - Mobile-friendly navigation
  - Optimized for all devices

- **Formspree Email Integration**
  - Service request form sends emails
  - Loading states and success/error messages
  - Spam protection

## 🚀 Live Demo

Visit the live website: [https://yourusername.github.io/udhayam-tv-repair-website/](https://yourusername.github.io/udhayam-tv-repair-website/)

## 🛠️ Setup Instructions

### 1. Formspree Email Setup
The contact form uses Formspree for email notifications. Follow these steps:

1. Go to [formspree.io](https://formspree.io) and sign up
2. Create a new form (e.g., "Udhayam TV Repair Service Requests")
3. Copy your Formspree form ID
4. In `index.html`, find line 1306 and replace `YOUR_FORM_ID` with your actual form ID:
   ```html
   <form id="serviceForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
