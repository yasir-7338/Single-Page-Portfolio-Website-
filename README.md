# Mohammed Yasir K - Portfolio Website

A modern, responsive portfolio website built with Next.js, React, and Tailwind CSS.

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (version 18.0 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone or extract the project**
   \`\`\`bash
   # If you have the ZIP file, extract it to your desired location
   # If using git:
   git clone <repository-url>
   cd Yasir-portfolio
   \`\`\`

2. **Install dependencies**
   \`\`\`bash
   npm install
   # or
   yarn install
   \`\`\`

3. **Run the development server**
   \`\`\`bash
   npm run dev
   # or
   yarn dev
   \`\`\`

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to see the website.

## 🛠️ Development Setup in VS Code

### Recommended Extensions

Install these VS Code extensions for the best development experience:

1. **ES7+ React/Redux/React-Native snippets** - Provides useful React snippets
2. **Tailwind CSS IntelliSense** - Autocomplete for Tailwind classes
3. **TypeScript Importer** - Auto import for TypeScript
4. **Prettier - Code formatter** - Code formatting
5. **Auto Rename Tag** - Automatically rename paired HTML/JSX tags
6. **Bracket Pair Colorizer** - Color matching brackets
7. **GitLens** - Enhanced Git capabilities

### VS Code Settings

Create a `.vscode/settings.json` file in your project root:

\`\`\`json
{
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "typescript.preferences.importModuleSpecifier": "relative",
  "emmet.includeLanguages": {
    "typescript": "html",
    "typescriptreact": "html"
  }
}
\`\`\`

## 📁 Project Structure

\`\`\`
Yasir-portfolio/
├── app/                    # Next.js App Router
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx          # Home page
├── components/            # Reusable components
│   ├── ui/               # UI components (shadcn/ui)
│   └── theme-provider.tsx
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
├── public/               # Static assets
├── .vscode/              # VS Code configuration
├── next.config.mjs       # Next.js configuration
├── package.json          # Dependencies and scripts
├── tailwind.config.ts    # Tailwind CSS configuration
└── tsconfig.json         # TypeScript configuration
\`\`\`

## 🎨 Features

- **Responsive Design** - Works on all devices
- **Modern UI** - Built with shadcn/ui components
- **Smooth Animations** - CSS animations and transitions
- **Project Showcase** - Interactive project gallery
- **Contact Form** - Easy way to get in touch
- **SEO Optimized** - Meta tags and structured data
- **Performance Optimized** - Fast loading and smooth interactions

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🚨 Troubleshooting

### Common Issues

1. **Port 3000 already in use**
   \`\`\`bash
   # Kill the process using port 3000
   npx kill-port 3000
   # Or use a different port
   npm run dev -- -p 3001
   \`\`\`

2. **Module not found errors**
   \`\`\`bash
   # Clear node_modules and reinstall
   rm -rf node_modules package-lock.json
   npm install
   \`\`\`

3. **TypeScript errors**
   \`\`\`bash
   # Check TypeScript configuration
   npx tsc --noEmit
   \`\`\`

4. **Styling issues**
   \`\`\`bash
   # Rebuild Tailwind CSS
   npm run build
   \`\`\`

### VS Code Specific Issues

1. **IntelliSense not working**
   - Restart TypeScript server: `Ctrl+Shift+P` → "TypeScript: Restart TS Server"
   - Check if TypeScript extension is enabled

2. **Import suggestions not working**
   - Check `tsconfig.json` paths configuration
   - Restart VS Code

3. **Tailwind classes not autocompleting**
   - Install "Tailwind CSS IntelliSense" extension
   - Check `tailwind.config.ts` is properly configured

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Performance Tips

1. **Images**: Use Next.js Image component for optimization
2. **Fonts**: Preload critical fonts
3. **Code Splitting**: Components are automatically code-split
4. **Caching**: Static assets are cached by default

## 📞 Support

If you encounter any issues:

1. Check this README for common solutions
2. Look at the browser console for error messages
3. Ensure all dependencies are installed correctly
4. Try clearing cache and rebuilding

## 📄 License

This project is for portfolio purposes. Feel free to use as inspiration for your own portfolio!
