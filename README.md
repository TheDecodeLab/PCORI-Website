# PCORI-Website

A responsive research website focused on improving stroke recovery in rural communities. This project presents findings and information about stroke recovery initiatives, featuring an interactive design optimized for all devices.

## 🌟 About the Project

This website showcases research focused on **Improving Stroke Outcomes in Rural Communities** through patient-centered outcomes research. The project aims to build capacity for patient-centered research by engaging rural stroke survivors and caregivers as equal partners.

### Key Features
- **Responsive Design**: Optimized for all screen sizes (mobile, tablet, desktop)
- **Interactive Elements**: Smooth scrolling, hover effects, and modern UI components
- **Audio Content**: Integrated audio overview of the project
- **Team Information**: Comprehensive team profiles and roles
- **Research Resources**: Training materials and recommended publications
- **Community Engagement**: Information about the Community Advisory Board (CAB)

## 🚀 Live Demo

The website is deployed on GitHub Pages and can be accessed at:
**https://thedecodelab.github.io/PCORI-Website/**

## 📋 Project Sections

### 1. **Hero Section**
- Main project title with typewriter effect
- Project overview and call-to-action
- Responsive background with overlay

### 2. **About Our Project**
- Detailed project description
- Research methodology and goals
- Visual representation of project phases

### 3. **Our Goals**
- Four key objectives presented in card format
- Equal partnership engagement
- Community empowerment
- Trust building
- Care strategy improvement

### 4. **Project Overview**
- Two-phase research process
- Timeline and milestones
- Visual project roadmap

### 5. **Audio Content**
- Project overview audio file
- Download functionality
- Accessible audio controls

### 6. **Team Information**
- Principal Investigators
- Co-Investigators and Staff
- Consultants
- Community Advisory Board (CAB) Members

### 7. **Training and Resources**
- Engagement training materials
- CITI Program courses
- Research fundamentals
- Recommended publications

### 8. **Contact Information**
- Lead institution details
- Project duration and support information

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Vanilla JavaScript**: Interactive functionality
- **Responsive Design**: Mobile-first approach
- **GitHub Pages**: Hosting and deployment

## 📱 Responsive Design Features

- **Mobile-First**: Optimized for mobile devices first
- **Breakpoint System**: 
  - Mobile: ≤480px
  - Tablet: 481px - 768px
  - Desktop: 769px+
- **Flexible Typography**: Font sizes scale with screen size
- **Touch-Friendly**: Optimized for touch interactions
- **Accessibility**: Proper contrast ratios and semantic markup

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Git (for version control)
- GitHub account (for deployment)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/TheDecodeLab/PCORI-Website.git
   cd PCORI-Website
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience

3. **Using a local server** (optional)
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Access the site**
   - Open your browser and go to `http://localhost:8000`

## 🌐 Deployment

### GitHub Pages Setup

1. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Pages**
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** (or **master**) branch and **/ (root)** folder
   - Click **Save**

2. **Automatic Deployment**
   - The site will automatically deploy when you push changes to the main branch
   - GitHub Actions workflow handles the deployment process

3. **Custom Domain** (optional)
   - In the Pages settings, you can add a custom domain
   - Update the `_config.yml` file with your domain

### Manual Deployment
```bash
# Commit your changes
git add .
git commit -m "Update website content"
git push origin main
```

## 📁 Project Structure

```
PCORI-Website/
├── index.html              # Main website file
├── README.md              # Project documentation
├── _config.yml            # GitHub Pages configuration
├── .github/
│   └── workflows/
│       └── deploy.yml     # GitHub Actions deployment workflow
├── audio/                 # Audio resources
│   └── luvvoice.com-20250808-ReLb6h.mp3
├── photos/                # Image assets
│   ├── About our project.png
│   └── PCORI project overviwe by phase.jpg
└── LICENSE                # Project license
```

## 🎨 Design Features

### Visual Elements
- **Gradient Backgrounds**: Modern gradient overlays
- **Card Components**: Elevated cards with hover effects
- **Typography**: Inter font family with gradient text effects
- **Animations**: Smooth transitions and hover effects
- **Icons**: SVG icons for better scalability

### Interactive Components
- **Smooth Scrolling**: Navigation between sections
- **Hover Effects**: Button and card interactions
- **Responsive Images**: Optimized for all screen sizes
- **Audio Player**: Integrated audio content

## 🔧 Customization

### Colors
The website uses a blue color scheme defined in Tailwind CSS:
- Primary: `#1e3a8a` (Blue-800)
- Secondary: `#1e40af` (Blue-700)
- Accent: `#1d4ed8` (Blue-600)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700
- **Responsive Sizing**: Scales from 1rem to 6rem based on screen size

### Adding Content
1. **New Sections**: Add new `<section>` elements in `index.html`
2. **Images**: Place in `photos/` directory and reference with relative paths
3. **Audio**: Place in `audio/` directory and update audio controls
4. **Styling**: Use Tailwind CSS classes or add custom CSS in the `<style>` section

## 📊 Performance

### Optimizations
- **CDN Resources**: Tailwind CSS loaded via CDN for faster loading
- **Optimized Images**: Compressed images for web
- **Minimal JavaScript**: Lightweight vanilla JS
- **Responsive Images**: Proper sizing for different devices

### Loading Speed
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## 👥 Team

### Principal Investigators
- **Zand, Ramin** - Lead Principal Investigator
- **McShane, Michael P.** - Co-Principal Investigator

### Co-Investigators and Staff
- **Abedi, Vida**
- **Gerzsenyi, Danielle**
- **Radfar, Nazli**
- **Thorndike, Sara F.**
- **Vamuri, Ajith**
- **Zonk, Michelle**

### Consultants
- **Thomas, Gay**
- **Suarez-Almazor, Maria E.**
- **Zimmerman, Emily**

### Community Advisory Board (CAB) Members
- **Coleman, Amber**
- **Hwang, Wenke**
- **Patrick, Scott**
- **Dux, Philip**
- **Richardson, Alicia**
- **Roy, Pete**
- **Taylor, Danielle**
- **Wasko, Lisa**
- **Wildasin, Amy**
- **Fetzer, Lannette**

## 📞 Contact

For questions about this project or the research initiative, please contact the lead institution or refer to the contact information provided on the website.

---

**Note**: This website is part of a research initiative supported by PCORI (Patient-Centered Outcomes Research Institute) and is designed to engage rural stroke survivors and caregivers in patient-centered outcomes research.