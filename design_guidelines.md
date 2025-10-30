# TopJersey - Design Guidelines

## Design Approach

**Selected Approach:** Reference-based, inspired by premium sports e-commerce sites (Nike, Adidas, Fanatics)

**Core Principles:**
- Bold, dynamic sports aesthetic with energetic layouts
- Product-first design showcasing UEFA Champions League jerseys prominently
- Clean, modern e-commerce patterns optimized for product discovery
- Italian language throughout

## Typography

**Font Stack:**
- Primary: 'Inter' or 'DM Sans' (Google Fonts) - clean, modern sans-serif for UI elements
- Headings: 'Montserrat' or 'Poppins' (Google Fonts) - bold, impactful for titles and CTAs
- Body: 16px base, headings scale from 24px (h3) to 48px (h1)
- Weights: 400 (regular), 600 (semibold), 700 (bold), 800 (extra-bold for hero)

## Layout System

**Spacing:** Tailwind units of 4, 6, 8, 12, 16, 20 for consistent rhythm
- Sections: py-16 to py-24 (desktop), py-12 (mobile)
- Component spacing: gap-6 to gap-8 for grids
- Container: max-w-7xl with px-4 to px-8

**Grid Patterns:**
- Product catalog: 4-column grid (lg), 3-column (md), 2-column (sm), 1-column (mobile)
- Featured products: 3-column grid for highlights
- Reviews: 2-3 column grid with rating cards

## Page-Specific Designs

### Homepage
**Hero Section:**
- Full-width hero with large background image showing Champions League atmosphere (stadium, trophy, jerseys)
- Height: 85vh with centered content
- Overlay: Dark gradient (bottom to top) for text readability
- Content: Bold heading "Le Maglie Ufficiali UCL 2024" + subheading + primary CTA button with blur background
- CTA: "Esplora il Catalogo" button prominently placed

**Secondary Sections:**
- Featured jerseys showcase: 3-column grid with product cards
- UCL branding strip: Logo badges of top clubs available
- Value propositions: 3-column feature grid (Autenticità Garantita, Spedizione Veloce, Prezzi Competitivi) with icons
- Newsletter signup section with centered layout

### Catalogo (Product Page)
**Layout:**
- Left sidebar: Team filter list (clickable badges with club logos/names)
- Main area: 4-column responsive product grid
- Each product card: Large jersey image (hover zoom effect), team name, price (€), size selector dropdown (XS-XL), "Aggiungi al Carrello" button
- Product images: High-quality jersey photos on white/transparent background
- Price display: Bold, prominent €XX.XX formatting

### Carrello (Checkout)
**Table Layout:**
- Full-width responsive table with columns: Immagine Prodotto, Nome Maglia, Taglia, Quantità, Prezzo Unitario, Totale
- Summary section: Right-aligned box with Subtotale, IVA (22%), Totale finale
- Bottom CTA: Large "Completa Ordine (Simulato)" button
- Empty state: Centered message with icon when cart is empty

### Contatti
**Two-column split:**
- Left: Contact form (Nome, Email, Messaggio) with validation states
- Right: Contact information card (Email, Telefono, Orari di supporto) + embedded map placeholder
- Full-width on mobile with form first

### Informazioni
**Content-focused layout:**
- Hero section: Smaller height (40vh) with "Chi Siamo" heading
- Content sections: max-w-4xl centered, well-spaced paragraphs
- Sections: Storia TopJersey, Politiche di Reso, Informazioni Spedizione
- Trust badges: Row of icons showing authenticity guarantees

### Recensioni
**Card-based grid:**
- 3-column grid of review cards (2-col tablet, 1-col mobile)
- Each card: Star rating (5-star display), customer name, review text, date
- Overall rating summary at top: Large star display + average rating number
- Filter by rating (5★, 4★, etc.)

## Component Library

**Navigation:**
- Sticky header with TopJersey logo (left), nav links (center: Home, Catalogo, Recensioni, Informazioni, Contatti), cart icon with badge (right)
- Mobile: Hamburger menu with full-screen overlay

**Buttons:**
- Primary: Bold, rounded (rounded-lg), high contrast with blur background when on images
- Secondary: Outlined variant
- Sizes: py-3 px-6 (regular), py-4 px-8 (large hero CTAs)

**Product Cards:**
- White background with subtle shadow (hover: enhanced shadow)
- Image area: 4:5 aspect ratio
- Padding: p-4 to p-6
- CTA always visible (not hover-only)

**Footer:**
- Dark background with multi-column layout
- Columns: Logo + tagline, Links rapidi, Contatti, Social media icons
- Copyright row at bottom
- Newsletter signup integrated

**Icons:**
- Use Heroicons via CDN for UI elements
- Star icons for ratings
- Shopping cart, user, menu icons

## Images

**Required Images:**
1. **Hero Homepage:** Dynamic Champions League stadium/trophy scene with jerseys (wide landscape, 1920x1080 minimum)
2. **Product Catalog:** Individual jersey photos for each team - front view on white/transparent background (square format, 800x800)
3. **Team Logos:** Small club badge icons for filters and product cards
4. **Informazioni Page Hero:** Smaller atmospheric football image
5. **Contact Page:** Map placeholder or office/warehouse photo

**Image Treatment:**
- Hero images: Slight darkening overlay for text contrast
- Product images: Clean, professional with consistent lighting
- Maintain UEFA Champions League branding where appropriate

## Accessibility & Interactions

- Form inputs: Clear labels, visible focus states, validation feedback
- Buttons: Sufficient contrast, clear hover states (subtle scale or brightness)
- Cart badge: Animated number update when items added
- Product size selector: Clear visual feedback for selection
- Smooth scroll between sections
- Keyboard navigation support throughout

## Design Consistency

- Maintain consistent card styles across all pages
- Use same spacing rhythm (4, 6, 8, 12, 16, 20) throughout
- Keep typography hierarchy uniform
- Apply consistent hover effects (subtle shadow/scale)
- Ensure mobile responsiveness with touch-friendly targets (minimum 44px)