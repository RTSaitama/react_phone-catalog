# Nice Gadgets Frontend

🛍️ Modern e-commerce frontend application built with React, TypeScript, and Vite.

## 🚀 [**► LIVE DEMO ◄**](https://RTSaitama.github.io/nice-gadgets-frontend/)

> 🌟 **[Click here to view the live application](https://RTSaitama.github.io/nice-gadgets-frontend/)** 🌟

## ✨ Features

- 🎨 Modern, responsive design with Tailwind CSS
- 🌙 Dark/Light theme support
- 🌐 Internationalization (i18n) support
- 📱 Mobile-first responsive design
- ⚡ Fast loading with Vite
- 🔥 Firebase integration
- 🎯 TypeScript for type safety
- 📦 Component library with Radix UI
- 🎭 Smooth animations with Motion
- 🍞 Toast notifications with Sonner

## 🛠️ Tech Stack

- **Frontend Framework:** React 19
- **Build Tool:** Vite 7
- **Language:** TypeScript
- **Styling:** Tailwind CSS 4, Bulma
- **UI Components:** Radix UI, Headless UI
- **Animations:** Motion (Framer Motion)
- **Routing:** React Router DOM
- **Internationalization:** i18next
- **Backend:** Firebase
- **State Management:** React Hooks
- **Deployment:** GitHub Pages

## 🚀 Getting Started

### Prerequisites

- Node.js (version 18+)
- npm or yarn

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/RTSaitama/nice-gadgets-frontend.git
   cd nice-gadgets-frontend
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 📋 Available Scripts

| Script              | Description                |
| ------------------- | -------------------------- |
| `npm run dev`       | Start development server   |
| `npm run build`     | Build for production       |
| `npm run preview`   | Preview production build   |
| `npm run lint`      | Run ESLint                 |
| `npm run format`    | Format code with Prettier  |
| `npm run fix-style` | Fix linting and formatting |
| `npm run deploy`    | Deploy to GitHub Pages     |

## 🚀 Deployment

This project is automatically deployed to GitHub Pages. To deploy manually:

```bash
npm run deploy
```

The deployment process:

1. Builds the project (`npm run build`)
2. Deploys the `dist` folder to the `gh-pages` branch
3. Site becomes available at `https://RTSaitama.github.io/nice-gadgets-frontend/`

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
├── pages/              # Page components
├── hooks/              # Custom React hooks
├── utils/              # Utility functions
├── types/              # TypeScript type definitions
├── styles/             # Global styles
├── locales/            # i18n translation files
└── firebase/           # Firebase configuration
```

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
# Add other Firebase config variables
```

### Vite Configuration

The project uses Vite with the following key configurations:

- React plugin for Fast Refresh
- TypeScript support
- Tailwind CSS integration
- SVG support
- GitHub Pages deployment base path

## 🌐 Internationalization

The app supports multiple languages using i18next:

- English (default)
- Ukrainian
- Add more languages in `src/locales/`

## 🎨 Theming

The application supports both light and dark themes:

- Automatic system theme detection
- Manual theme switching
- Persistent theme preference

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Code Style

This project uses:

- **ESLint** for code linting
- **Prettier** for code formatting
- **Husky** for pre-commit hooks
- **TypeScript** for type checking

Code is automatically formatted on commit.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**RTSaitama**

- GitHub: [@RTSaitama](https://github.com/RTSaitama)
- Email: your.email@example.com

## 🙏 Acknowledgments

- Built with [Vite](https://vitejs.dev/)
- UI components from [Radix UI](https://www.radix-ui.com/)
- Styling with [Tailwind CSS](https://tailwindcss.com/)
- Icons from [Lucide React](https://lucide.dev/)

---

⭐ Star this repository if you find it helpful!
