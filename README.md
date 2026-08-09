# Remimder â€” Your AI Life Coach ðŸ¤–

A beautiful, intelligent life coaching web app with a 3D robot companion that helps you navigate daily choices and life decisions.

## âœ¨ Features

- **3D Robot Companion** â€” A cute interactive robot that follows your mouse/touch movement
- **AI Life Coach** â€” Smart responses for daily choices, life decisions, mood tracking, and pros/cons analysis
- **Day/Night Mode** â€” Automatically switches based on time of day and ambient light sensor
- **Liquid Glass UI** â€” Beautiful glassmorphism design with animated gradient backgrounds
- **Scroll Animations** â€” Navigation hides when scrolling up, appears when scrolling down
- **Login/Sign Up** â€” Secure local authentication with user settings
- **Smart Recommendations** â€” Personalized suggestions for daily and life activities
- **Daily Insights** â€” Motivational quotes that change daily
- **Mobile Optimized** â€” Responsive design with safe area support for all devices
- **Ambient Light Sensor** â€” Uses device light sensor (when available) for automatic theme switching

## ðŸš€ Getting Started

1. Open `index.html` in your browser
2. Create an account or log in
3. Start chatting with your AI coach!

## ðŸ“± Mobile Support

- Responsive design works on all screen sizes
- Touch-optimized interactions
- Safe area insets for notched devices
- Ambient light sensor integration (Android Chrome)

## ðŸ›  Tech Stack

- **HTML5** â€” Semantic markup
- **CSS3** â€” Glassmorphism, animations, CSS variables for theming
- **JavaScript (ES6+)** â€” Vanilla JS, no frameworks
- **Three.js** â€” 3D robot rendering
- **Web APIs** â€” AmbientLightSensor, localStorage

## ðŸ“‚ Structure

```
remimder/
â”œâ”€â”€ index.html          # Main app
â”œâ”€â”€ css/
â”‚   â””â”€â”€ style.css       # All styles + themes
â”œâ”€â”€ js/
â”‚   â”œâ”€â”€ theme.js        # Day/night + light sensor
â”‚   â”œâ”€â”€ robot3d.js      # 3D robot with Three.js
â”‚   â”œâ”€â”€ auth.js         # Login/signup system
â”‚   â”œâ”€â”€ ai.js           # AI coach responses
â”‚   â”œâ”€â”€ scroll.js       # Scroll animations
â”‚   â””â”€â”€ app.js          # Main controller
â””â”€â”€ README.md
```

## ðŸŽ¨ Customization

### Themes
- Auto: switches based on time (7PM-6AM = night)
- Manual: toggle via the sun/moon button
- Light sensor: auto-adjusts based on ambient light

### AI Personality
Choose from 4 personalities in Settings:
- **Friendly** â€” Warm, supportive, emoji-filled
- **Professional** â€” Formal, analytical
- **Motivational** â€” High-energy, empowering
- **Chill** â€” Relaxed, no pressure

## ðŸ“„ License

MIT â€” use it however you want!# Reminder
