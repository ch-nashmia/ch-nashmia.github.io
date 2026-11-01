# Nashmia Ch — Information Security Portfolio

Personal portfolio website for **Nashmia Ch**, a BS Information Security student
at the National University of Sciences and Technology (NUST).

## About the Project

This responsive portfolio presents:

- Information security coursework and areas of focus
- Technical skills in Linux, networking, programming, and security tools
- Practical projects and GitHub repositories
- Certifications and current learning goals
- Academic and professional contact information

## Features

- Responsive layout for laptops, tablets, and mobile devices
- Accessible navigation with skip links and keyboard-friendly controls
- Vanilla JavaScript interactions with Bootstrap utilities
- Reduced-motion support for users who prefer less animation
- Portfolio project cards with responsive artwork
- Contact links for GitHub, LinkedIn, and email
- Off-white paper design with cobalt, tomato, and sunflower accents

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Bootstrap
- SVG illustrations
- Google Fonts

## Project Structure

```text
.
├── assets/                 # Profile image and project illustrations
├── css/
│   ├── style.css           # Custom responsive styles
│   └── vendor/             # Bootstrap CSS
├── js/
│   ├── main.js             # Portfolio interactions
│   └── vendor/             # Bootstrap JavaScript
├── index.html              # Main portfolio page
├── projects.html           # Project listing page
└── commissions.html        # Additional portfolio page
```

## Running Locally

The site is made with static files, so no build process is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/ch-nashmia/ch-nashmia.github.io.git
   ```

2. Open `index.html` in a browser.

For the best local experience, serve the folder with a simple local server:

```bash
python -m http.server
```

Then visit `http://localhost:8000`.

## Customization

The main design tokens are defined at the top of
[`css/style.css`](css/style.css). You can update:

- Colors
- Fonts
- Border thickness
- Card shadows
- Corner radii
- Container width

Project links and portfolio content are maintained in [`index.html`](index.html).

## Contact

- **GitHub:** [ch-nashmia](https://github.com/ch-nashmia)
- **LinkedIn:** [Nashmia Ch](https://www.linkedin.com/in/nashmia-ch-552307320/)
- **Email:** [chnashmia613@gmail.com](mailto:chnashmia613@gmail.com)

## License

This portfolio is intended for personal use. Please do not reuse personal
images, identifying information, or project content without permission.
