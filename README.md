# 🌌 S1B Gr0up GitHub Theme

A stunning, vibrant GitHub theme by **S1B Gr0up** featuring glassmorphism effects, animated backgrounds, and a cyberpunk aesthetic.

![S1B Gr0up Theme Preview](preview.png)

> 🔓 **By S1B Gr0up** - Offensive Security Specialists

## ✨ Features

- **🎨 Vibrant Cyberpunk Background**: Dynamic purple-to-magenta gradient with animated grid overlay
- **💎 Glassmorphism Effects**: Transparent containers with backdrop blur for a modern, premium look
- **🌊 Smooth Animations**: Floating elements, pulsing glows, and moving grid patterns
- **🎯 Enhanced Readability**: Carefully balanced transparency and contrast
- **⚡ Performance Optimized**: Smooth 60fps animations with GPU acceleration

## 🚀 Installation

### Using Stylus (Recommended)

1. Install [Stylus](https://github.com/openstyles/stylus) extension for your browser
2. Click on the Stylus icon and select "Manage"
3. Click "Write new style"
4. Copy the contents of `s1b-github-theme.css`
5. Paste into the code editor
6. Set "Applies to" → "URLs on the domain" → `github.com`
7. Save and enjoy!

### Using Stylish

1. Install Stylish extension
2. Create a new style for `github.com`
3. Paste the CSS code
4. Apply and reload GitHub

## 🎨 Customization

You can customize the theme by modifying these key variables in the CSS:

### Background Colors

```css
/* Main gradient (lines 130-137) */
background: linear-gradient(
  to bottom,
  #4a1a6b 0%,
  /* Deep purple */ #5d2b7f 20%,
  #7a3d9e 40%,
  #9b4fbd 60%,
  #bd62dc 80%,
  #e075ff 100% /* Bright magenta */
);
```

### Accent Colors

- **Cyan**: `rgba(0, 243, 255, ...)` - Used for borders and highlights
- **Magenta**: `rgba(255, 0, 255, ...)` - Used for secondary accents

### Animation Speed

```css
/* Grid animation (line 159) */
animation: cyber-grid-move 20s linear infinite; /* Change 20s to adjust speed */
```

## 📸 Screenshots

### Profile Page

Beautiful glassmorphism effect on profile cards with the vibrant background showing through.

### Repository View

Transparent file lists and code viewers with perfect readability.

### Code Editor

Syntax highlighting preserved with enhanced cyberpunk aesthetics.

## 🛠️ Technical Details

- **Transparency Levels**: Main containers use `rgba(34, 40, 48, 0.75)` for optimal balance
- **Blur Effect**: `backdrop-filter: blur(8-12px)` for glassmorphism
- **Animations**: CSS keyframes for smooth, performant effects
- **Z-index Management**: Proper layering to ensure background visibility

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Share your customizations

## 📝 License

This theme is released under the CC-BY-4.0 License. Feel free to use, modify, and share!

## 👤 Author

**ind4skylivey** (they/them)

- GitHub: [@ind4skylivey](https://github.com/ind4skylivey)
- Offensive Security Specialist — Red Team & Malware Analysis 🔓

## 🙏 Acknowledgments

Based on the original "GitHub Dark Wide Transparent" theme by doublehelix, enhanced with modern glassmorphism and cyberpunk aesthetics.

---

⭐ If you like this theme, please give it a star!

🎨 Made with love and neon lights 💜
