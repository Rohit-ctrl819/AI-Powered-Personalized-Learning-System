# EduAI - AI-Powered Personalized Learning System

A comprehensive college mini project demonstrating an AI-powered personalized learning system for students. This application showcases modern web development practices with Next.js, TypeScript, and Tailwind CSS.

## Features

### 1. Demo Login System
- Easy login with any email/password combination
- No real authentication required (demo mode)
- Instant dashboard access

### 2. Dashboard
- **Student Profile**: View personal information and achievements
- **Learning Statistics**: Study streak, accuracy rate, total hours studied, quizzes completed
- **Subject Performance**: Track progress in Mathematics, Physics, Chemistry, and Biology
- **AI Recommendations**: Intelligent suggestions based on performance analysis
- **Recent Activities**: Timeline of all learning activities with scores and timestamps

### 3. Quiz Module
- **Interactive MCQ Quizzes**: Multiple choice questions with instant feedback
- **Quiz Management**: Browse, filter, and attempt quizzes by difficulty
- **Score Calculation**: Automatic scoring and performance analysis
- **Answer Review**: Detailed explanation for each question
- **Quiz Statistics**: Track attempts, performance trends, and achievement levels

### 4. Emotion Analysis
- **Emotion Detection**: Detect four emotional states (Focused, Happy, Stressed, Tired)
- **Dynamic Recommendations**: AI-powered suggestions based on emotional state
- **Learning Tips**: Emotion-specific guidance for optimal learning
- **Mood Tracking**: Weekly emotional trends visualization

### 5. Analytics Dashboard
- **Weekly Study Progress**: Line charts showing study hours by day
- **Subject Performance**: Pie charts displaying subject-wise performance
- **Monthly Trends**: Bar charts tracking progress over weeks
- **Quiz Statistics**: Difficulty-wise quiz performance analysis
- **Personalized Insights**: AI-generated insights and recommendations

### 6. About Project
- Problem statement and objectives
- Detailed feature list
- Technology stack documentation
- Future enhancement roadmap
- Project information and status

## Project Structure

```
app/
├── page.tsx                    # Login page
├── layout.tsx                  # Root layout with metadata
├── globals.css                 # Global styles with design tokens
├── dashboard/
│   ├── page.tsx               # Main dashboard
│   ├── layout.tsx             # Dashboard layout
│   ├── quizzes/page.tsx       # Quiz module page
│   └── analytics/page.tsx     # Analytics dashboard
├── emotion-analysis/
│   └── page.tsx               # Emotion analysis page
└── about/page.tsx             # About project page

components/
├── navbar.tsx                 # Top navigation bar
├── sidebar.tsx                # Left sidebar navigation
├── dashboard-card.tsx         # Reusable dashboard card component
├── emotion-card.tsx           # Emotion selection card
├── quiz-card.tsx              # Quiz card component
├── recommendation-card.tsx    # Recommendation card
└── analytics-chart.tsx        # Chart component wrapper

lib/
├── mock-data.ts              # Mock data for the entire application
├── helpers.ts                # Utility and helper functions
└── recommendation-engine.ts  # AI recommendation logic

types/
├── student.ts                # Student and learning related types
├── quiz.ts                   # Quiz related type definitions
└── emotion.ts                # Emotion analysis types
```

## Technology Stack

### Frontend
- **Framework**: Next.js 16 - Modern React framework with SSR
- **Language**: TypeScript - Type-safe development
- **Styling**: Tailwind CSS v4 - Utility-first CSS framework
- **Icons**: Lucide React - Beautiful and consistent icon library
- **Charts**: Recharts - React components for building data visualizations

### Architecture
- **Mock Data System**: No backend/database required for demo
- **Client-side Storage**: LocalStorage for session management
- **Modular Components**: Reusable React components with composition
- **Type Definitions**: Comprehensive TypeScript interfaces for type safety
- **Helper Functions**: Utility functions for common operations

## Getting Started

### Installation

```bash
# Install dependencies
pnpm install

# or
npm install

# or
yarn install
```

### Running the Development Server

```bash
pnpm dev
# or
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

### Building for Production

```bash
pnpm build
pnpm start
```

## Demo Login Credentials

Use any email and password to log in:
- Email: `student@example.com` (or any email)
- Password: `any-password` (or any password)

The system will instantly grant access to the full application.

## Key Pages

| Page | Route | Description |
|------|-------|-------------|
| Login | `/` | Demo login page |
| Dashboard | `/dashboard` | Main student dashboard with stats |
| Quizzes | `/dashboard/quizzes` | Interactive quiz system |
| Analytics | `/dashboard/analytics` | Learning analytics and charts |
| Emotion Analysis | `/emotion-analysis` | Emotion detection and recommendations |
| About | `/about` | Project information and documentation |

## Features Explained

### AI Recommendations
The recommendation engine analyzes:
- Student performance in each subject
- Quiz accuracy and trends
- Learning patterns and time spent
- Weak topics and strengths
- Current study streak and consistency

Generates intelligent suggestions for:
- Topics needing revision
- New advanced concepts to explore
- Optimal study timing
- Practice recommendations

### Emotion-Based Learning
Four emotional states with tailored guidance:
1. **Focused** - Optimal for difficult topics and new concepts
2. **Happy** - Best for collaborative learning and quizzes
3. **Stressed** - Recommended for light revision and breaks
4. **Tired** - Suitable for short sessions and flashcard review

### Learning Analytics
Comprehensive visualization of:
- Daily and weekly study patterns
- Subject-wise performance distribution
- Monthly progress trends
- Quiz completion statistics
- Achievement tracking

## Code Quality

- **TypeScript**: Comprehensive type safety throughout the application
- **Component Architecture**: Reusable, composable React components
- **Code Comments**: Well-documented code with JSDoc comments
- **Helper Functions**: Centralized utilities for common operations
- **Mock Data**: Structured mock data for realistic demonstrations

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Fast page loads with Next.js optimization
- Responsive design for all screen sizes
- Smooth animations and transitions
- Optimized chart rendering with Recharts
- Client-side caching with localStorage

## Future Enhancements

1. **Real Authentication**: OAuth2 with Google/GitHub
2. **Database Integration**: PostgreSQL/MongoDB for data persistence
3. **Real AI Model**: Machine learning for actual emotion detection
4. **Live Chat**: Real-time tutor assistance
5. **Mobile App**: Native iOS/Android applications
6. **Multiplayer Features**: Peer collaboration and group learning
7. **Gamification**: Badges, achievements, leaderboards
8. **Video Content**: Integrated video lessons and tutorials

## Project Information

- **Type**: College Mini Project
- **Status**: Fully Functional Demo
- **Duration**: 2-3 months development
- **Team Size**: Individual project
- **Repository**: Available on GitHub

## Author Notes

This project was designed as a comprehensive demonstration of:
- Modern React development with Next.js
- TypeScript for type-safe applications
- Responsive UI design with Tailwind CSS
- Component-based architecture
- State management and data flow
- API integration patterns
- Performance optimization
- Professional project structure

## License

This project is available for educational purposes. You are free to use, modify, and distribute it as needed for your college project or learning.

## Support

For questions, issues, or suggestions, please refer to the About page in the application for more information about the project.

---

**Built with ❤️ using Next.js, TypeScript, and Tailwind CSS**
