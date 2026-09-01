# Pinki Milikipi — GitHub Pages Store

## Files
- `index.html` — complete website
- `images/` — 20 tiny working sample SVG images

## Replace product photos
Open `index.html` and find `PRODUCT DATABASE / PRODUCT CONFIGURATION`.
Each product has an `images` array. Replace the sample `.svg` paths with your PNG/JPG/WebP paths, e.g.
`images: ["images/product1-1.jpg", "images/product1-2.jpg", "images/product1-3.jpg"]`

You can also simply replace the sample SVG files with your own files if you keep the same filenames/extensions.

## Add the remaining 25 products
Copy one product object inside `const PRODUCTS = [...]`, change its ID/name/price/category/descriptions/images. No rendering code needs changing.

## FormSubmit
The current email is `reinsangma@gmail.com` in:
`const FORM_EMAIL = "reinsangma@gmail.com";`
Change that line if needed. FormSubmit is required for order submission because this is a static GitHub Pages site.

## GitHub Pages
Upload the contents of this folder to a repository. In GitHub:
Settings → Pages → Deploy from branch → choose your branch and `/ (root)` → Save.

## Important
The website has no database, Firebase, PHP, server-side code, or payment gateway. Cart data is stored locally in the customer's browser. Orders require internet access because FormSubmit is an external form service.
