# Static Website Projects

Three responsive, single-page websites built with plain **HTML and CSS** (no frameworks, no JavaScript). Each site is one self-contained `.html` file, so you can open it by double-clicking it.

| # | Project | File | Theme |
|---|---------|------|-------|
| 1 | **Sweet Bites** – bakery & cake shop | [`cakes_shop.html`](cakes_shop.html) | Pink / chocolate brown |
| 2 | **TechStore** – online electronics shop | [`online_shopping.html`](online_shopping.html) | Indigo / white |
| 3 | **Travel With Us** – travel agency | [`travel_agency.html`](travel_agency.html) | Teal / orange |

## Screenshots

Full-page captures at 1440 px (desktop). Mobile (390 px) captures are in [`screenshots/`](screenshots/) and in the PDF below.

| Sweet Bites | TechStore | Travel With Us |
|:-:|:-:|:-:|
| <img src="screenshots/cakes_shop_desktop.png" width="260"> | <img src="screenshots/online_shopping_desktop.png" width="260"> | <img src="screenshots/travel_agency_desktop.png" width="260"> |

> **Note:** the pages load their photos from Unsplash. When these screenshots were captured, those images could not be fetched, so the Sweet Bites photos are the ones from the original design and the TechStore and Travel With Us photos appear as labelled placeholders. Re-capture them on your own machine (browser DevTools → *Capture full size screenshot*) to show the real photos.

More material:

- [`docs/Screenshots.pdf`](docs/Screenshots.pdf) – all screenshots, desktop and mobile
- [`docs/Documentation.pdf`](docs/Documentation.pdf) – structure, design system, features and notes for each site

## Features

### 1. Sweet Bites (bakery)
- Header with logo and anchor navigation (Home, Products, Custom Cakes, Offers, Contact)
- Hero banner with call-to-action
- Product cards: Chocolate Cake ₹499, Vanilla Cake ₹449, Pastries ₹99, Chocolate Cookies ₹79
- Custom cake section, special offers, six-image gallery
- Contact section with a `mailto:` button and opening hours (9 AM – 9 PM)

### 2. TechStore (online shopping)
- Indigo hero banner and "Shop by Category" buttons (Mobiles, Laptops, Audio, Accessories)
- Eight product cards with discount badge, star rating, current price and struck-through old price
- Benefits strip: free delivery, secure shopping, customer support
- Hover effects on cards, category buttons and Buy buttons

### 3. Travel With Us (travel agency)
- Photo hero with call-to-action
- Six destination cards: Agra, Kerala, Goa, Manali, Jaipur, Maldives
- Three holiday packages: Kerala Tour ₹5,999 (3D/2N), Goa Beach Trip ₹7,499 (4D/3N), Manali Adventure ₹9,999 (5D/4N)
- Sample 3-day Kerala itinerary
- Inquiry form (name, email, destination, travellers, date, message) that opens the visitor's email client

## Tech stack

- HTML5
- CSS3 (Flexbox, media queries, hover states)
- Images from [Unsplash](https://unsplash.com) (hot-linked)

## Getting started

```bash
git clone <your-repo-url>
cd <your-repo-folder>
```

Then open any of the three `.html` files in a browser. No build step or server is needed.

### Publish with GitHub Pages
1. Push the repository to GitHub.
2. Go to **Settings → Pages**, choose the `main` branch and the `/ (root)` folder, then save.
3. The pages will be available at `https://<username>.github.io/<repo>/cakes_shop.html` (and the same for the other two files).

## Project structure

```
.
├── cakes_shop.html          # Sweet Bites bakery
├── online_shopping.html     # TechStore
├── travel_agency.html       # Travel With Us
├── screenshots/             # PNG captures (desktop + mobile)
├── docs/
│   ├── Screenshots.pdf
│   └── Documentation.pdf
└── README.md
```

## Customising

- **Colours and fonts:** edit the rules inside the `<style>` block at the top of each file.
- **Products and prices:** copy one `.card` / `.product-card` block and change the text, image URL and price.
- **Contact details:** the email, phone and address are sample values (`example.com`); replace them with real ones.
- **Images:** swap the Unsplash URLs for your own files (for example in an `images/` folder) so the pages work offline.

## Known limitations

- Sample data only: prices, phone numbers and email addresses are placeholders for a student project.
- Buttons such as *Order Now*, *Buy Now* and *Enquire Now* scroll to the contact area; there is no cart or checkout.
- The travel inquiry form uses `mailto:`, so it depends on the visitor having an email app configured.
- Photos are hot-linked and need an internet connection.

## Author

*Add your name here.*

## License

*Add a license of your choice (for example MIT) before publishing.*
