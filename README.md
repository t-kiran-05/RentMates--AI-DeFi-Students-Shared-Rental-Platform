
<div align="center">

# 🏠 RentMates

### AI & Blockchain-Powered Student Housing Platform

**Solving the international student housing crisis with smart contracts, machine learning, and decentralized finance.**

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_App-6366F1?style=for-the-badge)](https://rentmates-student-housing.vercel.app)
[![Portfolio](https://img.shields.io/badge/Type-Portfolio_Showcase-orange?style=for-the-badge)](#)

![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Polygon](https://img.shields.io/badge/Polygon-8247E5?style=flat-square&logo=polygon&logoColor=white)

📌 *This repository is a project showcase, it documents the architecture, models, and UI through screenshots and technical writeups. Source code is private.*

</div>

---

## 📋 Table of Contents

- [The Problem](#-the-problem)
- [The Solution](#-the-solution)
- [Key Features](#-key-features)
- [Live Demo](#-live-demo)
- [Product Walkthrough](#-product-walkthrough)
- [System Architecture](#-system-architecture)
- [Tech Stack](#-tech-stack)
- [Machine Learning Models](#-machine-learning-models)
- [Blockchain Layer](#-blockchain-layer)
- [Roadmap](#-roadmap)
- [Authors](#-authors--acknowledgments)

---

## 🎯 The Problem

International students relocating for university face a rental market stacked against them:

| Pain Point | Impact |
|---|---|
| 💸 **Upfront deposits before visa approval** | Students risk losing thousands with no refund guarantee if a visa is denied |
| 🏦 **No local credit history** | Locked out of traditional bank loans and financing options |
| 🎭 **Rampant rental scams** | Fake listings and unverified landlords target vulnerable newcomers |
| 📊 **No price transparency** | Students routinely overpay with no way to benchmark "fair" rent |

## 💡 The Solution

**RentMates** introduces a trust layer built on smart contracts and machine learning to neutralize each of these risks, automated escrow refunds, collateral-backed P2P lending, AI-driven fraud detection, and data-backed fair pricing, all in one platform.

---

## ✨ Key Features

<table>
<tr>
<td width="50%" valign="top">

### 🔒 Smart Escrow & Visa-Safe Deposits
Leases and deposits are executed entirely on-chain. If a visa is denied, refunds trigger automatically, no landlord can withhold funds.

### 💰 DeFi P2P Rental Lending
Peer-to-peer loans funded by investor pools, secured with **PAXG gold-token collateral** ,completely bypassing traditional bank underwriting.

### 📈 Dynamic AI Fair-Rent Pricing
A regression engine benchmarks rents against real-time **Numbeo cost-of-living data**, flagging overpriced listings before students commit.

</td>
<td width="50%" valign="top">

### 🕵️ NLP-Driven Scam Detection
A multi-layer audit engine scores every listing as **Safe / Medium / High risk** based on fraud keywords, pricing anomalies, and metadata patterns.

### 🤝 Verified KYC & Roommate Matching
Compatibility scoring connects KYC-verified students by habits, budget, and program of study for co-living and joint bids.

### 💬 Real-Time Communication
In-app messaging, live notifications, and viewing-appointment scheduling, all powered by WebSockets.

</td>
</tr>
</table>

---

## 🌐 Live Demo

**[rentmates-student-housing.vercel.app →](https://rentmates-student-housing.vercel.app)**

---

## 🖼️ Product Walkthrough

### 🏘️ Landlord Experience
Manage listings, review tenant requests, and track bids from a single dashboard.

<table>
<tr>
<td align="center" width="50%">
<img src="screenshots/landlord-dashboard.png" width="100%"/><br/>
<sub><b>Dashboard Overview</b></sub>
</td>
<td align="center" width="50%">
<img src="screenshots/landlord-add-property.png" width="100%"/><br/>
<sub><b>Add New Property</b></sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
<img src="screenshots/tenant-join-requests.png" width="100%"/><br/>
<sub><b>Tenant Join Requests</b></sub>
</td>
<td align="center" width="50%">
<img src="screenshots/landlord-bids.png" width="100%"/><br/>
<sub><b>Bids Management</b></sub>
</td>
</tr>
</table>

---

### 💼 Investor Experience
Track investment performance and allocate funds across pools by risk and return profile.

<table>
<tr>
<td align="center" width="50%">
<img src="screenshots/investor-dashboard1.png" width="100%"/><br/>
<sub><b>Investor Dashboard</b></sub>
</td>
<td align="center" width="50%">
<img src="screenshots/investment-pools.png" width="100%"/><br/>
<sub><b>Investment Pools</b></sub>
</td>
</tr>
</table>

---

### 🛡️ Admin Panel
Platform-wide oversight of registered users, roles, and activity.

<table>
<tr>
<td align="center" colspan="2">
<img src="screenshots/user-management.png" width="60%"/><br/>
<sub><b>User Management</b></sub>
</td>
</tr>
</table>

---

### 🎓 Student Experience
Search verified listings, complete KYC, schedule viewings, and find compatible roommates.

<table>
<tr>
<td align="center" width="50%">
<img src="screenshots/student-KYC-verification.png" width="100%"/><br/>
<sub><b>KYC Verification</b></sub>
</td>
<td align="center" width="50%">
<img src="screenshots/student-properties-search.png" width="100%"/><br/>
<sub><b>Property Search</b></sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
<img src="screenshots/property-details-page.png" width="100%"/><br/>
<sub><b>Property Details</b></sub>
</td>
<td align="center" width="50%">
<img src="screenshots/student-loan-application.png" width="100%"/><br/>
<sub><b>Loan Application</b></sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
<img src="screenshots/propertyListing-visit-schedule.png" width="100%"/><br/>
<sub><b>Schedule a Viewing</b></sub>
</td>
<td align="center" width="50%">
<img src="screenshots/roommates-matching.png" width="100%"/><br/>
<sub><b>Roommate Matching</b></sub>
</td>
</tr>
</table>

---

### 💬 Real-Time Communication
Direct messaging and live notifications keep students, landlords, and investors in sync.

<table>
<tr>
<td align="center" width="50%">
<img src="screenshots/messages-interface.png" width="100%"/><br/>
<sub><b>Messaging Interface</b></sub>
</td>
<td align="center" width="50%">
<img src="screenshots/notifications.png" width="100%"/><br/>
<sub><b>Notifications</b></sub>
</td>
</tr>
</table>

---

### ⛓️ Smart Contracts & Escrow
Tamper-proof, on-chain lease agreements with automated deposit conditions.

<table>
<tr>
<td align="center" width="50%">
<img src="screenshots/smartcontract1.png" width="100%"/><br/>
<sub><b>Lease Agreement</b></sub>
</td>
<td align="center" width="50%">
<img src="screenshots/smartcontract2.png" width="100%"/><br/>
<sub><b>Contract Execution</b></sub>
</td>
</tr>
</table>

---

### 👛 Wallet Management
Connect and manage MetaMask funds directly within the platform.

<table>
<tr>
<td align="center" colspan="2">
<img src="screenshots/wallet-management.png" width="60%"/><br/>
<sub><b>MetaMask Wallet Integration</b></sub>
</td>
</tr>
</table>

---

### 🤖 AI-Powered Pricing & Safety
AI-benchmarked pricing and fraud-risk scoring, side by side for every listing.

<table>
<tr>
<td align="center" width="50%">
<img src="screenshots/dynamic-rent-prediction.png" width="100%"/><br/>
<sub><b>Fair-Rent Prediction</b></sub>
</td>
<td align="center" width="50%">
<img src="screenshots/property-listing-scam-analysis.png" width="100%"/><br/>
<sub><b>Scam Risk Analysis</b></sub>
</td>
</tr>
</table>

---

### 💰 Loan Center
Students apply for collateral-backed rental loans against PAXG holdings.

<table>
<tr>
<td align="center" colspan="2">
<img src="screenshots/student-loan-center.png" width="60%"/><br/>
<sub><b>Loan Center</b></sub>
</td>
</tr>
</table>

---

## 🏗️ System Architecture

```
                       ┌────────────────────────────────┐
                       │      Client Layer (React)       │
                       │  Student · Landlord · Investor  │
                       └────────────────┬─────────────────┘
                                        │ HTTPS / WebSockets
                       ┌────────────────▼─────────────────┐
                       │     API Gateway — Node.js/Express │
                       │   JWT Auth · Role-Based Access    │
                       └──────┬─────────────────┬──────────┘
                              │                  │
            ┌─────────────────┴───┐     ┌────────┴──────────────┐
            │                     │     │                        │
 ┌──────────▼──────────┐ ┌────────▼─────▼───────┐ ┌──────────────▼─────────────┐
 │   MongoDB Database   │ │   AI / ML Services    │ │  Smart Contracts (Solidity) │
 │ Profiles · Listings · │ │ Rent Pricing Model   │ │ Escrow · PAXG Collateral ·   │
 │ Applications · Chats  │ │ Scam Detection (NLP) │ │ USDT Vault · Verification    │
 └───────────────────────┘ └───────────────────────┘ └───────────────────────────┘
```

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|---|---|
| **React 18 + TypeScript** | Component-driven, type-safe UI, built with Vite |
| **Tailwind CSS + Lucide Icons** | Responsive design system across all devices |
| **Ethers.js v6.15.0** | Web3 provider integration — MetaMask, tx signing, contract events |

### Backend & Microservices
| Technology | Purpose |
|---|---|
| **Node.js + Express.js** | RESTful API, scheduling, and core business workflows |
| **Socket.IO v4** | Real-time messaging, live bid updates, instant notifications |
| **JWT + Bcrypt.js** | Stateless auth with RBAC (Student / Landlord / Investor / Admin) |
| **Multer + Cloudinary** | KYC document handling and listing media pipeline |

### Machine Learning & NLP
| Technology | Purpose |
|---|---|
| **Python 3.12** | Model training, preprocessing, and analytics pipelines |
| **Random Forest Classifier** | Scam detection — 7 features, 3,000+ samples, **93.02% accuracy** |
| **XGBoost Regressor** | Rent pricing — bedrooms, bathrooms, furnishing, distance-to-city |
| **Google Gemini 2.5 Flash** | Dual-perspective negotiation insights for tenants and landlords |

### Blockchain & Web3
| Technology | Purpose |
|---|---|
| **Solidity** | On-chain contracts deployed on **Polygon** — leases, escrow, collateral |
| **PAXG Vault** | Gold-backed ERC-20 collateral securing student loans |
| **USDT Vault** | Stable payment rail insulating rent flows from crypto volatility |
| **Hardhat** | Contract compilation, testing, and deployment |

---

## 🤖 Machine Learning Models

### Scam Detection — Random Forest Classifier
- **93.02% accuracy** across 3,000+ real-world fraud-pattern samples
- Flags suspicious keywords, deposit anomalies, and fabricated listings
- Outputs a **Safe / Medium / High** risk classification per listing

### Fair-Rent Pricing — XGBoost Regressor
- Multi-variable regression across bedrooms, bathrooms, furnishing, and city distance
- Calibrated against **Numbeo** global cost-of-living baselines
- Surfaces a fair-rent range plus overpricing alerts for both tenants and landlords

---

## ⛓️ Blockchain Layer

- **Smart Escrow:** deposits lock on-chain and release automatically based on lease conditions or visa outcome
- **PAXG Collateral Vault:** gold-token collateral secures P2P loans under strict LTV thresholds
- **USDT Settlement:** all rent payments and pool contributions settle in stablecoin
- Deployed and tested on **Polygon** via **Hardhat**

---

## 🗺️ Roadmap

- [ ] Automated model retraining pipeline (Apache Airflow)
- [ ] Multi-currency support beyond USDT
- [ ] Mobile app (iOS/Android)
- [ ] Expanded university partnership integrations
- [ ] Historical rent trend dashboards by city/neighborhood

---

## 👥 Authors & Acknowledgments

| Name | Role |
|---|---|
| **Tayyiba Kiran** | CIIT/FA22-BCS-108/ISB |
| **Muhammad Ibrahim** | CIIT/FA22-BCS-062/ISB |
| **Sir Tanveer Ahmed** | Project Supervisor |

*Department of Computer Science, COMSATS University Islamabad, Pakistan (2022–2026)*

---

<div align="center">



</div>