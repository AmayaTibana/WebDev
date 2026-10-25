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

**Colors (4) - "North Star Night"**

| Color | Hex | Used for |
| --- | --- | --- |
| Navy | `#1F3A5F` | The night sky: headings, links, buttons, header border, current page in the nav |
| Gold | `#E3B448` | The star: accents only (card borders, dividers, link underlines, hover, keyboard focus) |
| Ivory | `#FBF7EF` | Page background, text on dark areas |
| Ink | `#22252B` | Body text and footer background |

**Fonts (2)**

- **Playfair Display** for headings (h1, h2, h3, and form legends)
- **Nunito** for body text, navigation, and form fields

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
