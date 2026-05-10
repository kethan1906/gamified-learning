# 🎓 BTR Bites — Gamified Learning Platform

> **🏆 Hackathon Winner** — A concept-stage gamified learning platform built for students preparing for competitive exams like NEET, JEE, and more.

---

## 📖 About the Project

**BTR Bites** (also known as **Quiz Quest**) is an interactive, gamified educational web app designed to make exam preparation fun and engaging. Students can explore subjects, tackle chapter-wise quizzes, earn XP, level up, and compete on a global leaderboard — all while playing mini-games between study sessions.

> ⚠️ **Note:** This project was built as a proof-of-concept during a hackathon. Core features are scaffolded and functional on the frontend; backend integration and full data persistence are not yet implemented.

---

## ✨ Features

### 📚 Subjects & Quizzes
- Chapter-by-chapter structured learning for **Physics, Chemistry, Biology, Mathematics, and NEET**
- Multiple-choice quizzes with instant feedback and answer explanations
- Difficulty levels: Easy → Medium → Hard
- Subject-specific diagrams and study content

### 🎮 Mini-Games
- **Tic-Tac-Toe** — Classic strategy game as a brain break
- **Reaction Test** — Sharpen your reflexes between study sessions
- **Sudoku** — Logical thinking challenge

### 🏅 Gamification System
- **XP & Levels** — Progress from *Novice Explorer* to *Grand Master* (5 levels)
- **Badges** — Unlock achievements like "First Steps", "Quick Learner", "Master Mind"
- **Leaderboard** — Compete with other learners globally
- **Daily Streaks & Stats** — Track quiz completion and average scores

### 👤 User System
- Register / Login with protected routes
- Personal Profile page with stats and achievements
- Notification bell for updates and alerts
- Settings page with customization options

### 🎨 UI/UX
- Dark/Light mode toggle
- Responsive design (mobile + desktop)
- Physics-inspired animated backgrounds
- Smooth transitions with Framer Motion

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 18 + TypeScript |
| Build Tool | Vite |
| Styling | Tailwind CSS |
| UI Components | shadcn/ui + Radix UI |
| Routing | React Router v6 |
| State Management | React Query (TanStack) |
| Animations | Framer Motion |
| Forms | React Hook Form + Zod |

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+) and npm

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<kethan1906>/hackathon.git

# 2. Navigate to the project directory
cd hackathon

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

The app will be available at `http://localhost:5173`.

---

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/              # shadcn/ui base components
│   ├── NavBar.tsx
│   ├── QuizCard.tsx
│   ├── GamesSection.tsx
│   ├── DailyWork.tsx
│   └── ...
├── pages/               # Route-level page components
│   ├── Home.tsx
│   ├── Login.tsx / Register.tsx
│   ├── QuizPage.tsx
│   ├── Leaderboard.tsx
│   └── ...
├── data/                # Static subject & quiz data
│   ├── subjects.ts
│   └── quizData.ts
├── config/
│   └── levels.ts        # XP & level progression config
├── contexts/
│   └── AuthContext.tsx  # Authentication state
└── hooks/               # Custom React hooks
```

---

## 🗺️ Roadmap

These features were planned but not completed during the hackathon:

- [ ] Backend API + database integration (user data, scores, streaks)
- [ ] Real-time leaderboard with live updates
- [ ] Full quiz data for all subjects and chapters
- [ ] AI-generated personalized quiz recommendations
- [ ] Performance analytics dashboard
- [ ] Mobile app (React Native)
- [ ] Social sharing of scores and badges

---

## 👥 Team

Built with ❤️ during a hackathon sprint.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
