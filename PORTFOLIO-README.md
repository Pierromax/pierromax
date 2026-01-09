# Professional Portfolio Website

A modern, responsive portfolio website built with Tailwind CSS and Vite, designed to showcase skills and projects for internship applications.

## 🎨 Features

- **Modern Design**: Clean, professional design with gradient accents and smooth animations
- **Fully Responsive**: Looks great on desktop, tablet, and mobile devices
- **Fast Performance**: Built with Vite for lightning-fast development and optimized production builds
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **Smooth Scrolling**: Enhanced user experience with smooth navigation
- **Interactive Elements**: Hover effects, animations, and transitions throughout
- **Contact Form**: Ready-to-integrate contact form for easy communication

## 📋 Sections

1. **Home/Hero**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal introduction and career objectives
3. **Skills**: Organized display of technical skills and technologies
4. **Projects**: Showcase of portfolio projects with descriptions
5. **Contact**: Contact information and form for getting in touch

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Pierromax/Pierromax.git
cd Pierromax
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

## 🛠️ Build for Production

To create a production-ready build:

```bash
npm run build
```

The built files will be in the `dist` directory, ready to be deployed to any static hosting service.

## 📦 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## 🎨 Customization

### Update Personal Information

1. Open `index.html`
2. Replace "Your Name" with your actual name
3. Update the email, GitHub, and LinkedIn links with your information
4. Modify the skills, projects, and about sections to match your experience

### Customize Colors

The portfolio uses a blue and purple gradient theme. To change colors:

1. Open `src/css/style.css`
2. Update the `@theme` section with your preferred colors:
```css
@theme {
  --color-primary: #your-color;
  --color-secondary: #your-color;
}
```

### Add Your Projects

Edit the Projects section in `index.html` to add your own projects with:
- Project name
- Description
- Technologies used
- Links to demo and source code

## 🌐 Deployment

This portfolio can be deployed to various hosting platforms:

### GitHub Pages

1. Update `vite.config.js` to set the correct `base` path
2. Run `npm run build`
3. Deploy the `dist` folder to GitHub Pages

### Netlify

1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`

### Vercel

1. Import your GitHub repository to Vercel
2. Vercel will automatically detect Vite and configure the build

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS v4**: Utility-first CSS framework
- **JavaScript (ES6+)**: Modern JavaScript features
- **Vite**: Next-generation frontend tooling
- **PostCSS**: CSS transformations

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## ✨ Features to Add

Future enhancements you might consider:

- [ ] Dark mode toggle
- [ ] Blog section
- [ ] Project filtering
- [ ] Animation library integration (e.g., AOS, Framer Motion)
- [ ] Form backend integration (e.g., Formspree, EmailJS)
- [ ] SEO optimization
- [ ] Analytics integration

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📧 Contact

- Email: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)

---

Built with ❤️ for internship applications
