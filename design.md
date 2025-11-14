# Design Style Document

## Design Philosophy

### Color Palette
- **Primary**: Deep charcoal (#2C2C2C) and warm white (#FAFAFA)
- **Accent**: Soft sage green (#8FBC8F) for interactive elements
- **Supporting**: Muted terracotta (#D4A574) for highlights
- **Text**: High contrast dark gray (#1A1A1A) on light backgrounds

### Typography
- **Display Font**: "Playfair Display" - elegant serif for headings
- **Body Font**: "Inter" - clean sans-serif for readability
- **Accent Font**: "Space Mono" - monospace for technical elements
- **Hierarchy**: Large bold headings, medium subheadings, small body text

### Visual Language
- **Minimalist Approach**: Clean layouts with purposeful white space
- **Organic Shapes**: Subtle rounded corners and flowing elements
- **Depth**: Soft shadows and layering for visual hierarchy
- **Consistency**: Unified spacing system (8px grid)

## Visual Effects

### Used Libraries
- **Anime.js**: Smooth micro-interactions and element animations
- **Splitting.js**: Advanced text effects and character animations
- **ECharts.js**: Data visualization with consistent color schemes
- **p5.js**: Creative coding for background effects
- **Splide.js**: Smooth carousel and slider functionality
- **Pixi.js**: Hardware-accelerated visual effects
- **Matter.js**: Physics-based interactions

### Effect Implementation

#### Header Effects
- Gradient text animation with color cycling
- Subtle parallax on scroll
- Smooth menu transitions with elastic easing

#### Background Effects
- Animated noise texture for depth
- Floating geometric shapes with slow movement
- Aurora gradient flow for hero sections

#### Text Effects
- Character-by-character reveal animations
- Gradient color transitions on hover
- Split-line highlighting for emphasis

#### Interactive Elements
- 3D tilt effects on cards
- Smooth scale and shadow transitions
- Ripple effects on button clicks
- Morphing icons on state changes

### Animation Principles
- **Easing**: Custom cubic-bezier curves for natural motion
- **Duration**: Fast micro-interactions (150-300ms), slower reveals (500-800ms)
- **Stagger**: Sequential animations with 50-100ms delays
- **Performance**: GPU-accelerated transforms, will-change optimization

### Responsive Design
- **Mobile-First**: Progressive enhancement approach
- **Breakpoints**: 
  - Mobile: 320px-768px
  - Tablet: 768px-1024px  
  - Desktop: 1024px+
- **Fluid Typography**: Clamp() for scalable text
- **Flexible Layouts**: CSS Grid and Flexbox combinations

### Accessibility Features
- **High Contrast**: 4.5:1 minimum ratio for all text
- **Focus States**: Clear keyboard navigation indicators
- **Motion Preferences**: Respect prefers-reduced-motion
- **Screen Readers**: Semantic HTML and ARIA labels

### Component Styling
- **Cards**: Soft shadows, rounded corners, hover lift effects
- **Buttons**: Gradient backgrounds, smooth state transitions
- **Forms**: Floating labels, validation states, smooth focus
- **Navigation**: Sticky header with blur backdrop
- **Modals**: Backdrop blur, scale animations, keyboard traps