# 🌐 Networks & Data Communication — Ultimate Exam Guide

> **Helwan International Technology University — Cybersecurity Department**
> **Course: Networks & Data Communication | Dr. Simon Ezzat**
> **Prepared by: Zeyad Eltmsah**

---

## 📖 About

A **fully interactive, bilingual (Arabic/English)** exam preparation guide built as a single-page web application.  
No frameworks, no dependencies — just pure HTML, CSS, and JavaScript.

Open `Ultimate_Exam_Preparation_Guide.html` in any modern browser and start studying!

---

## ✨ Features

### 📋 Section 1 — True & False (35 Questions)
- All 35 questions sourced 100% from the official Question Bank
- Click any card to reveal the answer and full explanation
- Both Arabic and English explanations

### 📝 Section 2 — Essay / Short Answer (70 Questions)
- Full model answers for all 70 essay questions
- Bilingual explanations

### 🌍 Section 3 — IP Protocols (IPv4 & IPv6)

#### IPv4 Sub-Tab
- **Interactive Header Length Checker** — enter any 8-bit binary, get VER + HLEN analysis
- **Data Size Calculator** — compute data payload from HLEN and Total Length
- **IPv4 Header Diagram** — full visual 32-bit field layout
- **Solved Lecture Examples** (Pages 7 & 11)

#### IPv6 Sub-Tab
- **IPv6 Compressor** — compress any full 128-bit address step-by-step
- **IPv6 Expander** — expand any compressed address with detailed steps
- **IPv6 Header Diagram** — fixed 40-byte structure
- **Compression Rules** explained with examples
- **Solved Lecture Examples** (Pages 24–26)

#### Wildcard Mask Sub-Tab
- **Theory & Formula** — `Wildcard = 255.255.255.255 − Subnet Mask`
- **3 Solved Examples** (Class A, B, C)
- **Interactive Wildcard Calculator** — enter any mask or CIDR prefix, get full binary + decimal breakdown

### 🧮 Section 4 — Subnetting Solver & Exercises
- **Live Subnetting Calculator** — enter IP + original mask + new mask → get all 8 metrics
- **3 Fully Solved Question Bank Problems** with screenshots from the official exam bank
  - Exercise 1: Class C Subnetting (`/24 → /27`)
  - Exercise 2: Class A Subnetting (`/8 → /17`)
  - Exercise 3: Class B Subnetting (`/16 → /19`)

---

## 🚀 How to Use

1. **Clone or download** this repository
2. Open `Ultimate_Exam_Preparation_Guide.html` in your browser (Chrome, Firefox, Edge)
3. No internet required for core functionality (fonts load from Google Fonts if online)

```bash
git clone https://github.com/YOUR_USERNAME/networks-exam-guide.git
cd networks-exam-guide
# Open the HTML file in your browser
start Ultimate_Exam_Preparation_Guide.html    # Windows
open Ultimate_Exam_Preparation_Guide.html     # macOS
xdg-open Ultimate_Exam_Preparation_Guide.html # Linux
```

---

## 📁 File Structure

```
WEB/
├── Ultimate_Exam_Preparation_Guide.html    # Main application (single file)
├── Screenshot 2026-06-06 011537.png        # Exercise 3 — Class B question
├── Screenshot 2026-06-06 011752.png        # Exercise 1 — Class C question
├── Screenshot 2026-06-06 011759.png        # Exercise 2 — Class A question
└── README.md                               # This file
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| **HTML5** | Structure & semantic markup |
| **Vanilla CSS** | Dark theme, animations, glassmorphism |
| **JavaScript (ES6+)** | All interactive calculators & tab logic |
| **Google Fonts** | Inter + Montserrat typography |

---

## 🎨 Design

- **Dark mode** cyberpunk-inspired UI with cyan & purple accent colors
- **Fully responsive** layout for desktop and mobile
- **Bilingual** — Arabic (RTL) and English side-by-side
- **Smooth animations** and micro-interactions throughout

---

## 📚 Topics Covered

- General Networking Basics
- IP Addressing (IPv4 & IPv6) and DHCP
- Networking Devices (Switch, Router, Hub, Firewall)
- OSI Model (7 Layers)
- VLAN Concepts
- Wi-Fi & Cabling
- IPv4 Datagram Header (VER, HLEN, TTL, Flags, Fragmentation)
- IPv6 Header (Fixed 40-byte, Compression Rules)
- Subnetting (CIDR, Block Size, Network/Host/Broadcast)
- Wildcard Masks (ACL & OSPF usage)

---

## 👤 Author

**Zeyad Eltmsah** — Cybersecurity Department, 1st Year  
Helwan International Technology University

---

*Good luck on your exam! 🎓*
