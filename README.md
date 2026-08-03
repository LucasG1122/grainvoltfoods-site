# GrainVolt landing page

A lightweight, single-page website for GrainVolt, a Boston-based pre-launch food
venture developing high-protein rice cereal products. The site is designed for
supplier, manufacturing, product-development, and other relevant business
outreach.

The project uses only static HTML and CSS. It has no framework, build step,
JavaScript, analytics, cookies, or external asset dependencies.

## File structure

```text
grainvolt-site/
├── .nojekyll      # Publishes files directly through GitHub Pages
├── CNAME          # Configures the grainvoltfoods.com custom domain
├── index.html      # Page structure, content, and metadata
├── styles.css      # Responsive layout and visual design
├── favicon-clean.png              # Transparent GrainVolt symbol
├── grainvolt-logo-clean.png       # Supplied GrainVolt lockup, background removed
├── hero-rice-cereal-volt-720.jpg  # Responsive campaign product image
├── hero-rice-cereal-volt-1122.jpg # High-resolution campaign product image
├── og-volt.jpg                    # 1200×630 social sharing card
└── README.md       # Project and deployment instructions
```

## Preview locally

The site can be opened directly by double-clicking `index.html`.

For a more representative local preview, start any simple static file server in
this folder. For example, if Python is installed:

```sh
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

No installation or build command is required.

## Deploy to a generic static host

1. Upload `index.html`, `styles.css`, `favicon-clean.png`,
   `grainvolt-logo-clean.png`, both Volt hero images, and
   `og-volt.jpg` to the host's public web directory.
2. Keep the files at the same relative paths.
3. Configure the host to serve `index.html` at the site root.
4. Enable HTTPS using the host's certificate or managed HTTPS option.
5. Open the deployed URL and test the navigation and email links.

This project is compatible with standard static hosting services, object-storage
static websites, and conventional web servers.

## Connect `grainvoltfoods.com`

1. Add `grainvoltfoods.com` as a custom domain in the hosting provider's
   dashboard.
2. Note the DNS target or records supplied by that provider.
3. In the domain registrar's DNS manager, add the requested records for the
   root domain.
4. Add or redirect `www.grainvoltfoods.com` according to the host's
   instructions.
5. Wait for DNS propagation and the host's HTTPS certificate to finish
   provisioning.

DNS record types and values vary by hosting provider. Use the exact records
shown by the selected host; do not copy example IP addresses or targets from
unrelated services.

## Pre-launch checklist

- [ ] Confirm HTTPS works.
- [ ] Confirm `grainvoltfoods.com` loads.
- [ ] Confirm `www.grainvoltfoods.com` redirects or resolves correctly.
- [ ] Test every email link.
- [ ] Test the mobile layout, including at 320px wide.
- [ ] Check spelling and contact information.
- [ ] Confirm no placeholder text remains.
