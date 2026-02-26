═══════════════════════════════════════════════════════
  VERDANT NATURALS — Website Package
  WhatsApp Business Integration Approval Site
═══════════════════════════════════════════════════════

COMPANY:  Verdant Naturals Pvt. Ltd.
GST NO.:  29AABCV1234M1ZX
ADDRESS:  47, 2nd Cross, Indiranagar, Bengaluru, Karnataka – 560 038
EMAIL:    hello@verdantnaturals.in
PHONE:    +91 80 4123 4567

─────────────────────────────────────────────────────
FILE STRUCTURE
─────────────────────────────────────────────────────
  index.html            → Homepage (About, Products, Contact)
  privacy.html          → Full Privacy Policy
  terms.html            → Full Terms & Conditions
  styles.css            → Single stylesheet (no external deps)
  assets/
    logo.svg            → Company logo (inline SVG)
    product-serum.svg   → Product 1 placeholder image
    product-cream.svg   → Product 2 placeholder image
    product-oil.svg     → Product 3 placeholder image
    product-mask.svg    → Product 4 placeholder image
  README.txt            → This file

─────────────────────────────────────────────────────
HOW TO TEST LOCALLY
─────────────────────────────────────────────────────

Option A — Direct browser open:
  1. Unzip this package into a folder.
  2. Double-click index.html to open in your browser.
  3. Navigate to privacy.html and terms.html via footer links.

Option B — Local HTTP server (recommended, avoids path issues):
  Using Python 3:
    cd /path/to/verdant-naturals/
    python3 -m http.server 8080
    Open: http://localhost:8080

  Using Node.js (npx):
    npx serve .
    Open the URL shown in your terminal.

─────────────────────────────────────────────────────
PRE-SUBMISSION CHECKLIST (WhatsApp Business Approval)
─────────────────────────────────────────────────────

 [ ] All three pages load without 404 errors
 [ ] Logo appears in header on all three pages
 [ ] Company name visible in header and footer
 [ ] "About Us" section present on homepage
 [ ] All 4 products display with images, names, descriptions
 [ ] Contact section has: phone (tel: link), email (mailto:), address, GST number
 [ ] Footer contains links to Privacy Policy and Terms & Conditions
 [ ] privacy.html loads and contains full Privacy Policy text
 [ ] terms.html loads and contains full Terms & Conditions text
 [ ] WhatsApp Business opt-out instructions present in Privacy Policy (Section 11)
 [ ] WhatsApp Business use described in Terms (Section 11)
 [ ] No broken image links (open browser DevTools → Network tab)
 [ ] No JavaScript console errors (open browser DevTools → Console tab)
 [ ] Site is mobile-responsive (resize browser to 375px width)
 [ ] All nav links work correctly across all pages
 [ ] No external HTTP/HTTPS links (except tel: and mailto:)

─────────────────────────────────────────────────────
DEPLOYING TO A SHARED HOST
─────────────────────────────────────────────────────

1. Upload all files maintaining the folder structure:
     public_html/
       index.html
       privacy.html
       terms.html
       styles.css
       assets/  (folder with all SVG files)

2. Your Privacy Policy URL will be:
     https://yourdomain.com/privacy.html

3. Your Terms URL will be:
     https://yourdomain.com/terms.html

4. Submit these URLs in the WhatsApp Business Manager
   under Business Settings → Business Info.

─────────────────────────────────────────────────────
REPLACING PLACEHOLDER IMAGES
─────────────────────────────────────────────────────

To replace SVG product placeholders with real photos:
  1. Place your .jpg or .png in the assets/ folder.
  2. In index.html, find the relevant <img> tag and update:
       src="./assets/product-serum.svg"
     to:
       src="./assets/your-photo.jpg"
  3. Update the alt attribute to match the real product.

─────────────────────────────────────────────────────
NOTES
─────────────────────────────────────────────────────
- No external CDNs, fonts, scripts, or analytics used.
- All fonts are system stack (works on all devices offline).
- No backend or server-side code required.
- Site is fully self-contained.
═══════════════════════════════════════════════════════
