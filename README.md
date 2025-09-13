# farmer-blockchain-marketplace
Hackathon project – Blockchain-powered farmer marketplace with logistics integration.
# 🌾 Farmer Blockchain Marketplace

**Hackathon Project – Blockchain-powered farmer marketplace with logistics integration.**  
Built for Gurugram University Internal Hackathon.

---

## 🚀 Problem Statement
Farmers often face unfair pricing, delayed payments, and lack of trust in delivery chains.  
Buyers struggle with transparency, while logistics confirmations are rarely verifiable.  

---

## 💡 Solution
A digital marketplace that connects **Farmers, Buyers, and Logistics** with:  
- Direct farmer-to-buyer orders (no middlemen).  
- Escrow simulation (payment locked → released after delivery).  
- Pickup & delivery confirmations via **QR/OTP**.  
- Blockchain anchoring for tamper-proof proof of transactions.  

---

## ⚙️ Tech Stack
- **Frontend:** React.js + Tailwind CSS  
- **Backend:** Node.js + Express + SQL  
- **Database:** MySQL / Firebase Firestore / MongoDB (to decide)  
- **Blockchain:** Solidity (Remix), Ethers.js, Sepolia/Polygon Testnet  
- **Collaboration:** GitHub, Postman, Canva/Google Slides  

---

## 📂 Folder Structure
/frontend → React UI (Farmer, Buyer, Logistics dashboards)
/backend → Node.js APIs + DB models
/blockchain → Solidity contracts + ethers.js integration
/docs → API contract, DB schema, system diagrams, pitch deck


---

## 🔑 API Contract (Draft)
- `POST /register` – Register user {name, role}  
- `POST /products` – Farmer adds product  
- `POST /orders` – Buyer requests product  
- `POST /orders/:id/accept` – Farmer accepts order (escrow = LOCKED)  
- `POST /orders/:id/pickup-confirm` – Logistics confirms pickup  
- `POST /orders/:id/delivery-confirm` – Logistics confirms delivery  
- `POST /orders/:id/buyer-confirm` – Buyer confirms delivery (escrow = RELEASED)  
- `POST /orders/:id/anchor` – Anchor order hash on blockchain  
- `GET /orders/:id` – Fetch order timeline  

---

## 👥 Team Roles
- **Frontend:** Keerti & Aryan  
- **Backend:** Anshul 
- **Blockchain:** Mohit  
- **Integrator (Lead):** Ayush  
- **Presentation & QA:** Aman  

---

## 🏆 Goal
- Build MVP in 5 days.  
- Deliver a smooth end-to-end demo with working blockchain verification.  
- Showcase at Gurugram University Hackathon → qualify for SIH 2025.  

