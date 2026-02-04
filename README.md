# Biodaat Website

Modern, professional website for Biodaat - Data Analytics & Bioinformatics.

## 🚀 Quick Deploy to GitHub Pages (FREE!)

### Step 1: Create GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `biodaat-website` (or `biodaat.github.io` for username.github.io URL)
3. Make it **Public**
4. Click "Create repository"

### Step 2: Upload Files
1. Click "uploading an existing file"
2. Drag all files from this folder
3. Commit directly to `main` branch

### Step 3: Enable GitHub Pages
1. Go to repository **Settings** → **Pages**
2. Under "Source", select `main` branch
3. Click **Save**
4. Wait 2-3 minutes for deployment

Your site will be live at: `https://YOUR-USERNAME.github.io/biodaat-website/`

### Step 4: Connect Your Domain (biodaat.com)

#### A. In GitHub:
1. Go to Settings → Pages
2. Under "Custom domain", enter: `www.biodaat.com`
3. Click Save
4. Check "Enforce HTTPS"

#### B. In Your Domain Registrar (Namecheap/Cloudflare/etc):
Add these DNS records:

**For www.biodaat.com:**
```
Type: CNAME
Name: www
Value: YOUR-USERNAME.github.io
```

**For biodaat.com (apex domain):**
```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153
```

Wait 24-48 hours for DNS propagation.

---

## 📧 Setup Contact Form (Formspree)

1. Go to [formspree.io](https://formspree.io) and sign up (free)
2. Create a new form
3. Copy your form ID (looks like `xyzabcde`)
4. Open `contact.html` and replace `YOUR_FORM_ID`:
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
5. Commit the change

Free tier: 50 submissions/month (plenty for a business site)

---

## 💰 Cost Comparison

| Item | Wix | GitHub Pages |
|------|-----|--------------|
| Hosting | $15-25/month | **FREE** |
| Domain | Included | ~$10/year |
| SSL | Included | **FREE** |
| Forms | Included | Free (Formspree) |
| **Annual Cost** | ~$180-300 | **~$10** |

**Savings: ~$170-290/year!**

---

## 📁 File Structure

```
biodaat-website/
├── index.html          # Home page
├── about.html          # About page
├── life-science.html   # Life Science services
├── business.html       # Smarter Business services
├── products.html       # Products page
├── blog.html           # Blog listing
├── contact.html        # Contact form
├── accessibility.html  # Accessibility statement
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # JavaScript
├── images/             # Your images
└── blog/               # Blog posts (create as needed)
```

---

## 🖼️ Adding Your Images

1. Download your images from Wix (right-click → Save)
2. Place them in the `images/` folder
3. Update the HTML files to reference them:
   ```html
   <img src="images/your-photo.jpg" alt="Description">
   ```

For your profile photo, replace the emoji placeholder in `about.html`.

---

## 📝 Adding Blog Posts

Create new files in the `blog/` folder. Example structure for a post:

```html
<!-- blog/my-new-post.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Post Title | Biodaat Blog</title>
    <link rel="stylesheet" href="../css/style.css">
</head>
<body>
    <!-- Copy nav from other pages -->
    
    <section class="page-header">
        <div class="container">
            <div class="page-header-content">
                <h1>Post Title</h1>
                <p>January 30, 2025 • 5 min read</p>
            </div>
        </div>
    </section>
    
    <section>
        <div class="container">
            <article style="max-width: 800px; margin: 0 auto;">
                <p>Your content here...</p>
            </article>
        </div>
    </section>
    
    <!-- Copy footer from other pages -->
</body>
</html>
```

Then add a card in `blog.html` linking to it.

---

## 🔧 Customization

### Colors
Edit CSS variables in `css/style.css`:
```css
:root {
    --primary: #0a1628;      /* Dark blue background */
    --accent: #00d4aa;       /* Teal accent */
    --accent-warm: #ff6b35;  /* Orange accent */
}
```

### Fonts
The site uses:
- **Outfit** - Main font (headings & body)
- **Space Mono** - Monospace for labels

Change in the `@import` line in `style.css`.

---

## ✅ Transfer Checklist

- [ ] Create GitHub repository
- [ ] Upload all files
- [ ] Enable GitHub Pages
- [ ] Set up Formspree for contact form
- [ ] Transfer domain from Wix
- [ ] Update DNS records
- [ ] Add your profile photo
- [ ] Download and add other images from Wix
- [ ] Test all pages
- [ ] Cancel Wix subscription

---

## 🆘 Need Help?

Contact: info@biodaat.com

Or open an issue on GitHub!
