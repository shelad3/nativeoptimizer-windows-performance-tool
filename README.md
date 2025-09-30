# NativeOptimizer - Windows Performance Suite

[![Version](https://img.shields.io/badge/version-2.1.6-blue.svg)](https://github.com/NativeCodeX/NativeOptimizer/releases)
[![License](https://img.shields.io/badge/license-Proprietary-red.svg)](LICENSE)
[![Discord](https://img.shields.io/discord/123456789012345678?color=7289DA&label=Discord&logo=discord)](https://discord.gg/4HqhKXZ8)

NativeOptimizer is a comprehensive Windows performance optimization suite designed to enhance system performance, monitor hardware, and provide AI-powered assistance. Built with Python and featuring a modern dark-themed GUI, it offers a wide range of tools for system maintenance, optimization, and monitoring.

## ✨ Features

### 📊 System Monitoring
- **Real-time Dashboard**: Live CPU, RAM, Disk, and Network monitoring
- **Hardware Information**: Detailed system specs and component analysis
- **Network Speed Testing**: Download/Upload speed monitoring

### ⚙️ Optimization Tools
- **Performance Enhancer**: System tweaks for improved speed and responsiveness
- **Startup Tasks Manager**: Control and optimize startup programs
- **Services Optimizer**: Manage Windows services for better performance
- **System Tweaks**: Advanced registry and system optimizations
- **Driver Management**: Update and manage device drivers
- **Benchmark Suite**: Performance testing with GPU support

### 🛠️ Maintenance & Security
- **Security Scanner**: System vulnerability assessment
- **Backup & Restore**: System configuration backups
- **Network Optimization**: Internet connection tuning
- **Hardware Diagnostics**: Component health monitoring

### 🤖 AI Integration
- **Gemini AI Assistant**: Google Gemini-powered chat interface
- **Learning Resources**: AI-guided tutorials and documentation
- **Voice Commands**: Speech recognition for hands-free operation (Premium)
- **Creative Tools**: AI-powered content generation (Premium)

### 🎨 User Experience
- **Modern GUI**: CustomTkinter-based dark theme interface
- **Multiple Themes**: Customizable appearance options
- **Admin Mode**: Elevated privileges for system modifications
- **Logging Console**: Real-time operation logging
- **Developer Mode**: Advanced debugging and testing tools

## 🚀 Installation

### Option 1: Download Pre-built Installer (Recommended)

1. Visit the [Releases](https://github.com/NativeCodeX/NativeOptimizer/releases) page
2. Download the latest `NativeOptimizer_Installer_vX.X.X.exe` file
3. Run the installer and follow the setup wizard
4. Launch NativeOptimizer from your desktop or start menu

### Option 2: Build from Source (For Developers)

#### Prerequisites
- **Python 3.8+** (64-bit recommended)
- **Windows 10/11**
- **Administrator privileges** (for full functionality)
- **Inno Setup 6** (for building installer)

#### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/NativeCodeX/NativeOptimizer.git
   cd NativeOptimizer
   ```

2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
   ```

## 📖 Usage

### First Launch
- Accept the End-User License Agreement (EULA)
- Optional: Set up user authentication
- The application will automatically detect admin privileges

### Main Interface
- **Status Bar**: Real-time system metrics
- **Tab Navigation**: Organized into 5 main categories:
  - 📊 System: Dashboard, Hardware, Network
  - ⚙️ Optimization: Performance, Tweaks, Services, Startup, Drivers, Benchmark
  - 🛠️ Maintenance: Security, Backup, Network Optimization
  - 🤖 AI & Learn: Gemini, Learning Resources, Premium Features
  - ⚙️ Settings & Info: Settings, About, Developer Tools

### Key Features Usage
- **Admin Mode**: Toggle for system-level modifications
- **Gemini Overlay**: Floating AI assistant (appears on startup)
- **Themes**: Customize appearance in Settings tab
- **Logging**: Monitor operations in the bottom console

## 🔧 System Requirements

### Minimum Requirements
- **OS**: Windows 10 (64-bit)
- **RAM**: 4 GB
- **Storage**: 500 MB free space
- **Python**: 3.8+ (for source builds)

### Recommended Requirements
- **OS**: Windows 10/11 (64-bit)
- **RAM**: 8 GB+
- **Storage**: 1 GB free space
- **CPU**: Multi-core processor
- **Internet**: Required for AI features and updates

## 🏗️ Build Instructions

### Building the Application
1. Ensure all dependencies are installed
2. Run the build script:
   ```bash
   build.bat
   ```
   This will:
   - Clean previous builds
   - Create executable with PyInstaller
   - Generate Windows installer with Inno Setup

3. Find the installer in `installer_output/` folder

### Release Process
- Update version in `resources/version.txt` and `inno-setup.iss`
- Run `build.bat` to create new installer
- Create a new GitHub release and upload the installer
- Tag the release with the version number (e.g., `v2.1.6`)

## 📋 License

This software is proprietary and provided "AS IS" without warranty. See the End-User License Agreement (EULA) included with the installer for full terms.

**Disclaimer**: Use at your own risk. The authors are not liable for any damages or issues caused by this software.

## 🤝 Contributing

While the source code is maintained privately, we welcome feedback and suggestions:

- **Bug Reports**: Open issues on GitHub
- **Feature Requests**: Use GitHub Discussions
- **Community Support**: Join our [Discord](https://discord.gg/4HqhKXZ8)

## 📝 Changelog

See the [Releases](https://github.com/NativeCodeX/NativeOptimizer/releases) page for version history and changelogs.

### Recent Updates
- **v2.1.6**: Latest stable release with enhanced AI features and performance improvements
- **v1.2.0**: Previous major release with Inno Setup installer

## 🙏 Acknowledgments

- **CustomTkinter**: Modern GUI framework
- **PyInstaller**: Application packaging
- **Inno Setup**: Windows installer creation
- **Google Gemini**: AI integration
- **Open Source Community**: Various Python libraries

## 📞 Support

- **Discord Community**: [https://discord.gg/4HqhKXZ8](https://discord.gg/4HqhKXZ8)
- **GitHub Issues**: For bug reports and technical support
- **Documentation**: Built-in help and learning resources

---

**NativeOptimizer** - Optimize Your Windows Experience
