# Art Gallery Website Design Guidelines

## Design Approach
**Reference-Based Approach**: Drawing inspiration from premium art gallery websites like Saatchi Art and Artsy, focusing on sophisticated presentation that elevates the artwork while maintaining elegant simplicity.

## Core Design Elements

### Color Palette
**Dark Mode Primary** (recommended for art galleries):
- Background: 18 5% 8% (deep charcoal)
- Surface: 20 8% 12% (slightly lighter charcoal)
- Text Primary: 0 0% 95% (near white)
- Text Secondary: 0 0% 70% (light gray)
- Accent: 220 100% 60% (refined blue for interactive elements)

**Light Mode Alternative**:
- Background: 0 0% 98% (warm white)
- Surface: 0 0% 100% (pure white)
- Text Primary: 0 0% 15% (dark gray)
- Accent: 220 80% 45% (deeper blue)

### Typography
- **Primary Font**: Inter or similar modern sans-serif via Google Fonts
- **Headings**: 600-700 weight, generous letter spacing
- **Body Text**: 400-500 weight, optimized line height for readability
- **Captions**: 400 weight, smaller scale for artwork details

### Layout System
**Spacing Primitives**: Tailwind units of 4, 6, 8, 12, 16
- Consistent rhythm using these increments
- p-6 for standard component padding
- gap-8 for component spacing
- m-12 for section margins

### Component Library

**Navigation**:
- Minimal header with logo and essential links
- Transparent background with subtle backdrop blur
- Sticky positioning during scroll

**Gallery Container**:
- Full viewport height with hidden vertical scrollbar
- Horizontal painting track with smooth transform animations
- Momentum-based scroll with easing curves

**Painting Frames**:
- Consistent aspect ratios (4:3 or 3:4 depending on artwork)
- Subtle borders (1-2px) in muted accent color
- Generous whitespace around each piece
- Scale transform on hover (1.02-1.05x)
- Animated sheen overlay effect on hover

**Interactive Elements**:
- Smooth transitions (300-400ms duration)
- Subtle shadow effects for depth
- Click states with gentle scale animation

### Visual Treatment
- **Backgrounds**: Deep, neutral tones that don't compete with artwork
- **Shadows**: Soft, natural shadows for painting frames
- **Borders**: Minimal, refined stroke weights
- **Spacing**: Generous whitespace to let artwork breathe

### Animations
**Minimal and Purposeful**:
- Smooth horizontal scroll momentum with physics-based easing
- Gentle hover scale effects on paintings
- Subtle sheen animation overlay
- Page transitions with fade effects

### Images
**Hero Section**: No large hero image - focus immediately on the gallery
**Artwork Images**: High-resolution paintings with consistent framing and professional photography lighting. Each painting should be properly cropped with even margins and consistent lighting to maintain gallery cohesion.

### Key Principles
1. **Artwork First**: Every design decision serves to showcase the art
2. **Sophisticated Simplicity**: Refined aesthetics without visual noise
3. **Smooth Interactions**: Physics-based animations that feel natural
4. **Consistent Framing**: Professional presentation standards throughout
5. **Responsive Excellence**: Seamless experience across all devices

This design creates a premium digital gallery experience that respects both the artwork and the viewer's attention.