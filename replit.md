# 4x4 Norwegian Running Timer

## Overview

This is a web-based interval training timer specifically designed for the 4x4 Norwegian running protocol. The application provides a visual and interactive timer that guides users through different training phases including warmup, high-intensity intervals, rest periods, and cooldown. The timer uses color-coded backgrounds and audio cues to help runners maintain proper pacing during their workout sessions.

## User Preferences

Preferred communication style: Simple, everyday language.
Device optimization: Pixel phone responsive design
Sound preferences: Longer audio cues for better workout feedback
QA features: Timeline navigation for testing different workout stages

## System Architecture

### Frontend Architecture
- **Single-page application**: Built with vanilla HTML, CSS, and JavaScript for simplicity and fast loading
- **Responsive design**: Uses CSS flexbox for mobile-friendly layouts that work across devices
- **Visual feedback system**: Color-coded backgrounds that change based on workout phase (green for warmup, red for high-intensity, blue for rest, gray for cooldown/ready)
- **Component-based styling**: CSS classes organized by workout stages for easy maintenance and customization

### User Interface Design
- **Minimalist approach**: Clean, distraction-free interface focused on essential timer information
- **High contrast**: White text on colored backgrounds for excellent readability during exercise
- **Typography**: System fonts for fast rendering and consistent appearance across platforms
- **Mobile-first**: Responsive design optimized for Pixel phone and smartphone usage during outdoor running
- **Prominent branding**: Clear app title header "4x4 Norwegian Running Protocol" for easy identification
- **QA navigation**: Timeline controls for testing different workout stages and time manipulation

### State Management
- **Client-side only**: All timer logic and state management handled in the browser
- **No external dependencies**: Self-contained application without frameworks or libraries
- **Session-based**: Timer state exists only during the active session

## External Dependencies

### Core Technologies
- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with transitions, flexbox, and responsive design
- **Vanilla JavaScript**: Timer logic, DOM manipulation, and user interactions

### Browser APIs
- **Web Audio API**: For workout phase transition sounds and audio cues
- **Local Storage API**: Potential for saving user preferences and workout history
- **Vibration API**: Possible haptic feedback for mobile devices during phase transitions

### No External Services
- **Offline-capable**: Designed to work without internet connection
- **No server requirements**: Pure client-side application
- **No third-party CDNs**: All resources served locally for reliability during outdoor workouts