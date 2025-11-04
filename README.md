# PORJECT PPW K3
## 🛠 Tech Stack

- 🛣️ [edgejs](https://docs.adonisjs.com/) as frameworks
- 🎨 [TailwindCSS](https://tailwindcss.com/) with custom theme
- 🎯 [TypeScript](https://www.typescriptlang.org/) for type safety
- 📦 [Vite](https://vitejs.dev/) for fast builds
- 🎭 [edgejs](https://edgejs.dev/) templating engine

## 🚀 Getting Started

### Prerequisites
- Node.js 
- npm or pnpm
- Git
- VS Code (recommended)

### First Time Setup

1. **Clone Repository**

   ```powershell
   git clone https://github.com/username/galacash.git
   cd galacash
   ```

2. **Setup Node.js**

   ```powershell
   # Install and use correct Node.js version
   nvm install lts/*
   nvm use lts/*
   ```

3. **Install Dependencies**

   ```powershell
   # Install project dependencies
   npm install

   # Setup Git hooks
   npm run prepare
   ```

4. **VS Code Setup**
   Install recommended extensions:
   - Edge Template Syntax
   - Adonis JS Extension (bukan yang unggu)
   - Auto Rename Tag
   - Tailwind CSS IntelliSense
   - GitLens

## 🚀 Deployment

### Production Build

```bash
npm run dev
```

## 🔄 Git Workflow

### Commit Convention

```
type(scope): subject
feat(auth): add user authentication
fix(api): handle network errors
docs(readme): update deployment steps
```

### Branch Strategy

- `main`: Production-ready code
- `develop`: Development branch
- `feature/*`: New features
- `fix/*`: Bug fixes


## 📦 Main Project Structure
[app/]       Berisi Controller, Model, Middleware, dan logika bisnis utama.
[config/]    File konfigurasi untuk aplikasi (database, session, dll.).
[database/]  Berisi migration, seeders, dan definisi database lainnya.
[resources/] Semua template EdgeJS (.edge) untuk frontend.
[start/]     Konfigurasi route (start/routes.ts), kernel, dan hooks.
