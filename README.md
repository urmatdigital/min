# Library Management System 📚

A modern library management system built for Kyrgyzstan's libraries, featuring comprehensive management tools and multilingual support.

## Features 🌟

- 🌐 Multilingual Support (Russian, Kyrgyz)
- 🎨 Modern UI with Dark/Light Theme
- 📱 Responsive Design
- 🔒 Secure Authentication
- 📊 Comprehensive Library Management Tools

## Tech Stack 💻

- React + TypeScript
- Vite
- Tailwind CSS
- Supabase
- React Router
- i18next

## Getting Started 🚀

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Git

### Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd library-management-system
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Copy the environment variables:
```bash
cp .env.example .env
```

4. Update the .env file with your Supabase credentials

5. Start the development server:
```bash
npm run dev
# or
yarn dev
```

## Development 🛠️

### Project Structure

```
src/
├── components/     # Reusable UI components
├── pages/         # Page components
├── context/       # React context providers
├── lib/           # Utility functions and configurations
├── locales/       # Translation files
└── styles/        # Global styles and Tailwind configuration
```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
