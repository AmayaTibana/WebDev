# WebDev

North Star Bakery Website

A four-page website for North Star Bakery, a neighborhood bakery that bakes everything by hand. The site helps local customers, commuters, families, and event planners see the products and send pre-order requests.

This started as my Touchstone Task 2 (HTML structure) and was updated for Touchstone 3 (CSS visual design and responsive layout).

## Pages

| File | What it has |
| --- | --- |
| `index.html` | Welcome message, pre-order button, featured item of the week, what we're known for, audio message from the bakers, hours and location |
| `products.html` | Breads, pastries, and cakes with short descriptions and price ranges |
| `about.html` | Bakery story, Signature Loaf figure, behind-the-scenes video, sourcing philosophy, staff highlights |
| `contact.html` | Inquiry and pre-order form, location, hours of operation |
| `styles.css` | One external stylesheet shared by all four pages |

## Touchstone 3: Design System

**Colors (4)**

| Color | Hex | Used for |
| --- | --- | --- |
| Cream | `#FFF8F0` | Page background, text on dark areas |
| Brown | `#6B3E26` | Headings, links, buttons, header border, current page in the nav |
| Peach | `#D88C5A` | Accents only: card borders, dividers, hover, keyboard focus |
| Charcoal | `#2F2A26` | Body text and footer background |

**Fonts (2)**

- **Lora** for headings (h1, h2, h3, and form legends)
- **Open Sans** for body text, navigation, and form fields

**Responsive layout**

- Mobile-first: the base CSS is written for phones, with everything stacked in one column.
- Flexbox is used for the header, navigation, card rows, image and text sections, the contact page layout, and the hours list.
- One media query, `@media (min-width: 768px)`, moves the logo and navigation into one row, puts the cards side by side, places images next to their text, and puts the form next to the location and hours on the contact page.

## HTML Features Used

- Semantic `header`, `nav`, `main`, and `footer` on every page
- Navigation built with an unordered list and relative links
- Images with descriptive alt text
- A `figure` with `figcaption` for the Signature Loaf
- A responsive image using `picture` and `source`
- An `audio` element and a `video` element, both with fallback text
- A form with `label`, `fieldset`, `legend`, and built-in validation (`required`, `type="email"`, `type="date"`, `pattern`, `maxlength`)

## How to View It

Open `northstar/index.html` in a browser, or run a local server from the `northstar` folder:

```bash
python3 -m http.server 8000
```

Then go to http://localhost:8000. In GitHub Codespaces, click **Open in Browser** when the pop-up appears.

## Media

All images, audio, and video come from the North Star Bakery media files provided by the course. For Touchstone 3 I replaced the images with the updated course files and compressed the behind-the-scenes video from about 99 MB to under 1 MB so it loads quickly and fits on GitHub. Business details like the address, phone number, and staff names are placeholders.

## Author

Carlos Amaya
