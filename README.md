# <h1 align="center"> Obsidian Theme: Elegance Enhanced </h1>

<p align="center">
  <img src="https://img.shields.io/github/v/release/Victologo/elegance-theme?style=for-the-badge&logo=obsidian&color=7c3aed" alt="Version">
  <img src="https://img.shields.io/github/downloads/Victologo/elegance-theme/total?style=for-the-badge&logo=github&color=22c55e" alt="Downloads">
  <img src="https://img.shields.io/github/stars/Victologo/elegance-theme?style=for-the-badge&logo=github&color=fbbf24" alt="Stars">
  <img src="https://img.shields.io/github/license/Victologo/elegance-theme?style=for-the-badge&color=3b82f6" alt="License">
</p>
 
![Miniatura - Elegance Enhanced](https://user-images.githubusercontent.com/118286581/221659569-c28fa6d4-c74e-4bfb-86d0-5d168bd954e6.jpg)

<p align="center">
  <a href="#-whats-new">What's New</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-features">Features</a> •
  <a href="#-style-settings">Style Settings</a> •
  <a href="#-credits">Credits</a>
</p>

---

## ✨ What's New in v2.0

### Enhanced Edition - Major Update

This enhanced version builds upon the original Elegance theme with significant improvements:

#### 🎛️ **Style Settings Compatible** ✅
- **20+ customizable options** via Style Settings plugin
- Control font sizes, colors, spacing without editing CSS
- Real-time visual adjustments from the UI

#### 📎 **Improved Embedded Notes** ✅
- **Configurable height** (0-1500px or unlimited)
- Custom scrollbars matching the theme
- Smooth scroll option
- Auto-height mode available

#### 🖱️ **Native Zoom Support** ✅
- `Ctrl + Scroll` works perfectly out of the box
- `Ctrl + +/-` keyboard shortcuts
- No additional setup required

#### 🎴 **Integrated Snippets** ✅
Built directly into the theme:
- **Cards** for Dataview (books, games, movies)
- **Quiet Outline** custom styling
- **MathJax** visual improvements
- **Kanban** text optimization

#### ⚡ **Performance Optimizations** ✅
- Enhanced font rendering
- Consistent scrollbars everywhere
- Respects reduced motion preferences
- Better accessibility support

---

## Screenshots

### Dark Mode
![image](https://user-images.githubusercontent.com/118286581/222965141-035ec2ef-6042-4cb4-b3fc-6dbb1a5e3126.png)

### Light Mode
![image](https://user-images.githubusercontent.com/118286581/222965154-e8f2fa20-6ea6-4f63-8997-e2cd1d74fdc9.png)

### Style Settings Panel (New!)
Configure everything visually - no CSS editing needed.

---

## 📥 Installation

### Method 1: From Obsidian Community Themes (Recommended)
1. Open **Settings** in Obsidian
2. Go to **Appearance** → **Themes** → **Manage**
3. Search for **"Elegance Enhanced"**
4. Click **Install** and then **Use**

### Method 2: Manual Installation
1. Download the [latest release](https://github.com/Victologo/elegance-theme/releases)
2. Extract to `.obsidian/themes/elegance-enhanced/`
3. Restart Obsidian
4. Enable in **Settings** → **Appearance** → **Themes**

### 🎨 Unlock Full Customization
Install **[Style Settings](https://github.com/mgmeyers/obsidian-style-settings)** plugin:
1. **Settings** → **Community Plugins** → **Browse**
2. Search **"Style Settings"**
3. Install and enable
4. Access options: **Settings** → **Style Settings** → **🎨 Elegance Theme**

---

## ✨ Features

### 🎨 Original Features

#### 🌈 Rainbow Headers
Beautiful gradient-style headers for visual hierarchy.

#### 🔍 Zoomable Images
Click and hold any image to zoom in.

<img src="https://user-images.githubusercontent.com/118286581/222966043-4c8efbfc-4c51-495a-a634-c344426b967b.png" width="500">

#### ⬅️➡️ Image Alignment
Position images easily:
```markdown
![[image.png|left|200]]    # Left aligned
![[image.png|right|200]]   # Right aligned
![[image.png|center|200]]  # Center (default)
```

<img src="https://user-images.githubusercontent.com/118286581/222966842-00c7c535-d9e7-4513-8f24-535f0627b7d4.png" width="550">

#### 💊 Pill Tags
Special styling for workflow tags:

<img src="https://user-images.githubusercontent.com/118286581/222966307-c0565773-6239-4ce6-a7fa-32245c37f2d3.png" width="350">

- `#ToDo` - Yellow pill
- `#InProgress` - Blue pill
- `#Completed` - Green pill

#### 📝 Active Line Highlighting
Visual guide for the current editing line.

<img src="https://user-images.githubusercontent.com/118286581/223382556-3445c0f6-1183-4232-8211-21e828baf51b.gif" width="650">

#### 🎬 Smooth Note Transitions
Elegant animations when switching notes.

<img src="https://user-images.githubusercontent.com/118286581/230440478-cd300cb3-f2d5-4c14-8a10-9c5df7bca998.gif" width="600">

#### 📊 Resizable Tables
Drag the bottom-right corner to resize.

<img src="https://user-images.githubusercontent.com/118286581/230439854-04717c35-23d0-4199-937c-06a32cc0f728.gif" width="450">

#### 🖼️ Image Captions
Special callout for image descriptions:
```markdown
> [!imagen]- Your caption here
> ![](image.png)
```

---

### ✨ New Enhanced Features

#### 🎛️ Style Settings Integration

Access all these settings visually in **Settings → Style Settings → Elegance Theme**:

**📝 Typography**
- Font size base (12-24px)
- Code font size (10-20px)
- Line height (1.2-2.5)
- Headers H1-H6 (individual control)

**📎 Embedded Notes**
- Max height (0-1500px, 0 = unlimited)
- Border radius (0-20px)
- Internal padding (0-40px)
- Shadow on hover (toggle)
- Smooth scroll (toggle)

**⚙️ Interface**
- Sidebar font sizes
- Status bar font size
- Scrollbar width (4-16px)

**🎨 Colors** (if you want to add them)
- Accent colors
- Background colors
- Text colors

#### 📎 Improved Embedded Notes

Embedded notes (`![[note]]`) now have:
- ✅ Configurable maximum height
- ✅ Custom scrollbar matching theme
- ✅ Smooth scroll option
- ✅ Unlimited height mode
- ✅ Better padding and spacing

**Example:**
```markdown
![[My Long Note]]
```
Will display with scrollbar if content exceeds the configured height.

#### 🖱️ Native Zoom

Works out of the box:
- **`Ctrl + Scroll`** - Zoom in/out with mouse wheel
- **`Ctrl + +`** - Zoom in
- **`Ctrl + -`** - Zoom out
- **`Ctrl + 0`** - Reset zoom

No configuration needed - it's Obsidian's native feature!

---

## 🎴 Integrated Snippets

All these features are **built into the theme** - no separate snippets needed!

### 📚 Dataview Cards

Transform Dataview tables into beautiful cards.

<img src="https://user-images.githubusercontent.com/118286581/222966399-4bcfeb92-3f5f-4e7f-875d-e6ea82410323.png" width="450">

**Usage:**
```yaml
---
cssclass: cards
---
```

````markdown
```dataview
TABLE WITHOUT ID
  file.link as "Title",
  author as "Author",
  cover as "Cover"
FROM "Books"
```
````

**Card Types:**
- `cssclass: cards` - Standard cards (books, general)
- `cssclass: cards-games` - Compact cards for video games
- `cssclass: cards-movies` - Horizontal cards for movies/series

**Column Control:**
- `cards cards-cols-3` - 3 columns
- `cards cards-cols-5` - 5 columns

### ✅ Enhanced Checkboxes (Minimal Theme)

For a lighter theme, checkboxes are not included by default. Download from: [Minimal Theme Checkboxes](https://github.com/kepano/obsidian-minimal/releases/tag/5.1.8)

| Syntax  | Description |
| ------- | ----------- |
| `- [ ]` | to-do       |
| `- [x]` | done        |
| `- [-]` | canceled    |
| `- [>]` | forwarded   |
| `- [<]` | scheduling  |
| `- [?]` | question    |
| `- [!]` | important   |
| `- [*]` | star        |
| `- ["]` | quote       |
| `- [l]` | location    |
| `- [i]` | information |

<img src="https://user-images.githubusercontent.com/118286581/222965921-5fa014fd-5893-4438-94c2-41ec7d7ba6e7.png" width="330">

### 📐 MathJax Improvements

Better rendering for long arrows and lines in equations:
```latex
$$A \xrightarrow{\text{long text}} B$$
```

### 📊 Kanban Styling

Optimized text sizing and spacing for Kanban boards.

### 📋 Quiet Outline

Custom styling for the Quiet Outline plugin with theme colors.

---

## 🎨 Style Settings

### How to Use

1. **Install Style Settings** plugin
2. Go to **Settings → Style Settings**
3. Find **🎨 Elegance Theme**
4. Adjust options with visual sliders and toggles

### Available Options

#### Typography Section
- Base font size
- Code font size  
- Line height
- H1, H2, H3, H4, H5, H6 sizes

#### Embedded Notes Section
- Maximum height slider
- Border radius
- Internal padding
- Show shadow (toggle)
- Smooth scroll (toggle)

#### Interface Section
- Sidebar font sizes
- Status bar size
- Scrollbar width

### Without Style Settings

You can still use the theme! It works perfectly with default values. To customize:
1. Open `theme.css`
2. Find the `:root` section
3. Edit values like `--font-size-normal: 16px;`
4. Save and reload Obsidian (`Ctrl+R`)

---

## 🚀 Performance

### Optimizations
- ✅ Optimized font rendering (`antialiased`)
- ✅ Efficient CSS selectors
- ✅ Reduced reflows
- ✅ Respects `prefers-reduced-motion`
- ✅ Better accessibility (focus indicators)

### System Preferences
The theme respects:
- **Reduced motion** - Disables animations if system preference is set
- **High contrast** - Adapts to system settings

---

## 📱 Mobile Support

Current status: **Partial support**

The theme works on mobile but some features are optimized for desktop. Mobile-specific improvements are planned for future updates.

---

## 🐛 Troubleshooting

### Ctrl+Scroll doesn't work for zoom
- Make sure you're focused on the editor (click on your note first)
- Some plugins might interfere - try disabling them
- Works in Obsidian v0.16.0+

### Style Settings options don't appear
- Make sure Style Settings plugin is installed and enabled
- Restart Obsidian after installing the plugin
- Check that you're using the latest version of the theme

### Embedded notes are too tall/short
- Open **Settings → Style Settings → Elegance Theme → Embedded Notes**
- Adjust "Maximum height" slider
- Set to 0px for unlimited height

### Cards don't display
- Make sure **Dataview** plugin is installed
- Add `cssclass: cards` to your note's frontmatter
- Check your Dataview query syntax

---

## 📋 Changelog

### v2.0.0 - Enhanced Edition (2025)
- ✅ Added Style Settings compatibility
- ✅ Improved embedded notes with configurable height
- ✅ Integrated 4 popular snippets into theme
- ✅ Fixed native zoom support
- ✅ Performance optimizations
- ✅ Better accessibility
- ✅ Consistent scrollbars
- ✅ Respects motion preferences

### v1.0.0 - Original Release (2023)
- Initial release with core features

---

## 💡 Tips & Tricks

### Combining Features

**Example: Book Library with Cards**
```yaml
---
cssclass: cards cards-cols-4
---
```

````markdown
```dataview
TABLE WITHOUT ID
  file.link as "📖",
  author as "✍️",
  "![" + cover + "](" + cover + ")" as "",
  rating as "⭐"
FROM "Library"
SORT rating DESC
```
````

### Custom Variables

You can create your own custom styling:
```css
/* In a CSS snippet */
.my-custom-note {
    --font-size-normal: 18px;
    --embed-max-height: 800px;
}
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Report Issues
Found a bug? [Open an issue](https://github.com/Victologo/elegance-theme/issues)

Include:
- Obsidian version
- Theme version
- Steps to reproduce
- Screenshots if applicable

### Suggest Features
Have an idea? Open a feature request!

### Submit Pull Requests
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a PR with clear description

---

## 📄 License

MIT License - Copyright (c) 2023-2025 Víctor Alonso Arribas

See [LICENSE](LICENSE) file for details.

---

## 👏 Credits

### Original Theme
**Víctor Alonso Arribas** ([@Victologo](https://github.com/Victologo))
- Biology student at University of Alcalá de Henares (Spain)
- YouTube: [Victólogo](https://www.youtube.com/c/Victólogo) (Spanish Obsidian tutorials)
- Instagram: [@victologoyt](https://www.instagram.com/victologoyt/)

**David Catalá Merino**
- Theme co-creator
- Instagram: [@x.akira_71.x](https://www.instagram.com/x.akira_71.x/)

### Enhanced Version (v2.0)
- Style Settings integration
- Performance optimizations  
- Snippet integration
- Documentation improvements

### Inspired By
- **[Dracula for Obsidian](https://github.com/jarodise/Dracula-for-Obsidian.md)** - Base theme
- **[Bubble Space](https://github.com/Emrie-Candera/Bubble-Space-Theme)** - Structure and snippets
- **[Blue Topaz](https://github.com/whyt-byte/Blue-Topaz_Obsidian-css)** - Code and snippets
- **[Minimal](https://github.com/kepano/obsidian-minimal)** - Cards and checkboxes
- **Danny Hatcher theme** - Code inspiration
- **Bryan Jenks theme** - Code inspiration

### Special Thanks
- Jose (Snifer@L4b's)
- Obsidian community
- Style Settings plugin by [@mgmeyers](https://github.com/mgmeyers)
- All contributors and users!

---

## 💬 Support

### Get Help
- [GitHub Issues](https://github.com/Victologo/elegance-theme/issues)
- [Obsidian Forum](https://forum.obsidian.md)
- [Obsidian Discord](https://obsidian.md/community)

### Stay Updated
- ⭐ Star this repo to show support
- 👀 Watch for updates
- 📢 Share with the community

### Contact
- 📧 Email: kolrekole2@gmail.com
- 🎥 YouTube: [Victólogo](https://www.youtube.com/c/Victólogo)
- 📷 Instagram: [@victologoyt](https://www.instagram.com/victologoyt/)

---

<p align="center">
  <b>Enjoy the enhanced Elegance theme! 🎨✨</b>
</p>

<p align="center">
  Made with ❤️ for the Obsidian community
</p>
