# 🛡️ Shopify Tactical Collection Pro Section

A high-performance, modular Shopify collection template designed with a "Tactical" aesthetic. It features advanced AJAX functionality, dynamic layouts, and interactive product elements.

## 🚀 Key Features

- **AJAX Grid Switcher:** Instantly switch between 1, 2, 3, 4 columns or List View without page reloads.
- **Sub-Collection Slider:** Auto-scrolling Swiper.js slider for sub-collection navigation using circular thumbnails.
- **Smart Color Swatches:** 
    - Real-time product image switching on swatch click.
    - Automatic color mapping for tactical shades (Army Green, Gunmetal, Desert Khaki, etc.).
- **Tactical UI:** 
    - Built-in tooltips for color labels.
    - Custom fonts (Quantico & Instrument Sans).
    - Neon accent color customization via Shopify Schema.
- **Performance Optimized:** 
    - Lazy-loaded images.
    - Vanilla JavaScript (No jQuery required).
    - Responsive design (Mobile-first approach).

## 🛠️ Tech Stack

- **Liquid:** Shopify Templating.
- **CSS3:** Custom Grid & Flexbox layouts.
- **JavaScript:** Fetch API for AJAX and Swiper.js for carousels.
- **Fonts:** Google Fonts Integration.

## 📂 Installation

1. **Create Section:**
   In your Shopify Admin, go to **Online Store > Themes > Edit Code**. Create a new section named `tactical-collection.liquid`.

2. **Paste Code:**
   Paste the provided Liquid, CSS, and JS code into the file.

3. **Asset Links:**
   Ensure Swiper.js is included in your `theme.liquid` or within the section:
   ```html
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
   <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
