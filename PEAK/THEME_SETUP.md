# PEAK Theme - Santa Madre Inspired Design

This theme has been customized to match the aesthetic of the Santa Madre website with a bold, modern design featuring dark backgrounds and vibrant yellow accents.

## Design Features

### Color Scheme
- **Background**: Black (#000000)
- **Foreground**: White (#FFFFFF)
- **Accent**: Bright Yellow (#EFFF04)
- **Accent Red**: Red (#FF002F) - used for cart count badges
- **Border**: Dark Gray (#333333)

### Typography
- **Primary Font**: Pitviper (custom font)
- **Extended Font**: Pitviper Extended (for headings)
- Clean, uppercase styling with generous letter-spacing
- Modern, athletic aesthetic

## Components Created

### 1. Hero Section (`sections/hero.liquid`)
Full-width hero banner with:
- Background image support
- Customizable heading and subheading
- Call-to-action button
- Adjustable height and overlay opacity

### 2. Product Grid Section (`sections/product-grid.liquid`)
Flexible product display with:
- Customizable heading and description
- Responsive grid layout (1-4 columns on desktop, 1-2 on mobile)
- Supports theme blocks for product cards

### 3. Product Card Block (`blocks/product-card.liquid`)
Individual product display with:
- Product image with hover effects
- Product title, description (optional), and price
- Customizable call-to-action button
- Smooth transitions and animations
- Border highlight on hover

### 4. Header Section (`sections/header.liquid`)
Minimalist navigation with:
- Brand logo/name with Pitviper Extended font
- Center-aligned navigation menu
- Account and cart icons
- Sticky positioning
- Yellow accent underline on hover

### 5. Footer Section (`sections/footer.liquid`)
Clean footer with:
- Brand information section
- Navigation links
- Copyright information
- Payment icons support

## Using the Theme

### Setting Up the Homepage

1. Go to Shopify Admin → Online Store → Themes
2. Click "Customize" on the PEAK theme
3. Add the following sections in order:
   - **Hero**: Add a background image and your brand message
   - **Product Grid**: Add 3 product cards for ASCENT, BASE GEL, and DESCENT

### Adding Products to Product Grid

1. In the theme editor, add a "Product Grid" section
2. Click "Add block" → "Product Card"
3. Select a product from your store
4. Customize display options:
   - Show/hide description
   - Show/hide price
   - Show/hide button
   - Customize button text
5. Repeat for all 3 products

### Creating Products

Create three products in Shopify Admin with:
- Upload the product images from `inspo/gels/` folder
- **ASCENT**: Hydration solution with cold care
- **BASE GEL**: 25g carb, 200mg sodium, unflavored
- **DESCENT**: Recovery solution with cherry flavor

## Font Files

The Pitviper font family has been added to the theme:
- `Pitviper.ttf` - Regular
- `Pitviper-Italic.ttf` - Italic
- `PitviperExtended.ttf` - Extended Regular
- `PitviperExtended-Italic.ttf` - Extended Italic

Fonts are automatically loaded via `snippets/css-variables.liquid`.

## Customization

### Colors
Colors are defined as CSS variables in `snippets/css-variables.liquid`:
```css
--color-background: #000000;
--color-foreground: #FFFFFF;
--color-accent: #EFFF04;
--color-accent-red: #FF002F;
--color-border: #333333;
```

### Typography
Fonts are set via CSS variables:
```css
--font-primary--family: 'Pitviper', ...;
--font-extended: 'Pitviper Extended', sans-serif;
```

### Button Styling
Buttons feature:
- Yellow background with black text
- Hover effect: white background with yellow border
- Uppercase text with letter-spacing
- Smooth transitions

## Product Images

Your product images are located in:
- `/inspo/gels/ASCENT.png`
- `/inspo/gels/BASE GEL.png`
- `/inspo/gels/DESCENT.png`

These should be uploaded to your Shopify products.

## Mobile Responsive

All sections are fully responsive with:
- Flexible grid layouts
- Optimized typography scaling
- Touch-friendly navigation
- Reduced spacing on mobile devices

## Next Steps

1. **Upload product images** to Shopify products
2. **Create your 3 products** (ASCENT, BASE GEL, DESCENT)
3. **Customize the homepage** using the theme editor
4. **Add navigation menu** in Shopify Admin → Navigation
5. **Test on mobile devices** to ensure responsive design works

## Support

All theme files have been validated with Shopify's Theme Check and passed successfully.
