# Riftline Reports Blog Site (CS106 CSS Assignment)

This project is a multi-page sci-fi blogging website built to satisfy the CS106 "CSS Blogging Website" assignment requirements.

## Folder Structure

```
WebDevelopment(2)/
  index.html
  blog.html
  about.html
  contact.html
  style.css
  quantum-defrag.svg
  time-machine-conspiracy.svg
  alien-faultline.svg
  secret-chronotech.svg
  mandela-echo.svg
  chrononaut-diary.svg
  paradox-market.svg
  lunar-relay.svg
  retrocausal-ai.svg
  clocktower-slip.svg
  README.md
```

All files are intentionally placed in the main folder (no subfolders).
This version uses only HTML and CSS (no JavaScript).

## Requirement Coverage

### Multi-page website
- `index.html` (homepage)
- `blog.html` (blog entries)
- `about.html` (about page)
- `contact.html` (contact form)

### Navigation menu
- Styled horizontal nav bar on all pages with links to:
  - Home
  - Blog
  - About
  - Contact

### At least five blog entries
- Implemented in `blog.html` with 10 posts.
- Each post includes:
  - Title
  - Author name
  - Date
  - Content
  - Image/media element

### CSS Selectors (4.1)
- Element selectors: `body`, `p`, `img`
- Class selectors: `.panel`, `.post-card`, `.nav-menu`
- ID selectors: `#hero`, `#contact-form`
- Grouping selectors: `h1, h2, h3`
- Attribute selectors: `input[type="email"]`, `[data-topic*="time"]`, `a[target="_blank"]`
- Combinator selectors: `.nav-menu > li > a`, `.post-card h2 + .post-meta`, `.contact-form > .form-field`

### Box model (4.2)
- Margin, padding, border, width and height are used across cards, sections, nav links, media frames, and form fields.

### Typography and colors (4.3)
- Custom fonts via Google Fonts (`Orbitron`, `Rajdhani`)
- Styled headings and paragraph spacing
- Dark Neon Crimson color palette
- Gradient backgrounds used

### Navigation bar styling (4.4)
- Horizontal layout via flex
- Styled links
- Hover and active visual effects

### Layout system (4.5)
- CSS Grid used for:
  - Homepage preview cards (`.preview-grid`)
  - Blog post layout (`.posts-grid`)
  - About cards (`.mission-grid`)

### Pseudo classes (4.6)
- `:hover`
- `:active`
- `:focus`
- `:nth-child`

### Responsive design (4.7)
- Media queries at `960px` and `700px`
- Grid and navigation adjust for smaller screens

### Form styling (4.8)
- Contact form includes:
  - Name field
  - Email field
  - Message text area
  - Submit button
- Styled inputs and focus states

### Extra polish
- Staggered reveal animation for blog cards
- Hover transitions on cards and info panels
- Neon ambient overlay and scanline texture
- Home page signal dashboard and topic chips

## How to Run

Open `index.html` in a browser and navigate using the menu.

