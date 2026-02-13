# Game Homepage Implementation Plan

## Overview
Create a game homepage `index.html` based on the stitch/code.html template, with proper navigation to two games: snake.html and click.html.

## Current Files Analysis
1. **stitch/code.html** - Google Stitch generated homepage with modern design (Tailwind CSS, pink/purple theme)
2. **snake2.html** - Advanced snake game with special blocks (to be renamed to snake.html)
3. **game2.html** - Click challenge game (to be renamed to click.html)

## Tasks to Complete

### 1. Rename Game Files ✓
- Rename `snake2.html` to `snake.html`
- Rename `game2.html` to `click.html`

### 2. Create index.html from stitch/code.html
- Copy stitch/code.html to index.html
- Modify game cards to link to actual games:
  - Card 1 (Snake Game): Link to `snake.html`
  - Card 2 (Click Challenge): Link to `click.html`
- Update game descriptions to match actual games
- Ensure buttons have proper `onclick` or `href` attributes

### 3. Update Game Cards Content
- Snake Game Card:
  - Title: "贪吃蛇 - 特殊方塊版"
  - Description: Match actual snake game features
  - Category: "CLASSIC"
  - Icon: Keep current or update to match snake theme
  
- Click Challenge Card:
  - Title: "點擊方塊計分挑戰"
  - Description: Match actual click game features
  - Category: "SPEED RUN"
  - Icon: Keep current or update to match click theme

### 4. Add Navigation Features
- Ensure "Start Game" buttons navigate to respective games
- Consider adding "Back to Home" links in game pages
- Test navigation flow

### 5. File Organization
- Keep all HTML files in root directory
- Maintain stitch folder for reference
- Ensure all links use relative paths

## Design Considerations
- Maintain the visual style of stitch/code.html (pink/purple theme)
- Use Tailwind CSS from CDN as in original
- Keep responsive design
- Preserve animations and decorative elements

## Testing Checklist
- [ ] index.html loads correctly
- [ ] Snake game card links to snake.html
- [ ] Click game card links to click.html
- [ ] Games load and function properly
- [ ] Navigation back to homepage works (if implemented)
- [ ] Responsive design works on mobile/desktop