# Learning Sphere Platform

Adaptive learning platform with AI-driven personalization powered by React, TypeScript, and Firebase.

## Features

- 🎓 Adaptive Learning System
- 🤖 AI-Driven Personalization
- 🔐 Secure Authentication
- 📊 Progress Tracking
- 💾 Firebase Realtime Database

## Tech Stack

- **Frontend:** React 18, TypeScript
- **Backend:** Firebase (Auth, Firestore, Storage)
- **Testing:** Jest, React Testing Library
- **Deployment:** Vercel
- **Code Quality:** ESLint, Prettier

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/agodike-eng/learnsphere-platform.git
   cd learnsphere-platform
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.local.example .env.local
   ```
   Add your Firebase credentials to `.env.local`

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Run tests**
   ```bash
   npm test
   ```

## Project Structure

```
src/
├── config/          # Configuration files
├── services/        # API and service functions
├── components/      # React components
├── App.tsx         # Main app component
└── index.tsx       # Entry point
```

## Contributing

Feel free to submit issues and pull requests!

## License

MIT
