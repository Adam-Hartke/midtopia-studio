# 📝 QUICK CUSTOMIZATION REFERENCE

## Most Common Edits (All in index.html)

### 1. Change Cal.com Link
**Line 435**
```html
<a href="https://cal.com/YOUR-USERNAME"
```
➡️ Replace with: `https://cal.com/midtopia-studio`

### 2. Update Email Address
**Line 383**
```html
<a href="mailto:booking@midtopiastudio.com">
```
➡️ Replace with your real email

### 3. Change Phone Number (for "Call Us" button)
Add after line 387:
```html
<p>📞 <a href="tel:+13165551234">(316) 555-1234</a></p>
```

### 4. Update Studio Hours
Add in the "How Booking Works" section (around line 346):
```html
<li>Studio hours: Mon-Fri 10am-8pm, Sat 12pm-6pm</li>
```

### 5. Add Photos (Next Week)
**Line 300-307** (Gallery section)

Replace:
```html
<div class="gallery-item">Photo Coming Soon</div>
```

With:
```html
<div class="gallery-item">
  <img src="studio1.jpg" style="width:100%; height:100%; object-fit:cover; border-radius:15px;">
</div>
```

### 6. Embed Cal.com Calendar
**Lines 448-456** (Currently commented out)

Remove `<!--` at line 448 and `-->` at line 456, then update:
```html
<iframe src="https://cal.com/YOUR-USERNAME" ...>
```

### 7. Change Price
**Lines 242 & 260**
```html
<div class="price">$75<span>/hour</span></div>
```
➡️ Update the number

### 8. Add Social Media Links
Add before the footer (around line 378):
```html
<div style="text-align: center; padding: 20px;">
  <a href="https://instagram.com/midtopiastudio" style="color: var(--primary-gold); margin: 0 15px;">📷 Instagram</a>
  <a href="https://facebook.com/midtopiastudio" style="color: var(--primary-gold); margin: 0 15px;">👍 Facebook</a>
</div>
```

---

## Color Customization (index.html)

**Lines 28-34** (CSS Variables)
```css
:root {
    --primary-gold: #F5B443;        /* Main gold color */
    --secondary-orange: #E89236;    /* Secondary accent */
    --dark-orange: #C97B2E;        /* Darker accent */
    --black: #000000;              /* Background */
    --white: #FFFFFF;              /* Text */
}
```

---

## How to Edit & Re-Deploy

1. **Open file**: Use any text editor
   - Mac: TextEdit (set to Plain Text mode)
   - Windows: Notepad
   - Best: Visual Studio Code (free)

2. **Make changes**: Edit the lines above

3. **Save file**: Cmd+S / Ctrl+S

4. **Re-deploy**:
   - Go to Netlify/Vercel
   - Drag the updated folder
   - New version live in 30 seconds!

---

## Testing Changes Locally

Don't have a local server? Here's the easiest way:

### Option 1: Python (Mac/Linux)
```bash
cd midtopia-booking
python3 -m http.server 8000
```
Visit: http://localhost:8000

### Option 2: VS Code
1. Install "Live Server" extension
2. Right-click `index.html`
3. Click "Open with Live Server"

### Option 3: Just Upload to Netlify
- Testing in production is fine for small sites!
- Netlify is fast enough that you can test there

---

## Common Questions

**Q: Can I add more photos later?**  
A: Yes! Just add the image files to the folder and update the gallery section.

**Q: How do I change the logo?**  
A: Replace `logo.png` with your new logo (keep the same filename).

**Q: Can I add a "Call Us" button?**  
A: Yes! Add a phone number link (see #3 above).

**Q: How do I remove the "Install App" prompt?**  
A: Delete lines 396-406 in index.html.

**Q: Can I change the font?**  
A: Yes, but it's complex. The current font works perfectly on all devices.

---

## Need More Help?

- **HTML/CSS Tutorial**: https://www.w3schools.com
- **Cal.com Docs**: https://docs.cal.com
- **Netlify Docs**: https://docs.netlify.com

---

## Backup Your Files!

Before making big changes:
1. Make a copy of the entire folder
2. Name it `midtopia-booking-backup-JAN27`
3. Now you can experiment safely

If you break something, just re-deploy the backup!
