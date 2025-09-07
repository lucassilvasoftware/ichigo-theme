# Ichigo Theme

A dark, minimal VS Code theme inspired by Japanese design philosophy. Ichigo combines understated elegance with purposeful contrast, creating a coding environment that promotes focus and reduces visual fatigue.

## Philosophy

Ichigo embodies the Japanese principle of **ichigo ichie** (一期一会) — the concept that each moment is unique and should be treasured. Applied to development, this means creating a workspace where every coding session becomes a mindful, focused experience.

The theme draws from traditional Japanese aesthetics:
- **Ma** (間) — purposeful use of negative space
- **Kanso** (簡素) — simplicity without sacrifice  
- **Wabi-sabi** (侘寂) — finding beauty in subtle imperfection

Each color was chosen to honor the balance between visibility and restraint, ensuring your code remains the protagonist while the interface gracefully recedes into the background.

## Design Principles

**Hierarchical Clarity**  
Syntax highlighting follows a clear information hierarchy, making code structure immediately apparent without overwhelming the reader.

**Sustainable Viewing**  
Carefully calibrated contrast ratios and color temperatures minimize eye strain during extended coding sessions.

**Contextual Awareness**  
Colors adapt semantically — errors demand attention while comments blend thoughtfully into the background.

## Installation

### Via Marketplace
```bash
code --install-extension ichigo-theme
```

### Manual Installation
```bash
git clone https://github.com/your-username/ichigo-theme.git
cp -r ichigo-theme ~/.vscode/extensions/
```

Activate through **Settings** → **Color Theme** → **Ichigo**

## Language Support

Optimized for modern development workflows:

```
JavaScript/TypeScript    Python    Go    Rust
React/Vue/Svelte        Java      C++   PHP  
HTML/CSS/SCSS           JSON      YAML  Markdown
```

## Customization

Override specific elements in your `settings.json`:

```json
{
  "workbench.colorCustomizations": {
    "[Ichigo]": {
      "editor.background": "#0d1117"
    }
  }
}
```

## Contributing

Ichigo grows through community insight. Submit issues for color adjustments or language-specific improvements.

**Development Setup**
```bash
git clone https://github.com/your-username/ichigo-theme.git
cd ichigo-theme
npm install
npm run dev
```

## License

MIT License — see [LICENSE](LICENSE) for details.

---

*Built with intention, refined through use.*