# Hello Books Kenya Shop

A modern e-commerce platform for Hello Books Kenya with automated CI/CD deployment pipeline.

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Git
- Vercel account (for deployment)

### Local Development
```bash
# Clone the repository
git clone https://github.com/hellobookskenya/shop.git
cd shop

# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

### Automated Deployment
1. Push code to `main` branch
2. GitHub Actions workflow triggers automatically
3. Code is built and tested
4. Deployed to Vercel
5. Health checks verify deployment

## 📋 CI/CD Pipeline

The repository includes a **complete automated CI/CD pipeline** with:
- ✅ Automated diagnostics
- ✅ Build automation
- ✅ Vercel deployment
- ✅ Health checks
- ✅ Status reporting

See [CI-CD-SETUP.md](./CI-CD-SETUP.md) for detailed setup instructions.

## 🔐 GitHub Secrets Required

Add these secrets to enable deployments:
- `VERCEL_TOKEN` - Vercel API token
- `VERCEL_ORG_ID` - Vercel organization ID
- `VERCEL_PROJECT_ID` - Vercel project ID

## 📁 Project Structure

```
shop/
├── .github/
│   └── workflows/
│       └── ci-cd-deploy.yml    # Automated CI/CD pipeline
├── vercel.json                  # Vercel configuration
├── .vercelignore               # Vercel deployment rules
├── .gitignore                  # Git ignore rules
├── package.json                # Project dependencies
├── CI-CD-SETUP.md              # Detailed setup guide
└── README.md                   # This file
```

## 🛠️ Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run start    # Start production server
npm run test     # Run tests (if configured)
npm run lint     # Run linter (if configured)
```

## 📊 Deployment Status

Latest deployment status available at:
https://github.com/hellobookskenya/shop/actions

## 📝 License

MIT

## 👤 Author

Hello Books Kenya (@hellobookskenya)

---

**🎉 Ready to deploy! Push to main to trigger the automated pipeline.**
