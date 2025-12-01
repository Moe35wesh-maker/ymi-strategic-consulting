# Strategic Planning & Business Development Portfolio

A professional portfolio website showcasing strategic planning methodology for cultural institutions, featuring an adapted canvas-based framework for organizational transformation.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create Repository
1. Go to [github.com/new](https://github.com/new)
2. Name it: `ymi-strategic-consulting` (or any name you prefer)
3. Set to **Public**
4. Click **Create repository**

### Step 2: Upload Files
1. Click **"uploading an existing file"** link
2. Drag and drop `index.html` into the upload area
3. Add commit message: "Initial portfolio site"
4. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to repository **Settings** (tab at top)
2. Scroll down to **Pages** in left sidebar
3. Under "Source", select **Deploy from a branch**
4. Under "Branch", select **main** and **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 4: Access Your Site
Your site will be live at:
```
https://YOUR-USERNAME.github.io/ymi-strategic-consulting/
```

## 📁 Files Included

```
├── index.html          # Main portfolio page (single-file, no dependencies)
└── README.md           # This file
```

## ✨ Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Interactive Canvas Toolkit**: Tab-based canvas viewer showing 5 strategic frameworks
- **Scroll Animations**: Smooth fade-in effects as you scroll
- **No Build Required**: Pure HTML/CSS/JS - just upload and deploy
- **Professional Aesthetic**: Navy + gold color scheme suitable for consulting

## 🎨 Customization

### Update Contact Information
Find and replace in `index.html`:
```html
<a href="mailto:contact@example.com" ...>
```
Replace with your actual email.

### Update Download Button
The download button currently has `href="#"`. To link to your actual toolkit:
1. Upload your `.docx` file to the repository
2. Update the button href to point to the file

### Change Colors
Edit CSS variables at the top of `<style>`:
```css
:root {
    --navy: #0F1A2A;
    --gold: #C9A962;
    /* ... etc */
}
```

## 📋 Canvas Toolkit Included

The interactive section showcases 5 strategic canvases:

1. **Operating Model Canvas** - Current → Future state mapping
2. **SWOT Analysis Canvas** - Internal/external factor assessment  
3. **Program Design Canvas** - Detailed program planning (4x)
4. **Strategic Initiative Canvas** - Go/No-Go decision framework
5. **Revenue Stream Canvas** - 60/40 contributed/earned model

## 🔗 Share With Clients

Once deployed, you can:
- Include the link in your proposal
- Share during meetings for a professional presentation
- Reference specific sections with anchor links:
  - `#about` - About section
  - `#methodology` - Three-phase approach
  - `#canvases` - Interactive canvas toolkit
  - `#deliverables` - Four deliverables
  - `#experience` - Relevant experience

## 📱 Mobile Responsive

The site is fully responsive:
- Navigation collapses on mobile
- Canvas grid adapts to single column
- Touch-friendly tab navigation

## ⚡ Performance

- No external JavaScript libraries (vanilla JS only)
- Single CSS file (no framework dependencies)
- Google Fonts loaded async
- Optimized SVG icons inline

---

**Methodology adapted from WezaCare Transition Roadmap © 2023**
