# 📸 How to Add Your LinkedIn Photo to Your Website

## Quick Steps

### Step 1: Download Your LinkedIn Photo
1. Visit your LinkedIn profile: https://www.linkedin.com/in/diyadeepu/
2. Right-click on your profile photo
3. Select "Save image as..."
4. Save as `profile.jpg` (or `.png`)
5. Save it in your project folder: `/Users/diyadeepu/PycharmProjects/personal_website/`

### Step 2: Verify File is in Place
Your project folder should now have:
```
personal_website/
├── index.html
├── styles.css
├── script.js
├── profile.jpg  ← Your photo here!
└── ...other files
```

### Step 3: Test Locally
1. Open `index.html` in your browser
2. You should see your profile photo in the About section on the left
3. Hover over the photo to see the hover effect

### Step 4: Deploy
When you push to GitHub/Vercel/Netlify, make sure to include the `profile.jpg` file.

---

## Photo Requirements

### Best Format
- **Size:** 250×250 pixels (website will resize, but this is optimal)
- **Format:** JPG or PNG
- **File name:** `profile.jpg` or `profile.png`
- **File size:** < 500KB (compress if needed)

### Recommended Photo
- Professional headshot
- Clear face visible
- Good lighting
- Simple background
- Dressed professionally
- Genuine smile (like your LinkedIn photo!)

---

## If You Need to Compress the Image

### Mac Users (Easy Way)
1. Right-click image → Open with Preview
2. Tools → Adjust Size
3. Set to 250×250 pixels
4. File → Export → Save as JPEG

### Or Use Online Tool
- Visit: https://imagecompressor.com
- Upload your photo
- Download compressed version

---

## Making It Even More Modern

I've already updated your website to include:
✅ Professional photo with blue border
✅ Hover animation (scales up slightly)
✅ Responsive layout (photo adjusts on mobile)
✅ Professional shadow effect
✅ Rounded corners for modern look

---

## If Photo Doesn't Show

**Common Issues:**

1. **File not in right folder**
   - Make sure `profile.jpg` is in the same folder as `index.html`

2. **Wrong file name**
   - Check that file is exactly named `profile.jpg`
   - (or update `src="profile.jpg"` in HTML if different name)

3. **File format issue**
   - Try converting to JPG if using PNG
   - Ensure file is actually an image

---

## Want to Use Different Photo?

Simply replace `profile.jpg` with your new photo (same name and location).

Or edit `index.html` and change:
```html
<img src="profile.jpg" alt="Professional headshot" class="profile-photo">
```

to:

```html
<img src="your-photo-name.jpg" alt="Professional headshot" class="profile-photo">
```

---

## Updating HTML if Needed

The website now expects a photo file. If you want to temporarily remove it, edit `index.html` and remove this line:

```html
<div class="profile-photo-container">
    <img src="profile.jpg" alt="Professional headshot" class="profile-photo">
</div>
```

Or comment it out:
```html
<!-- <div class="profile-photo-container">
    <img src="profile.jpg" alt="Professional headshot" class="profile-photo">
</div> -->
```

---

## Responsive Design

The photo will:
- **Desktop:** Appear on the left, 250×250px with blue border
- **Tablet:** Stack above the bio content
- **Mobile:** Full width, responsive sizing

---

**Your website is now set up to display your professional photo!**
**Just download and save your LinkedIn photo as `profile.jpg` and you're ready to go! 🎉**

