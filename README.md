# Udeler - Udemy Course Downloader (Personal Fork)

<p align="center">
  <img src="https://user-images.githubusercontent.com/13087389/126053559-d4c7d080-0ad3-4deb-83dd-2a52b209e5f2.png" width="128" />
</p>

> 🔗 **Forked From:** [heliomarpm/udemy-downloader-gui](https://github.com/heliomarpm/udemy-downloader-gui)  
> 🔗 **Original Repository:** [FaisalUmair/udemy-downloader-gui](https://github.com/FaisalUmair/udemy-downloader-gui)  
> 📜 **License:** MIT

A cross-platform desktop application for downloading your purchased Udemy courses.

---

## 🎯 About This Fork

This is a personal fork maintained for learning and portfolio purposes.

### Fork Chain
```
FaisalUmair/udemy-downloader-gui (Original, archived)
    └── heliomarpm/udemy-downloader-gui (Active maintainer, +275 commits)
            └── queery-id/udemy-downloader-gui (This fork)
```

### My Contributions

| Type | Description | Status |
|------|-------------|--------|
| 🔍 Analysis | Investigated token authentication issues | ✅ Done |
| 📝 Documentation | Added setup guide and troubleshooting | ✅ Done |
| 🛠️ Build | Local build configuration for Windows | ✅ Done |

---

## 🚀 Quick Start

### Prerequisites
- [Node.js](https://nodejs.org/) (v14+)
- [Git](https://git-scm.com/)

### Installation

```bash
# Clone this repository
git clone https://github.com/queery-id/udemy-downloader-gui.git
cd udemy-downloader-gui

# Setup environment
copy .env.example .env

# Install dependencies
npm install

# Run in development mode
npm run dev

# Or run in production mode
npm start
```

### Build Portable EXE

```bash
# Build for Windows (64-bit)
npm run build

# Output will be in ./dist folder
```

---

## 📋 Troubleshooting

### Token Expired Error

If you encounter "Token expired" error during login:

1. **Use "Get Credentials" button** - Opens embedded browser for Udemy login
2. **Or use Access Token manually:**
   - Login to Udemy in your browser
   - Open DevTools (F12) → Application → Cookies
   - Find `access_token` cookie value
   - Paste it when prompted

### Build Fails with winCodeSign Error

This is usually a network issue. Try:
1. Wait a few minutes and retry
2. Check your internet connection
3. Use VPN if GitHub is blocked in your region

---

## 🙏 Credits & Acknowledgments

| Role | Credit |
|------|--------|
| **Original Author** | [@FaisalUmair](https://github.com/FaisalUmair) |
| **Active Maintainer** | [@heliomarpm](https://github.com/heliomarpm) |
| **This Fork** | [@queery-id](https://github.com/queery-id) |
| **License** | MIT |

> ⚠️ **Disclaimer:** This software is for personal use only. Downloading courses is against Udemy's Terms of Service. Use at your own risk.

---

## 📄 License

[MIT © Heliomar P. Marques](LICENSE)

This fork maintains the original MIT license. See the [LICENSE](LICENSE) file for details.
