# JobTrackr - Job Application Tracking System

JobTrackr is a modern web application built with React and TypeScript that helps job seekers organize and manage their job search process effectively.

## Features

- **Application Tracking**: Keep track of all your job applications in one place
- **Dashboard Analytics**: Visual representation of your job search progress
- **Task Management**: Organize and manage job search related tasks
- **Document Storage**: Store and manage resumes, cover letters, and other documents
- **Multi-language Support**: Available in English and Spanish
- **Dark Mode**: Support for light and dark themes
- **Google Authentication**: Secure sign-in with Google OAuth

## Tech Stack

- **Frontend Framework**: React 18
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Router**: React Router v6
- **Icons**: Lucide React
- **Date Handling**: date-fns
- **Authentication**: @react-oauth/google

## Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn package manager

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/job-tracker-app.git
cd job-tracker-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a `.env` file in the root directory and add your Google OAuth client ID:
```env
VITE_GOOGLE_CLIENT_ID=your_google_client_id_here
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:5173](http://localhost:5173) in your browser

## Project Structure

```
job-tracker-app/
├── src/
│   ├── components/        # Reusable UI components
│   ├── context/          # React context providers
│   ├── pages/            # Page components
│   ├── translations/     # i18n translation files
│   ├── App.tsx          # Root component
│   └── main.tsx         # Entry point
├── public/              # Static assets
└── package.json         # Project dependencies
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Key Features Breakdown

### Dashboard
- Overview of application statistics
- Recent applications
- Status distribution chart
- Task completion progress
- Upcoming interviews

### Job Applications
- Add/Edit job applications
- Track application status
- Save favorite positions
- Application history
- Status updates

### Tasks
- Create and manage tasks
- Set due dates and priorities
- Track completion status
- Task categories

### Documents
- Upload and manage documents
- Organize by categories
- Quick access to recent files
- Document version tracking

### Settings
- Language preferences
- Notification settings
- Theme customization
- Time zone settings
- Profile management

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Vite](https://vitejs.dev/) for the build tooling
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Lucide React](https://lucide.dev/) for icons
- [React Router](https://reactrouter.com/) for routing