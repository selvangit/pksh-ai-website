# PKSH.AI - Navigating the Future of AI

![PKSH.AI Banner](https://img.shields.io/badge/AI-Website-blue?style=for-the-badge&logo=openai)
![Vercel](https://img.shields.io/badge/vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![GitHub](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)

A comprehensive AI-focused website featuring news, events, company insights, and an interactive playground for exploring cutting-edge AI models.

## 🚀 Features

- **🔥 AI News**: Latest developments and breakthroughs in artificial intelligence
- **📅 Events Calendar**: Global AI conferences, meetups, and workshops
- **🏢 Company Ecosystem**: Industry landscape, partnerships, and market analysis
- **🎮 AI Playground**: Interactive tools for testing cutting-edge AI models
- - **🧠 AI Neural Interface**: Dedicated page for exploring AI SDK options (Vercel AI SDK, Google AI Studio, Chatbot Widgets) - opens in separate tab
- **📜 Patent Tracker**: Recent AI patent approvals and innovations
- **📚 Research Papers**: Top publications, citations, and trending research

## 🌐 Live Website

- **🎯 Production**: [https://pksh-ai-website.vercel.app](https://pksh-ai-website.vercel.app)
- **📱 GitHub Pages**: [https://selvangit.github.io/pksh-ai-website](https://selvangit.github.io/pksh-ai-website)

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Framework**: React (CDN)
- **Hosting**: Vercel (Primary), GitHub Pages (Backup)
- **CI/CD**: GitHub Actions
- **Analytics**: Vercel Analytics

## ⚡ Quick Start

### Prerequisites
- Node.js 18+ (for development)
- Git
- Vercel account (free)

### Local Development

```bash
# Clone repository
git clone https://github.com/selvangit/pksh-ai-website.git
cd pksh-ai-website

# Install dependencies
npm install

# Start development server
npm start
# Opens http://localhost:8000
```

### Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy to preview
vercel

# Deploy to production
vercel --prod
```

## 📁 Project Structure

```
pksh-ai-website/
├── README.md                   # This file
├── package.json               # Node.js dependencies
├── vercel.json               # Vercel configuration
├── .gitignore               # Git ignore rules
├── .github/
├── ai-neural-interface.html  # AI Neural Interface (separate tab)
│   └── workflows/
│       ├── deploy-vercel.yml    # Vercel deployment
│       └── deploy-pages.yml     # GitHub Pages deployment
├── public/
│   ├── favicon.ico             # Website icon
│   └── images/                 # Static assets
├── src/
│   ├── index.html             # Main application file
│   ├── styles/
│   │   └── main.css          # Custom styles
│   └── scripts/
│       └── main.js           # JavaScript functionality
└── docs/
    └── deployment.md         # Deployment guide
```

## 🎯 Key Sections

### 🏠 Homepage
- Hero section with compelling AI messaging
- Trending AI news cards
- Call-to-action for playground exploration

### 📰 AI News
- Latest AI breakthroughs and developments
- Categorized news articles
- Real-time updates on industry trends

### 📅 AI Events
- Global AI conferences and meetups
- Filtering by location and date
- Event details and registration links

### 🏢 AI Companies
- Industry ecosystem mapping
- Company valuations and partnerships
- Market analysis and trends

### 🎮 AI Playground
- Interactive AI model testing
- Support for multiple model types:
  - Text Generation (GPT-4o, DeepSeek-V3.2)
  - Image Generation (HunyuanImage-3.0)
  - Code Generation (StarCoder2)
  - Speech Models (NeuTTS Air)

### 📜 Patents & Publications
- Recent AI patent approvals
- Top research papers with citation metrics
- Trending research topics

## 🔧 Configuration

### Environment Variables

For Vercel Dashboard:
- `VERCEL_TOKEN`: Vercel API token
- `VERCEL_ORG_ID`: Organization ID  
- `VERCEL_PROJECT_ID`: Project ID

For GitHub Secrets:
- `VERCEL_TOKEN`: From Vercel account settings
- `VERCEL_ORG_ID`: From Vercel project settings
- `VERCEL_PROJECT_ID`: From Vercel project settings

## 📊 Performance & Analytics

- **Lighthouse Score**: 95+ across all metrics
- **Core Web Vitals**: All green
- **Global CDN**: Sub-100ms response times
- **Analytics**: Built-in Vercel Analytics
- **SEO Optimized**: Meta tags and structured data

## 🚢 Deployment

### Automatic Deployment
- **Push to main**: Triggers automatic deployment to both Vercel and GitHub Pages
- **Pull Requests**: Generate preview deployments for testing
- **Rollback**: Easy rollback to previous versions

### Manual Deployment
```bash
# Vercel
vercel --prod

# GitHub Pages
git push origin main
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📈 Roadmap

- [ ] Real-time AI model API integrations
- [ ] User authentication and personalization
- [ ] Advanced filtering and search capabilities
- [ ] Mobile app development
- [ ] Multi-language support
- [ ] AI-powered content recommendations

## 🔒 Security

- HTTPS enforced across all environments
- Content Security Policy headers implemented
- XSS protection enabled
- Frame denial for clickjacking prevention
- No sensitive data exposed in client-side code

## 📱 Mobile Responsive

- Fully responsive design
- Touch-friendly interface
- Optimized for all screen sizes
- Progressive Web App capabilities

## 🌟 Acknowledgments

- **OpenAI** for API access and model information
- **Hugging Face** for open-source model data
- **Financial Times** for AI ecosystem insights
- **Research institutions** for publication data
- **AI community** for continuous feedback

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact & Support

- **GitHub Issues**: [Report bugs or request features](https://github.com/selvangit/pksh-ai-website/issues)
- **Repository**: [https://github.com/selvangit/pksh-ai-website](https://github.com/selvangit/pksh-ai-website)
- **Vercel Dashboard**: Monitor deployments and analytics

---

**🤖 Built with ❤️ for the AI community by [selvangit](https://github.com/selvangit)**

![AI](https://img.shields.io/badge/Made%20for-AI%20Community-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge)
