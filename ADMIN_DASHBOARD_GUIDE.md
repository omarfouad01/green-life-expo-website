# Green Life Expo - Admin Dashboard Guide

## 🎉 Your Admin Dashboard is Ready!

### 🌐 Access URLs

**Main Website:** https://mwp6myux32.skywork.website

**Admin Login:** https://mwp6myux32.skywork.website/#/admin/login

**GitHub Repository:** https://github.com/omarfouad01/green-life-expo-website

---

## 🔐 Getting Started

### Step 1: Create Your Admin Account

You need to create an admin account in Supabase:

1. Go to your Supabase project: https://supabase.com/dashboard
2. Navigate to **Authentication** → **Users**
3. Click **Add User** → **Create new user**
4. Enter your email and password
5. Click **Create user**

### Step 2: Login to Admin Dashboard

1. Visit: https://mwp6myux32.skywork.website/#/admin/login
2. Enter your email and password
3. Click **Login**

---

## 📊 Dashboard Features

### 1. **Dashboard** (`/admin/dashboard`)
- Overview of all statistics
- Quick access to main features
- Recent activity feed

### 2. **Site Settings** (`/admin/settings`)
Control all website text content:
- ✏️ **General Info**: Site title, tagline
- 🎯 **Hero Section**: Main headline, subtitle, event date/location
- 📊 **Statistics**: Visitor count, exhibitor count, workshops, days
- 📧 **Contact Info**: Email, phone, address, social media links

### 3. **Design & Colors** (`/admin/design`)
Customize your brand colors:
- 🎨 Primary Color (Green)
- 🎨 Secondary Color (Light Green)
- 🎨 Accent Color (Gold)
- 🎨 Background Color (Beige)
- Real-time color preview
- HSL color format support

### 4. **Packages** (`/admin/packages`)
Manage exhibitor and sponsor packages:
- ✏️ Edit package names and prices
- 📝 Add/remove features
- ⭐ Mark packages as "Popular"
- 🔄 Reorder packages
- ✅ Activate/deactivate packages

### 5. **FAQs** (`/admin/faqs`)
Manage frequently asked questions:
- ➕ Add new FAQs
- ✏️ Edit existing FAQs
- 🗑️ Delete FAQs
- 📂 Categorize FAQs
- 🔄 Reorder FAQs

### 6. **Submissions** (`/admin/submissions`)
View all form submissions:
- 📧 Contact form submissions
- 🏢 Exhibitor applications
- 🤝 Sponsor inquiries
- ✅ Mark as read/replied
- 📊 Filter by type

---

## 🎨 How to Change Colors

Colors use HSL format: `hue saturation% lightness%`

**Examples:**
- Green: `130 45% 30%`
- Blue: `210 80% 50%`
- Red: `0 70% 50%`

**HSL Values:**
- **Hue**: 0-360 (color on the wheel)
  - Red: 0
  - Green: 120
  - Blue: 240
- **Saturation**: 0-100% (color intensity)
- **Lightness**: 0-100% (brightness)

---

## 📝 How to Update Content

### Update Homepage Hero:
1. Go to **Site Settings**
2. Click **Hero Section** tab
3. Edit "Hero section title" and "Hero section subtitle"
4. Click **Save Changes**

### Update Statistics:
1. Go to **Site Settings**
2. Click **Statistics** tab
3. Update numbers (e.g., "500+" → "600+")
4. Click **Save Changes**

### Update Contact Info:
1. Go to **Site Settings**
2. Click **Contact Info** tab
3. Update email, phone, address, social links
4. Click **Save Changes**

### Edit Packages:
1. Go to **Packages**
2. Click **Edit** on any package
3. Modify name, price, or features
4. Click **Save Changes**

### Manage FAQs:
1. Go to **FAQs**
2. Click **Add FAQ** or **Edit** existing
3. Enter question and answer
4. Click **Save**

---

## 🔒 Security Best Practices

1. **Use Strong Password**: At least 12 characters with mix of letters, numbers, symbols
2. **Don't Share Credentials**: Keep your admin login private
3. **Regular Backups**: Supabase automatically backs up your data
4. **Monitor Submissions**: Check submissions regularly for spam

---

## 🆘 Troubleshooting

### Can't Login?
- Check your email and password
- Make sure you created the user in Supabase
- Clear browser cache and try again

### Changes Not Showing?
- Click **Save Changes** button
- Refresh the main website (Ctrl+F5 or Cmd+Shift+R)
- Wait a few seconds for changes to propagate

### Lost Admin Access?
- Go to Supabase Dashboard
- Reset password in Authentication → Users
- Or create a new admin user

---

## 📱 Mobile Access

The admin dashboard works on mobile devices:
- Responsive design
- Touch-friendly interface
- All features available

---

## 🎓 Quick Tips

1. **Save Often**: Click save after each change
2. **Preview Changes**: Open main website in another tab to see updates
3. **Organize FAQs**: Use categories and display order
4. **Monitor Submissions**: Check daily for new inquiries
5. **Backup Important Data**: Export important submissions

---

## 📞 Support

For technical issues:
- Check Supabase Dashboard for database status
- Review browser console for errors
- Ensure stable internet connection

---

## 🚀 What You Can Control

✅ All text content on every page
✅ Brand colors and design
✅ Statistics and numbers
✅ Contact information
✅ Exhibitor packages and pricing
✅ Sponsor packages and pricing
✅ FAQs
✅ View all form submissions

---

## 📊 Database Tables

Your content is stored in these tables:
- `site_settings_20251225` - General settings
- `packages_20251225` - Exhibitor/sponsor packages
- `faqs_20251225` - Frequently asked questions
- `contact_submissions_20251225` - Form submissions

All data is securely stored in Supabase with automatic backups.

---

**Enjoy your new admin dashboard! 🎉**
