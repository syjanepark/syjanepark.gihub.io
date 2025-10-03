# Jane Park - Portfolio

A clean, modern single-page portfolio website showcasing my projects and skills.

## 🌟 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark Mode Support**: Built-in dark/light theme toggle
- **Modern UI**: Clean, professional design with smooth animations
- **Project Showcase**: Featured projects with live demos and GitHub links
- **Contact Integration**: Direct links to GitHub and LinkedIn

## 🚀 Live Demo

Visit the live portfolio: [Your Portfolio URL]

## 📁 Project Structure

```
syjanepark.gihub.io/
├── index.html          # Main portfolio page
├── public/
│   └── IMG_1026.JPG   # Profile photo
└── README.md          # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with modern features
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript**: Interactive elements and animations
- **Google Fonts**: Plus Jakarta Sans typography

## 📱 Projects Featured

### 1. CodeCraft
A web application for collaborative coding and version control.
- **GitHub**: [View Code](https://github.com/syjanepark/codecraft)
- **Tech Stack**: React, Node.js, MongoDB

### 2. DataViz
Interactive data visualization tool for complex datasets.
- **GitHub**: [View Code](https://github.com/syjanepark/dataviz)
- **Tech Stack**: D3.js, Python, Flask

### 3. Badger GPT
AI chatbot using GPT-4o with streaming responses and customizable AI personas.
- **GitHub**: [View Code](https://github.com/syjanepark/badger-gpt)
- **Tech Stack**: React, OpenAI API, TypeScript

## 🎨 Design Features

- **Color Scheme**: Custom pink primary color (#f471b3) with dark/light theme support
- **Typography**: Plus Jakarta Sans font family for modern, clean text
- **Layout**: CSS Grid and Flexbox for responsive design
- **Animations**: Smooth hover effects and transitions
- **Accessibility**: Semantic HTML and proper contrast ratios

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic understanding of HTML/CSS (for customization)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/syjanepark/syjanepark.gihub.io.git
   ```

2. Navigate to the project directory:
   ```bash
   cd syjanepark.gihub.io
   ```

3. Open `index.html` in your web browser or serve it using any local server.

### Local Development
For local development, you can use any simple HTTP server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have it installed)
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎯 Customization

### Updating Projects
Edit the project sections in `index.html` to add or modify your projects:

```html
<div class="flex flex-col gap-4 rounded-xl bg-background-light dark:bg-subtle-dark/40 p-5 shadow-sm hover:shadow-lg transition-shadow duration-300">
    <div class="bg-center bg-no-repeat aspect-video bg-cover rounded-lg" style="background-image: url('YOUR_IMAGE_URL');"></div>
    <div class="flex flex-col gap-2">
        <p class="text-sm font-medium text-primary">Project Category</p>
        <h3 class="text-lg font-bold text-content-light dark:text-content-dark">Project Title</h3>
        <p class="text-sm text-subtle-light dark:text-subtle-dark">Project Description</p>
    </div>
    <a class="mt-auto flex w-fit cursor-pointer items-center justify-center overflow-hidden rounded-full h-9 px-4 bg-primary/10 text-primary dark:bg-primary/20 text-sm font-semibold transition-colors hover:bg-primary/20 dark:hover:bg-primary/30" href="YOUR_GITHUB_LINK" target="_blank" rel="noopener noreferrer">
        View Project
    </a>
</div>
```

### Updating Profile Information
- **Profile Photo**: Replace `public/IMG_1026.JPG` with your own photo
- **Bio**: Update the bio text in the About Me section
- **Skills**: Modify the skill tags in the About Me section
- **Social Links**: Update GitHub and LinkedIn URLs

### Color Customization
Modify the color scheme in the Tailwind config section:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                "primary": "#f471b3",        // Main brand color
                "background-light": "#f8f6f7", // Light theme background
                "background-dark": "#221019",  // Dark theme background
                // ... other colors
            }
        }
    }
}
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

## 📞 Contact

- **GitHub**: [@syjanepark](https://github.com/syjanepark)
- **LinkedIn**: [Jane Park](https://www.linkedin.com/in/janesypark122/)

## 🙏 Acknowledgments

- Design inspiration from modern portfolio templates
- Icons and images from various open source resources
- Tailwind CSS for the utility-first styling approach

---

⭐ Star this repository if you found it helpful!
