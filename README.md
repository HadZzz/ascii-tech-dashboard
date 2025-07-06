# 🚀 ASCII Tech Dashboard

<div align="center">

![ASCII Tech Dashboard](https://img.shields.io/badge/ASCII-Tech%20Dashboard-00ff41?style=for-the-badge&logo=terminal&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A Professional ASCII-based Tech Dashboard with Interactive Terminal and Real-time System Monitoring**

[🌟 Live Demo](https://hadzzz.github.io/ascii-tech-dashboard) • [📖 Documentation](#features) • [🚀 Quick Start](#quick-start)

</div>

---

## ✨ Features

### 🖥️ **Professional Dashboard Layout**
- **3-Panel Grid Layout** - Sidebar, Main Content, Right Panel
- **Real-time Clock** - Updates every second
- **Status Indicators** - Color-coded system health
- **Modern Dark Theme** - Matrix-inspired design with neon effects

### 💻 **Interactive Terminal**
- **Working Command Line** - Type real commands
- **Built-in Commands**: `help`, `status`, `ps`, `top`, `ping`, `ls`, `whoami`, `date`, `uptime`
- **Command History** - Scrollable output
- **Auto-complete Ready** - Extensible command system

### 📊 **Real-time Monitoring**
- **System Status** - CPU, Memory, Disk, Network usage
- **Live ASCII Charts** - Dynamic bar charts and visualizations
- **Performance Metrics** - Animated performance graphs
- **Network Visualization** - Upload/Download traffic display

### 🎮 **ASCII Animations**
- **Loading Spinner** - Rotating ASCII characters
- **Walking Character** - Animated stick figure
- **Wave Animation** - Ocean wave simulation
- **Bouncing Ball** - Physics-based animation
- **Matrix Effects** - Falling character rain

### 📡 **Live Data Stream**
- **Event Logging** - Real-time system events
- **Auto-scrolling** - Latest events always visible
- **Timestamp** - All events timestamped
- **Event Simulation** - Realistic system activity

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/HadZzz/ascii-tech-dashboard.git
cd ascii-tech-dashboard
```

### 2. Open in Browser
```bash
# Simply open the HTML file
open index.html
# or
firefox index.html
# or
chrome index.html
```

### 3. Start Exploring!
- **Try the Terminal** - Type `help` to see available commands
- **Watch Real-time Updates** - All metrics update automatically
- **Enjoy the Animations** - ASCII art in motion!

---

## 🎯 Demo Commands

Try these commands in the interactive terminal:

```bash
help        # Show all available commands
status      # Display system status
ps          # Show running processes
top         # Display resource usage
ping        # Test network connectivity
ls          # List directory contents
whoami      # Show current user
date        # Display current date/time
uptime      # Show system uptime
clear       # Clear terminal output
```

---

## 🛠️ Technical Details

### Architecture
- **Pure Frontend** - No backend required
- **Vanilla JavaScript** - No frameworks or dependencies
- **CSS Grid & Flexbox** - Modern responsive layout
- **CSS Animations** - Smooth 60fps animations
- **Modular Design** - Easy to extend and customize

### Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

### Performance
- **Lightweight** - Single HTML file (~50KB)
- **Fast Loading** - No external dependencies
- **Efficient Updates** - Optimized refresh intervals
- **Memory Friendly** - Automatic cleanup of old data

---

## 🎨 Customization

### Adding New Terminal Commands
```javascript
const terminalCommands = {
  // Add your custom command here
  mycommand: () => 'Your custom output here',
  // ... existing commands
};
```

### Modifying Update Intervals
```javascript
// Adjust these values in the initDashboard() function
setInterval(updateSystemStatus, 3000);    // System status every 3s
setInterval(updateDataStream, 2000);      // Data stream every 2s
setInterval(updateCPUVisualization, 1500); // CPU viz every 1.5s
```

### Changing Color Scheme
```css
/* Modify these CSS variables */
:root {
  --primary-color: #00ff41;    /* Matrix green */
  --warning-color: #ffaa00;    /* Orange */
  --error-color: #ff4444;      /* Red */
  --info-color: #00aaff;       /* Blue */
}
```

---

## 🌟 Screenshots

### Main Dashboard
```
╔══════════════════════════════════════════════════════════════╗
║  ⚡ ASCII TECH DASHBOARD v2.1.0                    ● ONLINE  ║
╠══════════════════════════════════════════════════════════════╣
║ 🖥️ System Status    ║ 💻 Interactive Terminal    ║ 🚀 Servers ║
║ CPU: ██████████ 67% ║ root@dashboard:~$ help      ║ ● web-01   ║
║ MEM: ████████░░ 82% ║ Available commands:         ║ ● web-02   ║
║ DSK: ██████░░░░ 45% ║ help, status, clear, ps...  ║ ● db-01    ║
║ NET: ████████░░ 78% ║                             ║ ● cache-01 ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Ideas for Contributions
- 🔌 **API Integration** - Connect to real system APIs
- 🎮 **More ASCII Games** - Snake, Tetris, Pong
- 📊 **Advanced Charts** - Pie charts, line graphs
- 🔊 **Sound Effects** - Terminal beeps and clicks
- 📱 **Mobile Optimization** - Touch-friendly interface
- 🌍 **Internationalization** - Multi-language support

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Matrix Movie** - Inspiration for the green-on-black aesthetic
- **Unix/Linux Terminals** - Command structure and behavior
- **ASCII Art Community** - Character art and animations
- **GitHub Community** - Open source inspiration

---

## 📞 Contact

**HadZzz** - [@HadZzz](https://github.com/HadZzz)

**Project Link**: [https://github.com/HadZzz/ascii-tech-dashboard](https://github.com/HadZzz/ascii-tech-dashboard)

---

<div align="center">

**⭐ Star this repo if you found it helpful! ⭐**

Made with ❤️ and lots of ☕

</div>
