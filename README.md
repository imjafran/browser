# 🕵️‍♂️ Browser Detective

**Comprehensive System & Browser Fingerprinting Tool**

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue)](https://browser.jafran.online)
[![Developer](https://img.shields.io/badge/Developer-Jafran%20Hasan-green)](https://fb.com/iamjafran)
[![Feedback](https://img.shields.io/badge/Feedback-Form-orange)](https://forms.gle/u4QjCHiyN8gJzPBD8)

---

## 📋 Description

Browser Detective is a comprehensive web-based tool that provides detailed insights about your browser, device, system, and network information. It creates a complete "fingerprint" of your browsing environment for security analysis, debugging, or educational purposes.

**🔒 Privacy First:** All data is processed locally in your browser with complete privacy protection. No information is stored on servers - data sharing works through URL encoding.

---

## ✨ Key Features

### 🌐 Browser Details
- Browser name, version, variant, and engine information
- Language preferences and capabilities  
- Java, cookies, PDF viewer support
- Real-time current time display
- WebDriver detection

### 💻 System Information
- Operating system and version detection
- Architecture (x86, x64, ARM)
- Hardware concurrency (CPU cores)
- Device memory information
- Touch capabilities

### 🖥️ Display & Device
- Screen resolution and available space
- Color depth and pixel ratio
- Device orientation
- Viewport dimensions
- Touch support detection

### 🌍 Location & Network
- Public IP address and geolocation
- ISP and ASN information
- Connection type and speed
- Browser and IP timezone
- City, region, country details

### ⚙️ Technical Features
- Storage APIs (localStorage, sessionStorage, IndexedDB)
- Modern web APIs (WebGL, WebRTC, WebAssembly)
- Worker support (Web Workers, Service Workers)
- Security APIs (Web Crypto, Permissions)
- Observer APIs and ES6 features

### 🔒 Security & Privacy
- HTTPS detection
- Do Not Track status
- Permission API support
- WebDriver detection
- Security feature analysis

### 📊 Performance & Memory
- JavaScript heap memory usage
- Page load and DOM ready times
- Navigation type
- Performance metrics

### 🎵 Media & Audio
- Audio/video codec support
- Format compatibility (MP3, WAV, MP4, WebM, etc.)
- Advanced codec support (H.264, AV1)
- Web Audio API detection

### 📋 Session Information
- Current session details
- Page URL and referrer
- Character set and document title
- User agent string

---

## 🚀 How to Use

### Basic Usage
1. Open the tool in your web browser
2. All information loads automatically
3. Browse through different sections using the collapsible cards
4. Use the floating toggle button to expand/collapse all sections

### Sharing Data
1. Click **"Share Link"** button
2. Complete browser data is collected (including IP info)
3. Shareable URL is copied to clipboard
4. Send the URL to share your browser fingerprint

### Exporting Data
1. Click **"Export"** dropdown button
2. Choose **"Download Image"** for PNG screenshot
3. Choose **"Export as CSV"** for spreadsheet data
4. Use **"Copy Image"** to copy screenshot to clipboard

### Feedback
- Use the feedback link in the footer to report issues or suggest improvements

---

## 🛠️ Technical Details

### Technology Stack
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Styling:** Tailwind CSS
- **Image Generation:** html2canvas
- **APIs:** Multiple IP geolocation services

### Browser Compatibility
- **Modern browsers:** Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **Mobile browsers:** Fully supported
- **Progressive enhancement** for older browsers

### API Endpoints
Multiple IP detection services for reliability:
- `api.ipify.org`
- `ipapi.co`
- `ipinfo.io` 
- `api.ip.sb`
- `api.my-ip.io`

### Data Collection
- ✅ All data collected client-side using browser APIs
- ✅ No server-side processing or storage
- ✅ No cookies or tracking
- ✅ No external dependencies for core functionality

### URL Sharing
- Data encoded in URL parameters
- JSON compression and URL encoding
- Supports URLs up to 8000+ characters
- Backward compatibility with older share formats

---

## 🔐 Privacy & Security

### Privacy First Approach
- ✅ All data processed locally in your browser
- ✅ No server-side storage or logging
- ✅ No cookies or tracking scripts
- ✅ No external analytics or monitoring
- ✅ No user registration required

### Data Sharing
- Sharing works through URL encoding only
- Your data travels directly via the share link
- Recipients see only what you explicitly share
- No intermediary servers involved

### Security Features
- HTTPS enforced for secure connections
- No sensitive data collection
- No password or personal information requests
- Open source and transparent

---

## 📁 File Structure

```
liquid/
├── index.html          # Main application file
├── README.md          # This file
└── README.txt         # Plain text version
```

### Main Components
- HTML structure with semantic sections
- CSS styling with glass morphism design
- JavaScript for data collection and UI
- Responsive design for all devices

---

## 🌐 Browser Support

### Fully Supported
| Browser | Version | Platforms |
|---------|---------|-----------|
| Chrome | 80+ | Windows, Mac, Linux, Android |
| Firefox | 75+ | Windows, Mac, Linux, Android |
| Safari | 13+ | Mac, iOS |
| Edge | 80+ | Windows |

### Mobile Support
- ✅ Responsive design works on all screen sizes
- ✅ Touch-optimized interface  
- ✅ Mobile-specific data collection
- ✅ iOS and Android compatibility

---

## 💻 Development

### Getting Started
1. Clone or download the project files
2. Open `index.html` in a web browser
3. No build process or dependencies required
4. Works locally or on any web server

### Customization
- Modify CSS variables for theming
- Add new data collection functions
- Extend sharing formats
- Add new export options

### Contributing
- Report issues via the [feedback form](https://forms.gle/u4QjCHiyN8gJzPBD8)
- Suggest improvements or new features
- Contact developer for collaboration

---

## 📝 Changelog

### Version 2.0 (Current)
- ✅ Added comprehensive data sharing
- ✅ Enhanced IP geolocation with multiple APIs
- ✅ Real-time current time display
- ✅ Modern glass morphism UI design
- ✅ Advanced error handling and debugging
- ✅ CSV export functionality
- ✅ Image download and clipboard copy
- ✅ Mobile-responsive design improvements

### Version 1.0
- Initial release with basic browser detection
- Simple data display
- Basic sharing functionality

---

## 👨‍💻 Developer & Credits

**Jafran Hasan**
- 🌐 Website: [browser.jafran.online](https://browser.jafran.online)
- 👤 Facebook: [fb.com/iamjafran](https://fb.com/iamjafran)

### Technologies Used
- [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS framework
- [html2canvas](https://html2canvas.hertzen.com) - Screenshot generation
- Various IP geolocation APIs
- Modern Web APIs and browser capabilities

### License
This project is created for educational and development purposes.
Please respect privacy and use responsibly.

---

## 🆘 Support & Feedback

### 📝 Feedback Form
[https://forms.gle/u4QjCHiyN8gJzPBD8](https://forms.gle/u4QjCHiyN8gJzPBD8)

### 📞 Contact
- **Facebook:** [fb.com/iamjafran](https://fb.com/iamjafran)
- **Website:** [browser.jafran.online](https://browser.jafran.online)

### 🐛 Issues & Suggestions
- Use the feedback form for bug reports
- Suggest new features or improvements
- Report browser compatibility issues

---

## ❓ Frequently Asked Questions

<details>
<summary><strong>Is my data stored anywhere?</strong></summary>
<br>
No, all data is processed locally in your browser. Nothing is stored on servers.
</details>

<details>
<summary><strong>How does sharing work?</strong></summary>
<br>
Data is encoded in the URL itself. When you share a link, the data travels directly through the URL parameters.
</details>

<details>
<summary><strong>Why do some shared links show "Unknown" values?</strong></summary>
<br>
Older share links or links from different browser versions may have limited data. New shares include comprehensive information.
</details>

<details>
<summary><strong>Is this tool safe to use?</strong></summary>
<br>
Yes, it only reads publicly available browser information and doesn't access any personal data, passwords, or sensitive information.
</details>

<details>
<summary><strong>Can I use this for commercial purposes?</strong></summary>
<br>
Contact the developer for commercial licensing and usage permissions.
</details>

<details>
<summary><strong>How accurate is the location information?</strong></summary>
<br>
Location is based on IP geolocation, which is generally accurate to city level but may vary depending on your internet provider.
</details>

---

## 🎯 Live Demo

**Try it now:** [https://browser.jafran.online](https://browser.jafran.online)

---

<div align="center">

**Thank you for using Browser Detective!** 🕵️‍♂️

For the latest updates and information, visit: [browser.jafran.online](https://browser.jafran.online)

</div> 
