# Night Sky Experiences

A modern, animated web experience featuring a beautiful night sky theme and interactive card-based content.

## 🌟 Features

- Stunning night sky background with blend effects
- Smooth scroll-based animations using GSAP
- Responsive card-based layout
- Modern UI with engaging transitions
- Optimized performance

## 🛠️ Technologies Used

- [Astro](https://astro.build/) - Static Site Generator
- [GSAP](https://greensock.com/gsap/) - Animation Library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [ScrollTrigger](https://greensock.com/scrolltrigger/) - GSAP Plugin for scroll-based animations

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/nightsky.git
cd nightsky
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Start the development server:

```bash
npm run dev
# or
yarn dev
```

4. Open your browser and navigate to `http://localhost:3000`

## 📁 Project Structure

```
nightsky/
├── src/
│   ├── components/
│   │   ├── CardList.astro
│   │   ├── Experiences.astro
│   │   └── Heading.astro
│   ├── images/
│   │   └── nightsky.svg
│   └── pages/
│       └── index.astro
├── public/
└── package.json
```

## 🎨 Customization

### Animations

The project uses GSAP for smooth animations. You can modify the animation parameters in the `Experiences.astro` component:

- Adjust the stagger timing
- Modify the animation duration
- Change the easing functions

### Styling

The project uses Tailwind CSS for styling. You can customize the theme by modifying the Tailwind configuration.

## 📱 Responsive Design

The website is fully responsive and works on:

- Desktop
- Tablet
- Mobile devices

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- GSAP for the amazing animation library
- Tailwind CSS for the utility-first CSS framework
- Astro for the static site generator
