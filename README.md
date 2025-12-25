# Green Life Expo Website

🌱 **Egypt's Leading Go Green & Healthy Living Expo**

## 🌐 Live Website
[https://4hknrshye7.skywork.website](https://4hknrshye7.skywork.website)

## 📖 About
A complete, modern website for the Green Life Expo - a curated exhibition bringing together organic products, healthy lifestyles, and sustainable solutions under one platform.

## ✨ Features

### Pages
- **Homepage** - Hero section with event highlights and statistics
- **About** - Mission, vision, story, and core values
- **Exhibitors** - Exhibition packages and application form
- **Sponsors** - Sponsorship opportunities and benefits
- **Visitors** - Event information and visitor guide
- **Contact** - Contact form and FAQ

### Design
- 🎨 Custom brand colors matching Green Life Expo identity
- 📱 Fully responsive design for all devices
- ⚡ Fast loading with optimized images
- ♿ Accessible and user-friendly interface

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/omarfouad01/green-life-expo-website.git

# Navigate to project directory
cd green-life-expo-website

# Install dependencies
npm install

# Start development server
npm run dev
```

The website will be available at `http://localhost:5173`

## 🛠️ Build for Production

```bash
npm run build
```

Production files will be generated in the `dist/` folder.

## 🎨 Brand Colors

- **Primary Green**: #2A7038
- **Secondary Green**: #68B87B
- **Dark Gray**: #323232
- **Accent Gold**: #D4AF37
- **Background Beige**: #F8F6F0

## 📁 Project Structure

```
green-life-expo-website/
├── src/
│   ├── components/
│   │   ├── Header.tsx          # Navigation header
│   │   ├── Footer.tsx          # Footer component
│   │   └── ui/                 # Reusable UI components
│   ├── pages/
│   │   ├── Index.tsx           # Homepage
│   │   ├── About.tsx           # About page
│   │   ├── Exhibitors.tsx      # Exhibitors page
│   │   ├── Sponsors.tsx        # Sponsors page
│   │   ├── Visitors.tsx        # Visitors page
│   │   └── Contact.tsx         # Contact page
│   ├── index.css               # Global styles & design system
│   ├── App.tsx                 # Main app with routing
│   └── main.tsx                # Entry point
├── public/
│   └── images/                 # Logo and images
└── package.json                # Dependencies
```

## 🔧 Technologies Used

- **React 18** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool
- **Tailwind CSS** - Styling
- **React Router** - Navigation
- **Shadcn/ui** - UI components
- **Lucide React** - Icons

## 📝 Customization

### Change Colors
Edit `src/index.css` and modify the CSS variables in the `:root` section.

### Edit Content
All page content is in the `src/pages/` folder. Each page is a separate component.

### Modify Navigation
Edit `src/components/Header.tsx` to add/remove menu items.

### Update Footer
Edit `src/components/Footer.tsx` for footer content and links.

## 📧 Contact

For questions about Green Life Expo:
- Email: info@greenlifeexpo.com
- Phone: +20 123 456 7890
- Location: Cairo, Egypt

## 📄 License

This project is open source and available for use.

---

Built with ❤️ for a greener future 🌍
