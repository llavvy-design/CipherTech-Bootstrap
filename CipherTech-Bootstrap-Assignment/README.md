# CipherTech — Creative Technology Learning Hub

**A customized BootstrapMade Mentor template demonstrating responsive layout, learning cards and a Bootstrap carousel.**

> **Project status: Educational practice project.** CipherTech is a fictional technology-learning hub customized for a web development assignment. It is a static frontend demonstration, not a production learning platform. It does not include working enrolment, user accounts, payment processing, or a database.

## What this project demonstrates

- Starting from and customizing the **Mentor** education template by BootstrapMade.
- Bootstrap 5 layout utilities, containers, rows, columns, cards and responsive breakpoints.
- A Bootstrap carousel containing six fictional learning-path cards in two slides.
- Automatic carousel movement every three seconds, Previous/Next buttons, slide indicators and pause-on-hover behavior.
- Custom CSS design tokens using warm cream, forest green, muted orange, sage and lilac.
- Responsive navigation, course content, supporting pages and a consistent visual identity.
- Git and GitHub project versioning.

## Main learning paths shown

1. Web Development
2. Python & Data Science
3. Cybersecurity & Networks
4. AI & Machine Learning
5. Cloud & DevOps
6. UI/UX & Creative Technology

These programs, descriptions and durations are fictional examples used to populate the design. They are not real courses or promises of enrolment.

## Project structure

```text
CipherTech-Bootstrap-Assignment/
├── index.html
├── about.html
├── courses.html
├── course-details.html
├── trainers.html
├── events.html
├── pricing.html
├── contact.html
├── starter-page.html
├── assets/
│   ├── css/
│   │   ├── main.css
│   │   └── ciphertech-custom.css
│   ├── js/
│   ├── img/
│   └── vendor/
└── README.md
```

## Run locally

1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Start `index.html` with Live Server, or open it directly in a browser.
4. Open **Learning Paths** from the navigation to test the carousel.
5. Use the Previous/Next arrows or slide indicators; leave the carousel untouched to verify automatic movement.

Bootstrap's CSS and JavaScript are included locally in `assets/vendor/`, so the carousel does not depend on a remote Bootstrap CDN. Google Fonts require an internet connection.

## How the carousel works

The carousel is in `courses.html` and is also featured on `index.html`. It uses Bootstrap's `carousel`, `carousel-inner`, `carousel-item` and `active` classes. Each slide contains a Bootstrap grid row with three cards at larger breakpoints. The `data-bs-ride="carousel"` and `data-bs-interval="3000"` attributes enable automatic cycling. The previous and next buttons and slide indicators point to the carousel ID `learningPathCarousel`.

The Bootstrap bundle is loaded near the end of each page from:

```html
<script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
```

The bundle includes the JavaScript needed to operate the carousel.

## Limitations

- This is a static frontend project.
- The registration/contact and newsletter experiences are not connected to a live backend. Some template forms may require PHP/server-side setup before they can submit data.
- No user records are stored, no accounts are created, and no real course enrolment or payment occurs.
- Some supplied template pages and images are retained as a base for the assignment and have been rebranded or selectively customized. Mentor profiles, event descriptions, sample participation options and statistics are fictional demonstration content.
- A few stock images and template components originate from the starting template; this repository preserves the required BootstrapMade credit.

Do not use the sample forms to submit sensitive information.

## Attribution and license

This project is derived from **Mentor**, an education website template by [BootstrapMade](https://bootstrapmade.com/mentor-free-education-bootstrap-theme/). The BootstrapMade template credit and links have been retained in the page footer. Review the [BootstrapMade license](https://bootstrapmade.com/license/) for the terms that apply to redistribution and publication of the template files.

Bootstrap and Bootstrap Icons are included in the provided vendor assets. This is a student learning project and is not affiliated with or endorsed by BootstrapMade.

## Learning goals

The goal is to practise modifying an existing template, understanding Bootstrap's layout system, implementing a carousel from existing card content, maintaining clear project structure and sharing source code through GitHub.

**Learn by doing. Stay curious. Keep building.** ✳
