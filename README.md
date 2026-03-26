# Blue Carbon Restoration Registry 🌿

A decentralized platform for monitoring, verifying, and incentivizing ecological restoration activities in coastal ecosystems.

## 🚀 Overview
Blue Carbon (RestoreX) is a registry application that allows contributors to submit evidence of restoration activities (Mangroves, Seagrass, Wetlands). These submissions are reviewed by government officials and, once verified, result in the issuance of **Carbon Credits (CBC)** to the contributor.

## ✨ Key Features
- **Project Submission:** Upload photos with GPS metadata and descriptions of restoration work.
- **Verification Pipeline:** Advanced admin panel for officials to review evidence and approve/reject submissions.
- **Wallet & Payouts:** Regular users can track their Earned CBC and convert them to INR via Razorpay integration (Mock/Live).
- **Registry Transparency:** Verified projects are recorded with high integrity and ready for on-chain verification.

## 👥 User Roles
- **Restorers (Users):** Submit restoration activities, track impact, and manage their earnings wallet.
- **Officials (Managers):** Review field submissions, manage verified registries, and host ecological events.
- **Government:** Approve payout requests and monitor global restoration stats.

## 🛠️ Tech Stack
- **Frontend:** React, Vite, Tailwind CSS, Lucide Icons, Motion (Framer Motion).
- **Backend:** Firebase (Firestore, Auth, Storage).
- **Payment:** Razorpay Payouts Integration.
- **Metadata:** EXIF extraction for GPS verification.

## 🔧 Installation & Setup
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Set up a Firebase project and add your config to `src/lib/firebase.ts`.
4. Run `npm run dev` to start the development server.

## 📄 License
MIT License.
