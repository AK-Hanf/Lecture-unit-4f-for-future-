# Teaching Unit: 4f for Future

Interactive HTML learning materials for a teaching unit on **complex formation, colouration, and applications of lanthanoids**. This project was created as part of Aleksandar Lubinić's master's thesis.

## Contents

The repository contains a browser-based learning environment with no build process and no external JavaScript dependencies:

- **HSAB Concept** – exercises for classifying hard and soft acids and bases
- **Colouration** – interactive materials about the colouration of complex compounds and light absorption
- **Applications** – learning content about everyday and industrial applications of lanthanoids
- **Design System and Assets** – reusable design components, colour schemes, and UI examples
- **Thesis Data** – supplementary data and documents related to the master's thesis

The learning materials include:

- Interactive multiple-choice and sorting exercises
- Immediate feedback and progress indicators
- Light and dark themes
- German/English language switching in the extended version
- Accessible controls and responsive layouts for mobile devices

## Quick Start

Because the project consists of static HTML files, it can be opened directly in a web browser.

### Option 1: Open directly

Open `index.html` in a modern web browser and select the learning module you want to use.

### Option 2: Run a local web server

A local web server is recommended so that relative paths and browser features work reliably.

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## Project Structure

```text
.
├── index.html                         # Landing page / learning-module dashboard
├── HSAB Trainingseinheit 1.html       # HSAB training unit
├── assets.html                        # Design system and UI reference
├── Thesis Data/                       # Data and supplementary materials
├── docs                               # Documentation/deployment file
├── LICENSE                            # License information
└── README.md
```

Some learning modules are located within their respective module or documentation directories. Use the links on the landing page to open the available content.

## Technologies

- HTML5
- CSS3 with responsive layouts
- Vanilla JavaScript
- No package installation or build step required

## Customisation and Development

The learning modules are implemented as standalone HTML files. Content, exercises, and questions can be edited directly in the relevant files. For larger changes, reusable styles and components should be documented in the design system and in `assets.html`.

## License

See [`LICENSE`](LICENSE) for the applicable license terms.

## Usage Note

These materials are intended as interactive learning and teaching support. Before classroom use, review the subject content and adapt it to the target audience and relevant curriculum.
