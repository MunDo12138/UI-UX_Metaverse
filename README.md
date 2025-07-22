# Metaverse Landing Page

A modern, responsive metaverse landing page built with Next.js 13, featuring smooth animations and an immersive user experience. This project showcases various virtual worlds including The Hogwarts, The Upside Down, Paradise Island, and more with a sleek, futuristic design.

## ✨ Features

- **Modern UI/UX Design**: Clean, futuristic interface with custom gradient backgrounds and smooth transitions
- **Fully Responsive**: Optimized for all device sizes from mobile to desktop
- **Smooth Animations**: Powered by Framer Motion for engaging user interactions and page transitions
- **Interactive Sections**: 8 main sections including Hero, About, Explore, Get Started, What's New, World, Insights, and Feedback
- **Virtual World Showcase**: Explore 5 different metaverse worlds with immersive visuals
- **Social Media Integration**: Connected social media links (Twitter, LinkedIn, Instagram, Facebook)
- **Custom Typography**: Eudoxus Sans font integration for modern aesthetics

## 🛠 Tech Stack

- **Framework**: Next.js 13.0.3
- **Styling**: Tailwind CSS 3.2.4 with custom color scheme and JIT mode
- **Animations**: Framer Motion 7.6.7 for smooth transitions and interactions
- **Language**: JavaScript/JSX (React 18.2.0)
- **Linting**: ESLint with Airbnb configuration for code quality
- **Build**: Static export ready for deployment

## 📁 Project Structure

```
metaverse-landing-page/
├── app/                    # Next.js 13 app directory
│   ├── layout.js          # Root layout with font configuration
│   ├── page.js            # Main page with all sections
│   └── head.js            # Head configuration
├── components/            # Reusable UI components
│   ├── CustomTexts.jsx    # Typography components (TypingText, TitleText)
│   ├── ExploreCard.jsx    # Interactive world exploration cards
│   ├── Footer.jsx         # Footer with social links
│   ├── InsightCard.jsx    # Blog-style insight cards
│   ├── Navbar.jsx         # Navigation component
│   ├── NewFeatures.jsx    # Feature highlight component
│   ├── StartSteps.jsx     # Step-by-step guide component
│   └── index.js           # Component exports
├── sections/              # Main page sections
│   ├── Hero.jsx           # Landing hero section
│   ├── About.jsx          # About metaverse section
│   ├── Explore.jsx        # Virtual worlds showcase
│   ├── GetStarted.jsx     # Getting started guide
│   ├── WhatsNew.jsx       # New features section
│   ├── World.jsx          # Interactive world map
│   ├── Insights.jsx       # Blog/insights section
│   ├── Feedback.jsx       # User testimonials
│   └── index.js           # Section exports
├── constants/             # Static data (worlds, features, insights, socials)
├── styles/                # Global CSS and style configurations
├── utils/                 # Animation utilities and motion variants
├── public/                # Static assets (27 images, icons, SVGs)
│   ├── planet-*.png       # World/planet images (9 total)
│   ├── people-*.png       # User avatars (3 total)
│   ├── *.svg              # Icons and graphics (8 total)
│   └── *.png              # Other images (cover, map, etc.)
└── config files           # Next.js, Tailwind, ESLint configurations
```

## Getting Started

### Prerequisites

- Node.js 16.x or later
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd metaverse-landing-page
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Builds the application for production
- `npm run start` - Starts the production server
- `npm run lint` - Runs ESLint for code quality checks

## Key Sections

1. **Hero Section**: Eye-catching introduction with animated text and cover image
2. **About Section**: Information about the metaverse concept and VR experiences
3. **Explore Section**: Showcase of different virtual worlds (Hogwarts, Upside Down, etc.)
4. **Get Started**: Guide for users to begin their metaverse journey
5. **What's New**: Latest features and updates
6. **World Section**: Interactive world map and exploration
7. **Insights**: Blog-style content about metaverse trends
8. **Feedback Section**: User testimonials and reviews

## Customization

The project uses Tailwind CSS for styling with custom color schemes and animations. Key customization points:

- **Colors**: Primary black (`#1A232E`) and secondary white (`#c7c7c7`)
- **Animations**: Custom motion variants in the `utils/motion.js` file
- **Content**: Update the `constants/index.js` file to modify worlds, features, and insights

## Deployment

The project is configured for static export and can be deployed to any static hosting service:

```bash
npm run build
```

This generates a static export in the `out` directory.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: This is a demo/portfolio project showcasing modern web development techniques for creating immersive landing pages.
