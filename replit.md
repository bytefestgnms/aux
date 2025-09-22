# Art Gallery Website

## Overview

An interactive art gallery website featuring horizontal scrolling artwork display. Built as a modern single-page application with React and TypeScript, the site presents artwork in an immersive gallery experience where users scroll vertically to navigate paintings horizontally. The application combines sophisticated visual design with smooth animations and interactive hover effects to create an engaging art viewing experience.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React with TypeScript using Vite as the build tool
- **Routing**: Wouter for client-side routing with a simple single-page structure
- **UI Components**: Radix UI primitives with custom styling via Tailwind CSS
- **State Management**: React Query (@tanstack/react-query) for server state management
- **Styling**: Tailwind CSS with CSS custom properties for theming
- **Component Library**: shadcn/ui design system with "new-york" style variant

### Design System
- **Theme**: Dark mode primary approach inspired by premium art galleries (Saatchi Art, Artsy)
- **Typography**: Google Fonts integration with Playfair Display, Inter, Crimson Text, and Cormorant Garamond
- **Color Scheme**: Deep charcoal backgrounds with refined blue accents for interactive elements
- **Layout**: Consistent spacing using Tailwind units (4, 6, 8, 12, 16px increments)

### Gallery Features
- **Scroll-Driven Animation**: GSAP for smooth horizontal movement triggered by vertical scroll
- **Interactive Elements**: Hover effects with scaling and "sheen" animations on artwork
- **Responsive Design**: Mobile-first approach with desktop-optimized gallery experience
- **Image Assets**: Local artwork storage in attached_assets directory

### Backend Architecture
- **Server**: Express.js with TypeScript
- **Database**: PostgreSQL with Drizzle ORM for type-safe database operations
- **Schema**: User management system with username/password authentication
- **Storage Interface**: Abstracted storage layer with in-memory fallback for development
- **Session Management**: Express session handling with connect-pg-simple for PostgreSQL session storage

### Data Layer
- **ORM**: Drizzle with automatic schema generation and migrations
- **Type Safety**: Zod integration for runtime validation and TypeScript inference
- **Database Config**: Environment-based configuration with DATABASE_URL support

### Development Setup
- **Build System**: Vite with React plugin and runtime error overlay
- **Path Aliases**: Configured for clean imports (@/, @shared/, @assets/)
- **Development Server**: Hot reload with middleware integration
- **TypeScript**: Strict mode configuration with ESNext modules

## External Dependencies

### Core Framework Dependencies
- **React Ecosystem**: React 18 with React DOM, React Hook Form, and React Query
- **Build Tools**: Vite with TypeScript support and development plugins
- **Routing**: Wouter for lightweight client-side routing

### UI and Design
- **Component Library**: Radix UI primitives for accessible components
- **Styling**: Tailwind CSS with PostCSS and Autoprefixer
- **Animation**: GSAP for smooth scroll-driven animations
- **Carousel**: Embla Carousel for potential slideshow functionality
- **Icons**: Lucide React for consistent iconography

### Backend Services
- **Database**: PostgreSQL via @neondatabase/serverless for cloud database connectivity
- **ORM**: Drizzle ORM with Drizzle Kit for migrations and schema management
- **Validation**: Zod for runtime type checking and schema validation
- **Utilities**: date-fns for date manipulation, clsx for conditional styling

### Development Tools
- **Replit Integration**: Custom plugins for development environment integration
- **Error Handling**: Runtime error modal for development debugging
- **TypeScript**: Full type safety across client and server code