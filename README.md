# 🎭 Hollywood Hacker Prank Website

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

A theatrical "hacking" simulator that pranks users with Hollywood-style visual effects, fake system breaches, and dramatic warnings. **Completely harmless** - all effects are purely visual with no actual data collection or system access.

## 🎬 Demo

Visit the live demo: [Your-Demo-Link-Here]

![Screenshot](screenshot.png)

## ✨ Features

### 🎨 Visual Effects
- **Matrix Rain Animation** - Falling green characters with Japanese text
- **CRT Monitor Scanlines** - Authentic retro terminal aesthetic
- **Screen Glitch Effects** - Random red flashes and distortions
- **Custom Animated Cursor** - Pulsing crosshair cursor
- **Screen Shake** - Random vibrations for dramatic impact
- **Warning Popups** - Critical alert banners

### 💻 Fake "Hacking" Elements

#### 🔴 System Breach Panel
- Animated skull with rotation and shake effects
- Flashing warning banners
- "Remote Access Established" messaging

#### 📹 Camera Access Breached
- Live "REC" indicator with blinking effect
- Front/Rear camera status display
- Camera feed visualization

#### 🔓 Accounts Compromised
- Progressive reveal of "breached" accounts:
  - Gmail
  - Facebook
  - LinkedIn
  - Instagram
  - Twitter
  - Banking
  - Amazon
  - Steam
- Real-time password extraction counter
- Animated progress bar

#### 🌍 Live Location Traced
- Animated GPS trace lines
- Fake IP address generation
- Random city location display
- GPS coordinates with decimals
- Map-style visualization

#### 📡 Satellite Data Transfer
- Spinning satellite icon animation
- Real-time upload speed (MB/s)
- Files copied counter
- Data sent tracker (GB)

#### ⚡ Root Access Panel
- Admin rights granted
- Kernel access enabled
- Backdoor installation status
- Dangerous red-themed alerts

#### 💾 System Information Extraction
- Real OS detection (harmless)
- Real browser detection
- Real screen resolution
- Animated progress bars

#### 📟 Terminal Window
- 16+ detailed fake hacking commands
- Color-coded messages:
  - 🟢 Green - Success
  - 🟡 Yellow - Warning
  - 🔴 Red - Error
  - 🔵 Cyan - Info
- Auto-scrolling terminal output
- Realistic command syntax

### ⏱️ Dynamic Timing
- 10-second countdown to "system reboot"
- 18-second auto-reveal of prank
- Progressive animation reveals
- Staggered effect timing

## 🚀 Quick Start

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/suhasjk07/hollywood-hacker-prank.git
cd hollywood-hacker-prank
```

2. **Open the file**
```bash
# Simply open index.html in your browser
open index.html
# Or on Windows
start index.html
# Or on Linux
xdg-open index.html
```

That's it! No dependencies, no build process, no server required.

### Usage

1. Open `index.html` in any modern web browser
2. Share the link with friends (or deploy to a web server)
3. Watch them panic! 😄
4. The prank auto-reveals after 18 seconds, or they can click "EMERGENCY SHUTDOWN."

## 📁 Project Structure

```
hollywood-hacker-prank/
│
├── index.html          # Main HTML file (all-in-one)
├── README.md           # This file
├── LICENSE             # MIT License
└── screenshot.png      # Screenshot for README
```

## 🎯 How It Works

### Pure Client-Side Technology
- **No Backend Required** - Runs entirely in the browser
- **No Data Collection** - Zero actual data harvesting
- **No Tracking** - Completely privacy-friendly
- **No External Dependencies** - Self-contained HTML file

### Technical Implementation

#### Matrix Rain Effect
```javascript
// Canvas-based character rain animation
// Uses Japanese characters mixed with binary
// Constantly redraws with fade effect
```

#### Progress Animations
```javascript
// Randomized incremental progress bars
// Shimmer effects using CSS keyframes
// Timed intervals for realistic progression
```

#### Dynamic Counters
```javascript
// Files, passwords, data counters
// Random increments with realistic timing
// Auto-stop at predefined limits
```

#### Fake System Detection
```javascript
// Uses navigator.platform for OS
// Uses navigator.userAgent for browser
// Uses screen.width/height for resolution
// Generates random fake IP addresses
```

## 🛠️ Customization

### Change Timing
Edit the countdown duration:
```javascript
let countdown = 10; // Change to desired seconds
```

Auto-reveal timing:
```javascript
setTimeout(() => {
    // Auto-reveal code
}, 18000); // Change 18000 to desired milliseconds
```

### Modify Colors
Change the color scheme in the CSS:
```css
:root {
    --primary-color: #0f0;    /* Matrix green */
    --danger-color: #f00;      /* Alert red */
    --warning-color: #ff0;     /* Warning yellow */
}
```

### Add Custom Accounts
Add more "breached" accounts:
```javascript
const accounts = [
    '📧 Gmail: acc***@gmail.com',
    '🔵 Facebook: user***@fb.com',
    // Add your custom accounts here
];
```

### Customize Messages
Edit terminal messages:
```javascript
const messages = [
    { text: '> Your custom message', type: 'success', delay: 0 },
    // Add more messages
];
```

## 🎭 Use Cases

- **April Fools' Day pranks**
- **Friend pranks and jokes**
- **Cybersecurity awareness demonstrations**
- **Movie/TV show props**
- **Educational purposes (showing fake vs real hacking)**
- **Entertainment at tech events**

## ⚠️ Disclaimer

**IMPORTANT LEGAL NOTICE:**

This project is intended **SOLELY FOR ENTERTAINMENT AND EDUCATIONAL PURPOSES**. 

- ❌ **NO actual hacking** occurs
- ❌ **NO data is collected** or transmitted
- ❌ **NO system access** is gained
- ❌ **NO malicious code** is present
- ✅ **100% visual effects** only

### Responsible Use
- Only use on friends/family who can take a joke
- Always reveal the prank within a reasonable time
- Never use to scare vulnerable individuals (elderly, children)
- Never use for malicious purposes or to cause genuine distress
- Never misrepresent this as real hacking software

**Users are responsible for their use of this software. ** The creator assumes no liability for misuse.**

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Ideas for Contributions
- [ ] Add sound effects
- [ ] Add more visual effects
- [ ] Create mobile-responsive version
- [ ] Add multilingual support
- [ ] Create themes (blue hacker, dark mode, etc.)
- [ ] Add fake file system browser
- [ ] Add fake network packet sniffer visualization

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including, without limitation, the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🙏 Acknowledgments

- Inspired by Hollywood hacking scenes from movies and TV shows
- Matrix rain effect inspired by "The Matrix" (1999)
- Terminal aesthetics inspired by classic Unix/Linux terminals
- Special thanks to the web development community

## 📧 Contact

**Project Creator**: [SUHAS J K]
- GitHub: [@suhasjk07](https://github.com/suhasjk07)
- Email: suhasjk07@duck.com

**Project Link**: [https://github.com/suhasjk07/hollywood-hacker-prank](https://github.com/suhasjk07/hollywood-hacker-prank)

## 🌟 Star History

If you found this project helpful or entertaining, please consider giving it a star! ⭐

---

### 💡 Fun Fact
Did you know? Real hacking looks nothing like this! Actual cybersecurity work involves:
- Reading documentation
- Writing scripts
- Testing vulnerabilities
- Staring at text logs
- Lots of patience

**Stay safe online!** 🔒

---

<div align="center">

Made with ❤️ and JavaScript

**Remember: With great prank power comes great responsibility!** 🕷️

[⬆ Back to Top](#-hollywood-hacker-prank-website)

</div>
