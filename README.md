# PeerCode

**PeerCode** is a full-stack developer & coder community platform. It aims to provide an interactive space for students to collaborate, ask questions, share knowledge, and track their competitive programming progress across platforms like **LeetCode**, **Codeforces**, and **GitHub** — all in one place.


## 🎯 Key Features

### 👥 Community-Driven Q&A
- **Landing Page**: Displays questions with their top answers.
- **Filters**: Newest, Recommended, Frequent, Unanswered.
- **Search Bar**: Quickly find relevant questions and answers.
- **Answering**: Engage by submitting your own answers.

### ❓ Ask a Question
- Submit detailed questions with a title and tags (e.g., `DSA`, `HTML`, `React`).
- Tag-based categorization for better discoverability.

### 💾 Saved Questions
- Bookmark questions for later reference.
- Apply filters to organize saved content.

### 🏷️ Tag Explorer
- Discover tags and see questions associated with each tag.

### 🧑‍🤝‍🧑 Community Section
- View profiles of all platform members.
- Each profile showcases:
  - Contribution Badges
  - Top Questions & Answers

### 🙋 Profile Management
- Update personal info.
- Link your **LeetCode**, **Codeforces**, and **GitHub** profiles.

### 🏆 Leaderboard System
- Displays a ranked list of members based on performance.
- Unified rating system integrating:
  - Problem-solving (LeetCode & Codeforces)
  - Contest participation
  - GitHub activity

### 🔐 Authentication
- Auth powered by **Clerk**.
- Google OAuth login supported.

---

## 📈 Leaderboard Rating Criteria

### 🔸 LeetCode
- Easy → `0.5 pt`
- Medium → `1 pt`
- Hard → `2 pt`
- Contest → `Rating - 1500`

### 🔸 Codeforces
- ≤ 1200 → `0.5 pt`
- ≤ 1600 → `1 pt`
- ≤ 1900 → `2 pt`
- > 1900 → `3 pt`
- Contest → `(New Rating - 800) / 2`

### 🔸 GitHub
- Every 5 commits → `1 pt`
- Every 2 PRs → `1 pt`

> Clicking a user's profile on the leaderboard reveals detailed statistics for each platform.

---

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, React
- **Styling**: Tailwind CSS
- **Backend**: Next.js API Routes
- **Database**: MongoDB
- **Authentication**: Clerk (Email/Password & Google login)
- **Type Safety**: TypeScript

---

## 📂 Folder Structure

```
peercode/
├── app/                # Pages and route handlers
├── components/         # Reusable UI components
├── constants/          # Static data and config
├── context/            # React context for global state
├── database/           # MongoDB connection & schemas
├── lib/                # Utility functions
├── public/             # Static files
├── styles/             # Tailwind and global styles
├── types/              # TypeScript types
├── .env.local          # Environment variables (not committed)
├── next.config.js      # Next.js config
├── tailwind.config.ts  # Tailwind CSS config
└── tsconfig.json       # TypeScript config
```
