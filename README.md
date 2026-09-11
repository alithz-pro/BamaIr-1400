# Bama.ir — Front-End Recreation

A front-end recreation of the **Bama.ir** website, created as a web-development practice project while studying **Full-Stack Web Development** at **MFT (Mojtama Fanni Tehran / مجتمع فنی تهران)**.

The project was built to practice the fundamentals of:

* HTML
* CSS
* Bootstrap
* JavaScript
* Responsive web design
* DOM manipulation

## Live Preview

**[View the live preview](https://htmlpreview.github.io/?https://github.com/AliThz-Pro/BamaIr-1400/blob/main/index.html)**

> This project is an educational recreation of the website's interface and is not affiliated with Bama.ir.

## About the Project

As an early web-development exercise, I chose **Bama.ir**, an Iranian automotive marketplace, as the website to recreate.

The goal was not to build the complete functionality of Bama.ir, but to reproduce its front-end structure and visual style while learning the fundamentals of web development.

The project focuses on the first/main page and includes interactive elements implemented with JavaScript.

## Technologies

| Technology     | Purpose                             |
| -------------- | ----------------------------------- |
| **HTML**       | Page structure and content          |
| **CSS**        | Custom styling and layout           |
| **Bootstrap**  | Responsive layout and UI components |
| **JavaScript** | Interactivity and DOM manipulation  |

## Features

* Responsive page layout
* Navigation/header
* Automotive search interface
* Vehicle filtering sections
* Brand selection
* Vehicle body/chassis type selection
* Price-range selection
* Shortcut categories
* Interactive content panels
* Dynamic DOM manipulation
* Bootstrap-based responsive grid

## Interactive Filtering

One of the main JavaScript components is the filtering/showcase system.

The interface provides several categories that dynamically display their available options, including:

* Shortcuts
* Brands
* Chassis/body types
* Price ranges

For example, the brand section contains options such as Audi, MVM, Mercedes-Benz, Brilliance, BMW, Toyota, and Porsche.

The JavaScript dynamically creates the corresponding UI elements and inserts them into the page rather than relying entirely on pre-written HTML.

## JavaScript

The project uses vanilla JavaScript for client-side interactions and DOM manipulation.

The `ShowCase()` function acts as the main controller for the filtering interface and determines which section should be displayed.

Separate functions are used for different categories:

```text
ShowShortcutContent()
ShowBrandContent()
ShowChassisContent()
ShowPriceContent()
```

The project also dynamically creates HTML elements using JavaScript's DOM APIs, including containers, rows, cards, links, icons, and headings.

## Project Structure

```text
BamaIr-1400/
│
├── index.html
├── css/
│   └── ...
├── js/
│   └── ...
├── image/
│   └── ...
└── README.md
```

> The exact structure depends on the files included in the repository.

## Learning Goals

This project was created to practice the foundations of front-end web development, particularly:

### HTML

* Semantic page structure
* Forms and inputs
* Links
* Images
* Containers and sections

### CSS

* Layout
* Spacing
* Typography
* Styling
* Responsive behavior

### Bootstrap

* Grid system
* Responsive breakpoints
* Cards
* Utility classes
* Layout components

### JavaScript

* DOM selection
* DOM creation
* Event handling
* Dynamic content generation
* Conditional logic
* Functions
* Client-side interaction

## Background

This was one of my early web-development projects, created before modern AI-assisted development workflows were common.

It was developed as part of a **Full-Stack Web Development course at MFT (مجتمع فنی تهران)**, with the specific goal of practicing the fundamentals of HTML, CSS, Bootstrap, and JavaScript.

Rather than creating a generic exercise, I chose an existing real-world website as a reference and attempted to recreate its interface.

## Disclaimer

This is an educational project created for learning purposes.

**Bama.ir and its branding, content, and original design belong to their respective owners.**

This project is not affiliated with, endorsed by, or connected to Bama.ir.

## License

This project is intended for educational and personal portfolio purposes.
