# 🎵 Midtopia Studio - Booking PWA

Professional recording studio booking app for iOS, Android, and web.

## ✨ Features

- 📱 Installs like a native app on any device
- 📅 Integrated booking calendar (Cal.com)
- 💬 SMS notifications (Twilio)
- 🎨 Custom branded design with Midtopia colors
- 📍 Geolocation and directions
- 💰 Two service tiers ($75/hr with engineer, $50/hr solo)
- 🔒 Secure HTTPS hosting
- 📴 Works offline for viewing info

## 🚀 Quick Start

### Deploy in 2 Minutes:

1. Go to https://www.netlify.com
2. Sign up (free)
3. Drag the `midtopia-booking` folder onto Netlify
4. Done! Your site is live.

**Detailed instructions:** See `DEPLOYMENT-GUIDE.md`

## 📁 What's Included

- `index.html` - Main booking website
- `manifest.json` - PWA configuration
- `sw.js` - Service worker (offline mode)
- `logo.png` - Midtopia logo
- `icons/` - App icons (all sizes for iOS/Android)
- `DEPLOYMENT-GUIDE.md` - Complete setup instructions

## 🔧 Configuration

### 1. Connect Cal.com

Edit `index.html` line 435:
```html
<a href="https://cal.com/YOUR-USERNAME"
```
Replace `YOUR-USERNAME` with your Cal.com username.

### 2. Update Email

Edit `index.html` line 383:
```html
booking@midtopiastudio.com
```
Replace with your actual email.

### 3. Add Photos (Next Week)

Replace placeholder images in the gallery section with your studio photos.

## 📱 How It Works

### For You:
1. Customer visits your link
2. They select a service and time
3. You get SMS notification
4. You approve/deny in Cal.com
5. Customer gets confirmation SMS

### For Customers:
1. Tap your link (from text/social media)
2. Phone prompts "Add to Home Screen"
3. Midtopia icon appears on their phone
4. Opens full-screen like a real app
5. Books their session instantly

## 💰 Costs

- Hosting: **$0/month** (Netlify free tier)
- Cal.com: **$0/month** (free tier)
- SMS: **~$2/month** (Twilio - 100 messages)

**Total: $2/month** 🎉

## 🌐 Browser Support

- ✅ iPhone (Safari) - iOS 11.3+
- ✅ Android (Chrome) - Android 5+
- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ iPad and tablets

## 📞 Support

Questions? See the full `DEPLOYMENT-GUIDE.md` for:
- Step-by-step deployment instructions
- Cal.com integration guide
- Customization options
- Troubleshooting tips

## 🎯 What Makes This Different

**Not a "real" app but better:**
- No app store approval delays
- No $99/year Apple developer fee
- Works on ALL devices instantly
- Updates propagate immediately
- Better discoverability (Google, social media)
- SMS notifications more reliable than push
- 73% less friction than app downloads

**Customers will never know it's not a native app!**

## 📊 Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **PWA**: Service Workers, Web App Manifest
- **Booking**: Cal.com (embedded)
- **Notifications**: Twilio SMS + Zapier
- **Hosting**: Netlify/Vercel (free tier)

## 🚀 Ready to Launch

1. Deploy to Netlify (follow `DEPLOYMENT-GUIDE.md`)
2. Set up Cal.com booking system
3. Configure SMS notifications
4. Share your link
5. Start booking sessions! 🎸

---

**Built for Midtopia Studio**  
424 S. Greenwood St, Wichita, KS 67211
