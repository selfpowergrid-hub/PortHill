# Port Hill Guest House - Deployment Guide

This folder contains the complete, source code for the Port Hill Guest House website.

## 🚀 How to Get It Live

### 1. Requirements
- Node.js installed.
- A Supabase project (already configured in the code).

### 2. Local Setup (Verify first)
```bash
npm install
npm run dev
```
Visit `http://localhost:3000`.

### 3. Deploy to Production
The easiest way to go live is using **Vercel**:
1. Upload this folder to a GitHub repository.
2. Connect the repository to [Vercel](https://vercel.com).
3. Add the following **Environment Variables** in the Vercel dashboard:
   - `NEXT_PUBLIC_SUPABASE_URL`: (Already in code, but good to set)
   - `NEXT_PUBLIC_SUPABASE_ANON_KEY`: (Already in code, but good to set)

## 🔐 Administrative Access
- **Management Portal**: Open the booking form, click the three dots (`⋮`) in the top right.
- **Management Key**: `porthill2024`

## 🛠 Features Included
- **Luxury Booking UI**: Premium teals, glassmorphism, and smooth animations.
- **Smart Calendar**: Prevents double-bookings, shows real-time availability.
- **Integrated Admin**: Cancel or permanently delete bookings directly within the form.
- **AI Assistant**: Knowledge-based chat with a fallback to your WhatsApp.

---
*Created with care by Antigravity.*
