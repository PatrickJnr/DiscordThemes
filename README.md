# DiscordThemes

A collection of custom Discord themes inspired by Catppuccin color palettes.

## Available Themes

| Theme Name | Version | Description | Preview |
|------------|---------|-------------|---------|
| Purple Dreams | 2.1 | A cute pastel purple theme inspired by Catppuccin Mocha with soft status colors | [View](PurpleDreams/PurpleDreams.css) |

### Purple Dreams Features
- 🎨 Catppuccin Mocha color palette with purple accents
- 💜 Soft pastel status indicators (online, idle, DND, streaming, offline)
- ✨ Custom Quicksand font family
- 🌙 Dark mode optimized backgrounds
- 🎯 Enhanced Discord UI compatibility
- 📝 Improved message, mention, and spoiler styling
- 💬 Better code block and syntax highlighting support

## Installation Instructions

### For BetterDiscord
1. **Download the theme file**
   - Navigate to the theme folder (e.g., `PurpleDreams/`)
   - Download the `.css` file
2. **Locate your BetterDiscord themes folder**:
   - Windows: `%appdata%/BetterDiscord/themes/`
   - macOS: `~/Library/Application Support/BetterDiscord/themes/`
   - Linux: `~/.config/BetterDiscord/themes/`
3. **Install the theme**:
   - Copy the `.css` file to your BetterDiscord themes folder
   - Open Discord → User Settings → BetterDiscord → Themes
   - Enable the theme by toggling it on

### For Vencord
1. **Download the theme file**
   - Navigate to the theme folder and copy the `.css` file contents
2. **Install the theme**:
   - Open Discord → User Settings → Vencord → Themes
   - Click "Open Themes Folder" or use online themes
   - For local: Paste the `.css` file in the themes folder
   - For online: Click "Edit QuickCSS" and paste the theme code
3. **Enable the theme** in the Vencord themes list

### For Vesktop (Vencord Desktop)
- Follow the same steps as Vencord above
- Themes folder location: Same as Vencord

### Troubleshooting
- **No changes visible?** Restart Discord completely (Ctrl+R to reload)
- **Theme conflicts?** Make sure only one theme is enabled at a time
- **Updating a theme?** Delete the old file and add the new version
- **Colors look wrong?** Ensure you're using Discord's dark mode
- **Status colors not working?** Clear Discord cache and restart

## Customization

You can customize the theme by editing the CSS variables at the top of the file:

```css
/* Core Colors */
--highlight: #cba6f7;        /* Main accent color */
--background: #1e1e2e;       /* Primary background */
--text: #cdd6f4;             /* Main text color */

/* Custom Title */
--custom-title-text: "Purple Dreams - Mocha";
--show-custom-title: 1;      /* Set to 0 to hide */
```

## Credits

- **Author**: PatrickJr
- **Inspired by**: [Catppuccin](https://github.com/catppuccin/catppuccin)
- **Website**: [grimtech.co.uk](https://grimtech.co.uk)

## License

Feel free to modify and share these themes. Credit is appreciated but not required.


