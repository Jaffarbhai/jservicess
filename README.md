# JServicess Website

Social media agency & store — static website (GitHub Pages ready).

## Files
- `index.html` — poori website (design, animations, checkout, WhatsApp orders)
- `assets/js-mark.png` — JS logo

## GitHub Pages par free deploy kaise karein

1. github.com par login karein aur **New repository** banayein (naam jaise `jservicess`). **Public** rakhein.
2. Repository mein **Add file → Upload files** par click karein.
3. Is zip ko unzip karein aur `index.html`, `README.md` aur `assets` folder ko drag & drop kar dein. **Commit changes** dabayein.
4. Repository ki **Settings → Pages** mein jayein.
5. **Source:** "Deploy from a branch", **Branch:** `main` aur folder `/ (root)` chunein, phir **Save**.
6. 1–2 minute baad website is link par live hogi:
   `https://<aapka-username>.github.io/<repository-naam>/`

## Apna domain (optional)
Settings → Pages → **Custom domain** mein apna domain (jaise `jservicess.com`) likhein, aur domain provider par GitHub ke DNS records add karein.

## Tabdeeli kaise karein
- WhatsApp number: `index.html` mein `923162045631` search karke badlein.
- Prices aur products: `index.html` ke neeche script mein `var P = [` aur `var earning = [` wale hisse mein.

Note: website internet par chalne ke liye ek chhoti library (Preact/htm) unpkg.com se load karti hai, isliye offline nahi chalegi — GitHub Pages par bilkul theek chalegi.
