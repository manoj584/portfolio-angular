# 🧑‍💻 Bhaskar Manoj - Portfolio Website

A modern, responsive portfolio website built with Angular showcasing my skills, experience, and projects as a Software Engineer and Full Stack Developer.

## 🚀 Features

- **Responsive Design**: Works seamlessly across all devices

- **Modern UI/UX**: Clean, elegant, and professional layout with smooth animations

- **Interactive Navigation**: Smooth scrolling and active section highlighting

- **Contact Form**: Interactive form with demo functionality

- **Social Links**: Quick access to LinkedIn, GitHub, Email, and Phone

- **Skills Showcase**: Categorized display of technical skills and tools

- **Project Portfolio**: Detailed view of my featured projects

- **Certifications**: Display of professional certifications and achievements

- **Modern Angular Architecture**: Organized components for scalability and maintainability

## 🛠️ Technologies Used

- **Frontend**: Angular 19 (Generated with Angular CLI v19.2.15)

- **Styling**: CSS3, Bootstrap 5, Custom animations

- **Icons**: Font Awesome

- **Fonts**: Fonts (Inter)

- **Architecture**: Component-based Angular structure

## 📋 Sections

1. **Home Section**: Introduction with profile photo and social links

2. **About**: Educational background and skill set

3. **Experience**: Work experience and achievements

4. **Projects**: Featured projects with technologies used

5. **Certifications**: Professional certifications

6. **Contact**: Contact information and message form

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)

- Angular CLI (v19.2.15 or later)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd portfolio-website
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
ng serve
```

4. Open your browser and navigate to
```bash
👉 http://localhost:4200
```

### Building for Production

To create a production build:
```bash
ng build
```

The optimized build files will be generated in the dist/ directory.

## 📁 Project Structure

```
portfolio-website/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── navigation/
│   │   │   ├── home/
│   │   │   ├── about/
│   │   │   ├── experience/
│   │   │   ├── projects/
│   │   │   ├── certifications/
│   │   │   ├── contact/
│   │   │   └── footer/
│   │   ├── app.component.html
│   │   ├── app.component.ts     # Angular Entry point
│   │   └── app.module.ts        # Main Angular component
│   ├── assets/
│   │   └── MyImage.jpg
│   ├── environments/
│   └── index.html
├── angular.json
├── package.json
└── README.md
```

## 🎨 Customization

### Personal Information

Update your details in the following component files:

- **navigation.component.html**: Name in the navbar

- **home.component.html**: Introduction, title, and social links

- **about.component.html**: Education and skills

- **experience.component.html**: Work experience

- **projects.component.html**: Project details

- **certifications.component.html**: Certificates

- **contact.component.html**: Contact details

- **footer.component.html**: Footer text

### Styling

Modify src/styles.css to customize:

- Color theme

- Font styles

- Animations

- Layout spacing

### Profile Image

Replace src/assets/MyImage.jpg with your own profile photo.

## 📱 Responsive Design

The website is fully optimized for:
- Desktop (≥1200px)
- Tablet (768px–1199px)
- Mobile (≤767px)

## 🌟 Features in Detail

### Component Architecture

**Modular Design:** Each section is a separate Angular component

**Reusable Components:** Easy to maintain and update

**Clean Imports and Routing:** Well-structured navigation and imports

**Scalable Structure:** Easy to extend and maintain as the project grows

### Smooth Scrolling Navigation

- Fixed navigation bar with backdrop blur

- Active section highlighting

- Smooth scrolling behavior

- Responsive collapsible menu for mobile view

### Interactive Elements

- Hover effects on cards and buttons

- Typing animation for intro titles

- Fade-in and bounce animations for sections

- Smooth transitions for interactive actions

### Contact Form

- Styled input fields with modern design effects

- Demo form submission with alert message

- Fully responsive and accessible layout

### Skills Display

- Organized by categories (Languages, Frameworks, Tools)

- Clean layout with color-coded badges

- Hover effects for interactivity

## 🔧 Useful Angular CLI Commands

- ng serve – Run the development server

- ng build – Build the app for production

- ng generate component <name> – Generate new components

- ng test – Run unit tests

- ng e2e – Run end-to-end tests

For more details, visit the Angular CLI Documentation.

## 📄 License

This project is open-source and available under the MIT License.

## 🤝 Contact

- **Email:** manojbhaskar01234@gmail.com

- **LinkedIn:** Bhaskar Manoj

- **GitHub:** Manoj584

- **Phone:** +91 8317557678

## 🙏 Acknowledgments

- Bootstrap for responsive design

- Font Awesome for icons

- Google Fonts for typography

- Angular CLI for project setup and tooling

**Note**:
This portfolio website is a demo project. The contact form is for demonstration purposes only.
Please use the provided contact links to get in touch.
