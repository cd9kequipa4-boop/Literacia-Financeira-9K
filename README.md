# Teen Spending Coach & Wealth Predictor

A modern web application built with React and TypeScript to help teenagers develop healthy financial habits and predict their financial future.

## Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS
- **Database**: Supabase
- **UI Components**: Lucide React (icons)

## Getting Started

### Prerequisites

- Node.js 16+
- npm or yarn

### Installation

1. Install dependencies:
   ```bash
   npm install
   ```

2. Configure environment variables in `.env`:
   ```
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint
- `npm run typecheck` - Check TypeScript types

## Project Structure

```
src/
├── App.tsx           # Main application component
├── main.tsx          # Application entry point
├── index.css         # Global styles
└── vite-env.d.ts     # Vite environment types
```

## Features

- User authentication with Supabase
- Spending tracking and analytics
- Financial goal setting
- Wealth prediction based on savings patterns
- Responsive design for mobile and desktop

## Development

The project uses:
- **Vite** for fast development and optimized builds
- **TypeScript** for type safety
- **Tailwind CSS** for utility-first styling
- **ESLint** for code quality

## Building for Production

```bash
npm run build
```

The optimized build will be generated in the `dist/` directory.

## License

MIT
