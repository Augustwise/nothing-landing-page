# Nothing Online Store

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Parcel](https://img.shields.io/badge/Parcel-E8AB2E?style=for-the-badge&logo=parcel&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![Stylelint](https://img.shields.io/badge/Stylelint-263238?style=for-the-badge&logo=stylelint&logoColor=white)

A responsive landing page for **Nothing**, a tech brand online store. The page presents recommended products (Phone (1), Ear (2), Ear (stick)), lets users browse product categories, and includes an "About Us" section and a contact form.

## Live Preview

Experience the live website: [Nothing Online Store Demo](https://augustwise.github.io/nothing-landing-page/)

## Design Reference

Figma design file: [Nothing Landing Page Design](https://https://www.figma.com/file/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?type=design&node-id=6802-139&t=L7eKz5YKLN0m5WxR-0)

## Technologies Used

**Core**
- HTML5 — semantic markup
- SCSS — styling with variables and mixins
- JavaScript — interactivity (mobile menu, etc.)

**Development & Deployment**
- Parcel (v2.12.0) — build tool
- ESLint (v8.57.0) — JS code quality
- Stylelint (v16.7.0) — SCSS code quality
- LintHTML (v0.9.6) — HTML code quality
- Prettier (v3.3.2) — code formatting
- GitHub Pages — hosting and deployment

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/Augustwise/nothing-landing-page.git
cd nothing-landing-page
```

2. Install dependencies:

```bash
npm install
```

3. Run the project locally:

```bash
npm start
```

4. Build the project for production:

```bash
npm run build
```

## Features

- **Responsive Design**: Adapted for mobile, tablet, and desktop screen sizes, with dedicated image sources for each breakpoint (`<picture>` / `srcset`).
- **Mobile Navigation**: Slide-out menu with a burger icon, accessible via `#menu` anchor.
- **Recommended Products**: Showcase section with product photo, title, description, and price.
- **Product Categories**: Grid of category cards (All products, Audio, Accessories) with hover images.
- **About Us**: Company mission and story section.
- **Contact Form**: Name, email, and message fields with client-side validation.
- **Sticky Header**: Top bar with logo, phone number, and menu icon.
