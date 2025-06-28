# 🚀 Resume Web View

A modern, responsive web-based resume/CV template that showcases your professional profile in an elegant and interactive way. Perfect for developers, designers, and professionals who want to stand out with a beautiful online presence.

![Resume Preview](https://github.com/user-attachments/assets/c4e47e85-a1b3-45b2-9a5e-809f2d4e97d8)

## ✨ Features

- **Modern Design**: Clean, professional layout with a sophisticated dark theme
- **Responsive Layout**: Perfectly adapts to all screen sizes and devices
- **Interactive Elements**: Animated skills progress bars and smooth hover effects
- **Easy Customization**: Simple to modify colors, content, and styling
- **Professional Sections**: Complete with contact info, about me, skills, work experience, and education
- **Social Media Integration**: Links to your professional social profiles
- **Font Awesome Icons**: Beautiful iconography throughout the design
- **Google Fonts**: Elegant Montserrat typography
- **Cross-browser Compatible**: Works seamlessly across all modern browsers

## 🛠️ Technologies Used

| Technology | Usage | Version |
|------------|-------|---------|
| **HTML5** | Structure and content | Latest |
| **CSS3/SCSS** | Styling and animations | Latest |
| **JavaScript** | Interactive animations | ES6+ |
| **Bootstrap** | Responsive framework | 4.5.2 |
| **jQuery** | DOM manipulation | 3.2.1 |
| **Font Awesome** | Icons | 5.15.1 |
| **Google Fonts** | Typography (Montserrat) | Latest |

## 🚀 Quick Start

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor (VS Code recommended)
- Optional: Live server extension for development

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/vestearth/Resume-web-view.git
   cd Resume-web-view
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser, or
   - Use a local server for better development experience:
   
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using VS Code Live Server extension
   Right-click on index.html → "Open with Live Server"
   ```

3. **View your resume**
   Navigate to `http://localhost:8000` (or the URL provided by your local server)

## 📖 Usage Guide

### Basic Customization

1. **Update Personal Information**
   - Open `index.html`
   - Replace the sample data with your own information:
     - Name and job title in the profile section
     - Contact information (phone, email, address)
     - Social media links
     - About me description

2. **Modify Skills Section**
   - Update programming skills in the "Programming Skills" section
   - Add or remove skill categories as needed
   - Modify the "Other Skills" list

3. **Update Work Experience & Education**
   - Replace with your own work history
   - Update education details
   - Adjust dates and descriptions

### Advanced Customization

#### Changing Colors and Theme

1. **Edit SCSS Variables** (in `css/_earth.scss`):
   ```scss
   $orange: #ffb300;        // Primary accent color
   $yellow: #fdd835;        // Secondary accent color
   $darkest-blue: #1F1D1D;  // Main background
   $darker-blue: #464646;   // Section backgrounds
   $white: #ffffff;         // Text color
   ```

2. **Compile SCSS** (if you have Sass installed):
   ```bash
   sass css/resume_cv.scss css/resume_cv.css
   ```

#### Adding New Sections

1. Follow the existing HTML structure pattern
2. Add corresponding styles in the SCSS files
3. Update any necessary JavaScript if interactions are needed

## 📁 Project Structure

```
Resume-web-view/
├── index.html              # Main HTML file with resume content
├── css/
│   ├── resume_cv.css       # Compiled CSS (don't edit directly)
│   ├── resume_cv.scss      # Main SCSS file (imports _earth.scss)
│   ├── _earth.scss         # Core styling and variables
│   └── resume_cv.css.map   # Source map for debugging
├── js/
│   └── script.js           # JavaScript for animations and interactions
└── README.md               # This file
```

### Key Files Explained

- **`index.html`**: Contains all the resume content and structure. This is where you'll update your personal information.
- **`css/_earth.scss`**: The main stylesheet with all custom styles, variables, and responsive design rules.
- **`css/resume_cv.scss`**: Simple import file that includes the main stylesheet.
- **`js/script.js`**: Handles the animated progress bars for skills and smooth animations.

## 🎨 Customization Guide

### Changing Personal Information

1. **Profile Section** (Lines 29-32 in index.html):
   ```html
   <h1 class="name">Your Name</h1>
   <h2 class="job">Your Job Title</h2>
   ```

2. **Contact Information** (Lines 38-50):
   ```html
   <div class="call"><a href="tel:+1234567890">Your Phone</a></div>
   <div class="email"><a href="mailto:your.email@example.com">Your Email</a></div>
   ```

3. **Social Links** (Lines 26-35 in the follow section):
   Update the href attributes with your social media profiles.

### Modifying Colors

The color scheme is controlled by SCSS variables in `css/_earth.scss`. Key colors:

- **Primary Orange** (`$orange: #ffb300`): Used for headings and accents
- **Hover Yellow** (`$yellow: #fdd835`): Used for hover effects
- **Dark Background** (`$darkest-blue: #1F1D1D`): Main resume background
- **Section Background** (`$darker-blue: #464646`): Individual section backgrounds

### Adding Skills with Progress Bars

To add animated progress bars for technical skills:

1. Add the HTML structure:
   ```html
   <li data-percent="85">
     <span>Your Skill</span>
     <div class="skills-bar"><div class="bar"></div></div>
   </li>
   ```

2. The `data-percent` attribute controls the animation width (0-100).

## 🤝 Contributing

We welcome contributions! Please follow these steps:

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes**
   - Follow the existing code style
   - Test your changes thoroughly
   - Update documentation if needed
4. **Commit your changes**
   ```bash
   git commit -m "Add: your feature description"
   ```
5. **Push to your branch**
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Create a Pull Request**

### Code Standards

- Use consistent indentation (2 spaces)
- Follow semantic HTML structure
- Use SCSS for styling (compile to CSS)
- Comment complex JavaScript functions
- Test across multiple browsers
- Ensure responsive design principles

### Reporting Issues

Found a bug or have a suggestion? Please create an issue with:
- Clear description of the problem or suggestion
- Steps to reproduce (for bugs)
- Screenshots if applicable
- Your browser and OS information

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

### Credits

- **Icons**: [Font Awesome](https://fontawesome.com/)
- **Fonts**: [Google Fonts - Montserrat](https://fonts.google.com/specimen/Montserrat)
- **Framework**: [Bootstrap](https://getbootstrap.com/)
- **Animation**: [jQuery](https://jquery.com/)

## 📞 Contact

**Project Owner**: Sichol Korjitmate  
**Email**: sichol.kor@gmail.com  
**Location**: Chiang Mai, Thailand  

**Social Media**:
- [LinkedIn](https://www.linkedin.com/in/sichol-korjitmate-9bb04618b/)
- [Facebook](https://www.facebook.com/vestearth/)
- [Instagram](https://www.instagram.com/earth_sk/)
- [Pinterest](https://www.pinterest.com/earth56/)

---

## 🌟 Show Your Support

If this project helped you create an awesome resume, please give it a ⭐️!

### Languages Used
- **SCSS:** 33.1%
- **CSS:** 30.8%
- **HTML:** 30.2%
- **JavaScript:** 5.9%
