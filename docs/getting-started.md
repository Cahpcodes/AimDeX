# Getting Started with AimDeX

Welcome to AimDeX! This guide will help you get up and running quickly.

## Table of Contents

- [System Requirements](#system-requirements)
- [Installation](#installation)
- [First Launch](#first-launch)
- [Basic Configuration](#basic-configuration)
- [Next Steps](#next-steps)

---

## System Requirements

Before installing AimDeX, ensure your system meets the following requirements:

### Minimum Requirements

- **OS**: Windows 10 (64-bit) or later
- **RAM**: 4 GB
- **CPU**: Intel Core i3 or equivalent
- **GPU**: DirectX 11 compatible
- **Storage**: 100 MB free space

### Recommended Requirements

- **OS**: Windows 11 (64-bit)
- **RAM**: 8 GB or more
- **CPU**: Intel Core i5 or better
- **GPU**: Dedicated graphics card with DirectX 12 support
- **Storage**: 500 MB free space

---

## Installation

### Option 1: Download Pre-built Release (Recommended)

1. Visit the [Releases](https://github.com/Cahpcodes/AimDeX/releases) page
2. Download the latest `AimDeX.exe` from the Assets section
3. Save the file to a location of your choice
4. **Important**: Right-click the file and select "Run as Administrator" (recommended)
5. Allow Windows Defender/Firewall permissions if prompted

### Option 2: Build from Source

See the main [README](../README.md#building-from-source) for detailed build instructions.

---

## First Launch

When you first launch AimDeX:

1. **Welcome Screen**: You'll be greeted with a welcome screen explaining the basics
2. **Configuration Wizard**: Follow the setup wizard to configure your initial settings
3. **Model Selection**: Choose a detection model (start with the default for best compatibility)
4. **Hotkey Setup**: Configure your preferred activation hotkey

### Initial Setup Tips

- Start with default settings and adjust as needed
- Test in a safe environment before using elsewhere
- Review all settings in the Settings tab

---

## Basic Configuration

### Essential Settings

#### 1. Detection Settings

- **Model**: Choose from available detection models
- **Confidence Threshold**: Adjust detection sensitivity (default: 0.5)
- **Detection Area**: Configure the screen region to monitor

#### 2. Aim Settings

- **Smoothing**: Control movement smoothness (higher = smoother)
- **Speed**: Adjust aim assistance speed
- **FOV**: Set field of view for detection

#### 3. Hotkeys

- **Toggle**: Enable/disable aim assistance
- **Emergency Stop**: Immediately disable all functions
- **Settings**: Quick access to settings menu

### Recommended Starting Values

```
Confidence: 0.5
Smoothing: 3.0
Speed: 1.0
FOV: 100
```

---

## Next Steps

Once you've completed the basic setup:

1. **Test Your Configuration**: Use the built-in testing mode
2. **Fine-tune Settings**: Adjust based on your preferences
3. **Review Documentation**: Check out other guides:
   - [Configuration Guide](./configuration.md)
   - [Troubleshooting](./troubleshooting.md)
   - [API Reference](./api-reference.md)

4. **Join the Community**:
   - [Discord Server](https://discord.gg/aimdex)
   - [GitHub Discussions](https://github.com/Cahpcodes/AimDeX/discussions)

---

## Common Questions

### Q: Do I need to run as administrator?

**A**: Yes, it's recommended for full functionality, especially for input handling.

### Q: Why isn't it working?

**A**: Check:
- Antivirus/firewall settings
- Administrator privileges
- Correct hotkey configuration
- Compatible system requirements

See [Troubleshooting](./troubleshooting.md) for detailed help.

### Q: Is this safe to use?

**A**: AimDeX is open-source software. Review the code yourself or check community reviews. Use responsibly and in accordance with the terms of service of any software you use it with.

---

## Support

Need help? Check these resources:

- 📖 [Documentation](./)
- 💬 [Discord Community](https://discord.gg/aimdex)
- 🐛 [Report Issues](https://github.com/Cahpcodes/AimDeX/issues)
- 📧 [Contact Support](https://github.com/Cahpcodes/AimDeX/discussions)

---

**Next**: [Configuration Guide](./configuration.md) →
