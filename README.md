# Prix-coding-academy# SkillCraft - Freemium E-Learning Platform

![SkillCraft Demo](demo.gif) 


A full-stack platform for learning web development (HTML/CSS/JavaScript/Python) with free and premium tiers.

## 🌟 Features

- **Free Tier**:
  - 30+ interactive coding lessons
  - Community discussion forums
  - Basic code challenges

- **Premium Tier** ($15/month):
  - Certificates of completion
  - Real-world projects with automated testing
  - Priority support

- **Tech Stack**:
  - Frontend: React.js + Monaco Editor
  - Backend: Node.js/Express + MongoDB
  - Payments: Stripe integration
  - Security: JWT auth + Docker sandboxing

## 🚀 Quick Start

### Prerequisites
- Node.js v16+
- MongoDB Atlas account
- Stripe API keys

### Installation
```bash
# Clone repo
git clone https://github.com/your-repo/skillcraft.git
cd skillcraft

# Backend setup
cd backend
npm install
cp .env.example .env  # Fill in your credentials

# Frontend setup
cd ../frontend
npm install
