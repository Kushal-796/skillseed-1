# SkillSeed: Life Skills & Career Discovery Lab

An AI-driven (future implementation) educational platform for students (Grades 4-10) with a focus on gamified learning, real-world skills, and career exploration.

## 🎯 Features

### Student-Facing Features:

* **Interactive UI:** Gamified dashboard with a "Skill Map" for visualizing progress.
* **Gamification:** XP points, levels, and badges with celebratory animations.
* **Educational Games:** A library of mini-games for a hands-on learning experience.
* **Personalized Learning Paths:** Dynamically generated content streams (initial manual setup, with future AI integration).
* **Firebase Integration:** Real-time data sync for progress, achievements, and game states.

### Teacher-Facing Features:

* **Dashboard:** Clean, professional interface for tracking student progress.
* **Performance Analytics:** Visual charts and graphs to monitor engagement and skill mastery.
* **Student Management:** Tools to assign lessons, challenges, and manage the student roster.
* **Communication:** A secure channel for communicating with students and parents.

## 💻 Tech Stack

* **Frontend:** React.js for the main application, with a focus on UI libraries like **Framer Motion** or **React Spring** for fluid animations.
* **Backend:** Node.js for server-side logic and API creation.
* **Database:** MongoDB for storing user profiles, progress data, and game information.
* **Real-time Data:** Firebase Realtime Database for live updates on student progress and achievements.
* **Styling:** CSS-in-JS libraries like **Styled Components** for interactive and component-level styling.

## 🎨 UI/UX Design

### Color Palette:

* `--primary-blue`: `#4A90E2`
* `--primary-yellow`: `#F5A623`
* `--primary-green`: `#50E3C2`
* `--secondary-pastel-blue`: `#D5E8F7`
* `--secondary-pastel-yellow`: `#FDF2D9`
* `--background-color`: `#F5F8FA`
* **Interactive Glow:** A pulsing glow effect on buttons and active elements.

### Animations:

* **Component Transitions:** Page and panel transitions will use `ease-in-out` animations.
* **Feedback Animations:** Use confetti, sparkle, or glowing effects for positive reinforcement.
* **Button States:** Buttons will scale up slightly on hover/tap.

## 🚀 Getting Started

### Prerequisites

* Node.js (LTS version)
* npm or Yarn
* A Firebase project with Realtime Database enabled.
* A MongoDB Atlas cluster (or a local instance).

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [repository-url]
    cd SkillSeed
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Firebase Connection:**
    * Create a `.env` file in the root directory.
    * Add your Firebase configuration details:
    ```
    REACT_APP_FIREBASE_API_KEY=your-api-key
    REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
    REACT_APP_FIREBASE_DATABASE_URL=your-database-url
    # ... other Firebase config
    ```
    * Ensure your Firebase Realtime Database security rules are configured to allow reads/writes for authenticated users.

4.  **MongoDB Connection:**
    * Configure your MongoDB connection string in the Node.js backend.

5.  **Run the application:**
    * To start the frontend: `npm start`
    * To start the backend (if separate): `node server.js`

## 🕹️ Interactive Game Ideas

* **Word Puzzle:** A word-based game where students solve a puzzle to unlock a new skill badge.
* **Financial Maze:** A mini-game where students navigate a maze by making correct financial decisions.
* **Leadership Tower:** A tower-building game where each correct answer or challenge completion adds a new floor to their virtual leadership tower.
