# Digital-Agency-AURORA
A premium agency-style website showcasing advanced animations and seamless user interactions. This project demonstrates the implementation of modern web technologies and animation techniques.


## 🎯 Features

- Custom cursor with interactive animations
- Parallax floating cards effect
- Smooth scroll animations
- Interactive statistics with counters
- Advanced loading sequences
- Responsive design
- Interactive project cards
- Animated testimonials
- Contact form with dynamic interactions

## 🛠️ Technologies Used

- GSAP (GreenSock Animation Platform)
  - ScrollTrigger Plugin
  - ScrollToPlugin
  - Timeline animations
- HTML5
- CSS3
- Vanilla JavaScript

## ⚡️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/aurora-website.git
```

2. Navigate to the project directory:
```bash
cd Digital-Agency-AURORA
```

## 🔧 Usage

### Custom Cursor
The custom cursor implementation can be modified in the script section. Adjust the cursor size and animation parameters:

```javascript```
gsap.to(cursor, {
    scale: 2.4,
    background: '#4facfe',
    border: 'none',
    duration: 0.6
});
```

### Animation Timelines
Modify the loading sequence and animations in the GSAP timeline:

```javascript```
const tl = gsap.timeline();
tl.to('.loader', {
    // Animation parameters
});
```

### Scroll Triggers
Customize scroll-based animations using ScrollTrigger:

```javascript```
gsap.from('.feature-card', {
    scrollTrigger: {
        trigger: '.features-grid',
        start: 'top center',
        toggleActions: 'play none none reverse'
    }
});
```

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1200px and above)
- Tablet (768px to 1199px)
- Mobile (below 768px)

## ⚙️ Configuration

### Animation Settings
Adjust animation parameters in `script` tags:
- Timing
- Easing functions
- Trigger points
- Animation sequences

### Styling
Customize the appearance by modifying:
- Colors
- Typography
- Spacing
- Layout

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🙏 Acknowledgements

- [GSAP Documentation](https://greensock.com/docs/)
- [ScrollTrigger Plugin](https://greensock.com/scrolltrigger/)
- [Modern JavaScript Tutorial](https://javascript.info/)

## 📫 Contact

Narmesh Kumar Sah - LinkedIn: https://www.linkedin.com/in/narmeshkumarsah/

## 🚀 Future Improvements

- [ ] Add light/dark mode support
- [ ] Implement more interactive features
- [ ] Optimize animation performance
- [ ] Add more project examples
- [ ] Create documentation website