# 🚀 JobPortal – Full-Stack Web3 x AI Job & Networking Platform

This is my submission for the **RizeOS Core Team Internship**. It’s a next-gen job and networking portal inspired by LinkedIn, Upwork, and AngelList — powered by **AI**, **Web3**, and built with a full-stack MERN architecture.

---

## 🌟 Features

### 🧑‍💼 User Profiles & Authentication
- JWT-based authentication
- User profile with bio, skills, wallet address
- AI-based skill extraction from bio or uploaded resume

### 💼 Job Posting & Social Feed
- Authenticated users can post jobs or updates
- Job filtering by skill, location, tags
- View and interact with other user posts

### 🔗 Blockchain Integration
- MetaMask wallet connection (EVM chain)
- Pay platform fee (e.g., 0.001 ETH on testnet) before posting job
- Transaction verified via **Ethers.js** and logged on backend

### 🧠 AI Enhancements
- **NLP-based job-applicant matching** (match score)
- **Resume skill extraction** using simple NER
- Smart job recommendations (based on profile data)

---

## 🛠 Tech Stack

| Layer      | Tech                            |
|------------|----------------------------------|
| Frontend   | React.js, Tailwind CSS           |
| Backend    | Node.js, Express.js              |
| Database   | MongoDB Atlas                    |
| AI/NLP     | Custom NLP logic using `compromise.js` / Python |
| Blockchain | Ethereum (testnet), MetaMask, Ethers.js |
| Hosting    | Frontend on Vercel, Backend on Render |

---

## 🎯 Go-To-Market (GTM) Strategy

### 🎯 Target Users
- Fresh graduates and job seekers in Web2/Web3
- Freelancers and startup founders

### 🗺 Roadmap to First 10,000 Users (3 Months)
- Campus ambassador program
- College workshops + resume parsing utility
- Dev community promotions via Discord/Reddit

### 📣 Marketing Plan (₹5000 budget)
- Instagram reels + meme marketing (₹2000)
- Micro-influencer YouTube collabs (₹2000)
- LinkedIn ads / developer groups outreach (₹1000)

### 💰 Revenue Model
- ₹150/month premium subscription (boost visibility)
- Job poster fee: 0.001 ETH per post
- Optional NFT-based profile verifications in future

---

## 📦 How to Run Locally

```bash
git clone https://github.com/chakrinani/jobportal.git
cd jobportal
npm install
npm run dev
