# Green Life Expo - Source Code Guide

## 🌐 Live Website
https://4hknrshye7.skywork.website

## 📁 Project Structure

```
green_life_expo/
├── src/
│   ├── components/
│   │   ├── Header.tsx          # Navigation header
│   │   ├── Footer.tsx          # Footer component
│   │   └── ui/                 # UI components (buttons, cards, etc.)
│   ├── pages/
│   │   ├── Index.tsx           # Homepage
│   │   ├── About.tsx           # About page
│   │   ├── Exhibitors.tsx      # Exhibitors page
│   │   ├── Sponsors.tsx        # Sponsors page
│   │   ├── Visitors.tsx        # Visitors page
│   │   └── Contact.tsx         # Contact page
│   ├── index.css               # Design system & brand colors
│   ├── App.tsx                 # Main app with routing
│   └── main.tsx                # Entry point
├── public/
│   └── images/                 # Logo and images
├── package.json                # Dependencies
├── tailwind.config.ts          # Tailwind configuration
└── vite.config.ts              # Vite configuration
```

## 🎨 Brand Colors (in src/index.css)

- Primary Green: #2A7038 (hsl(130 45% 30%))
- Secondary Green: #68B87B (hsl(135 35% 56%))
- Dark Gray: #323232 (hsl(0 0% 20%))
- Accent Gold: #D4AF37 (hsl(43 65% 53%))
- Background Beige: #F8F6F0 (hsl(40 25% 97%))

## 🚀 How to Run Locally

1. Install Node.js (v18 or higher)
2. Extract the source code
3. Open terminal in the project folder
4. Run: `npm install`
5. Run: `npm run dev`
6. Open browser to: http://localhost:5173

## 📦 Build for Production

```bash
npm run build
```

The production files will be in the `dist/` folder.

## 🔧 Key Technologies

- React 18
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Shadcn/ui components

## 📝 Customization Tips

### Change Colors
Edit `src/index.css` - look for the `:root` section

### Edit Content
All page content is in `src/pages/` folder

### Modify Navigation
Edit `src/components/Header.tsx`

### Update Footer
Edit `src/components/Footer.tsx`

### Add New Pages
1. Create new file in `src/pages/`
2. Add route in `src/App.tsx`
3. Add link in `src/components/Header.tsx`

## 📧 Support

For questions about the code, refer to:
- React docs: https://react.dev
- Tailwind docs: https://tailwindcss.com
- Vite docs: https://vitejs.dev

