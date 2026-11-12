# Savannah Spoon Inn

A three-page website for a fictional hotel and restaurant, **Savannah Spoon Inn**, built with plain HTML and CSS as a learning project. The restaurant's tagline is *"Where every plate tells a story."*

The site presents an East African-inspired menu with flame-grilled meats, coastal seafood, vegetarian plates, Swahili classics and sweet endings.

## Pages

| Page | File | What it contains |
|------|------|------------------|
| Home | `landing_page.html` | Welcome banner, image strip, and the full menu (Drinks, Appetizers, Main Entrees, Sides, Desserts) with old and discounted prices |
| About Us | `about_page.html` | Our story, four brand values, menu categories, and a photo gallery from the kitchen |
| Contacts | `contacts_page.html` | Address, phone and email cards, a contact form, and opening hours |

## Features

- Shared navigation bar and footer across all pages
- Menu grouped into sections, with a collapsible "Click here to view Menu" index (`<details>`)
- Main Entrees split into Meat and Grills, Seafood and Fish, Vegetarians, and Pasta, Rice and Curries
- Each dish shows the original price struck through next to the current price (in Ksh)
- Inline SVG icons for section headings and value cards
- Lazy-loaded images for faster page loads
- Contact form with name, optional phone, email, topic and message fields
- Opening hours listed by day

## Tech Stack

- HTML5
- CSS3 (one stylesheet per page)
- No JavaScript (for now)

## Project Structure

```
.
├── README.md
├── landing_page.html
├── about_page.html
├── contacts_page.html
└── static/
    ├── css/
    │   ├── landing_page.css
    │   ├── about_page.css
    │   └── contacts_page.css
    └── images/
        ├── favicon.svg
        ├── img1.jpg ... img8.jpg
        └── (dish photos, e.g. ribeye_steak.jpg, mahamri.jpg, ...)
```

## Running Locally

No build step or installs are needed. Just run the project with the **Live Server** extension in VS Code:

1. Open the project folder in VS Code (the folder that contains `landing_page.html` and `static/`).
2. Right-click `landing_page.html` and choose **Open with Live Server** (or click **Go Live** in the status bar).
3. The site opens in your browser and reloads automatically when you save changes.

The pages reference assets with root-relative paths such as `/static/css/...`, so open the project folder itself as the VS Code workspace. Opening the HTML files directly by double-clicking them will not load the styles or images.

## Future Improvements

- Add JavaScript for contact form validation and submission
- Add an online table reservation flow
- Add a hamburger menu for small screens

## Credits

&copy; 2026 Savannah Spoon Inn. Built as a personal learning project.