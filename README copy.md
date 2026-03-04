# Solvix

HTML website that will be converted to WordPress theme.

## Structure

```
solvix/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Styles
├── js/
│   └── script.js      # JavaScript
└── images/            # Images folder
```

## WordPress Conversion Notes

When converting to WordPress:
- `index.html` → `index.php`
- Header section → `header.php`
- Footer section → `footer.php`
- Navigation → `wp_nav_menu()`
- Static content → WordPress loop
- CSS → `style.css` with WordPress theme headers
- Create `functions.php` for theme functionality
