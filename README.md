# The-BBQ-Place-Restaurant

## 👉 [Live Website](https://the-bbq-place-restaurant-website.netlify.app/)

A responsive multi-page restaurant website template built to practice CSS layout fundamentals, multi-page navigation, and mobile-responsive design patterns without a framework.

## What this demonstrates

- **Multi-page Architecture**: Developed a cohesive navigation structure across Home, About, Menu, and Contact pages with mobile-optimized state management.
- **Full-screen video background**: The home hero uses a muted, autoplaying, looping background video (`media/video/home-bg-video.mkv`) with overlaid content.
- **Responsive Navigation**: Implemented a consistent hamburger menu pattern using vanilla JavaScript to handle mobile state toggling across all pages.
- **Structured Content Layouts**: Utilized CSS Grid and Flexbox for modular design, specifically for menu item displays, testimonial cards, and featured delicacies.
- **Design System**: Implemented maintainable theming using CSS custom properties for color palettes and font stacks.
- **UX Enhancements**: Integrated responsive media queries (desktop-first) ranging from 1280px down to 576px.
- **Semantic Structure**: Built with semantic HTML5 and external icons via Font Awesome 6.1.1.

## Build/design decisions

| Decision | Reasoning |
| :--- | :--- |
| **Desktop-first CSS** | Structured initially for large screens with `max-width` breakpoint overrides in `media-query.css` for tablet and mobile responsiveness. |
| **Vanilla JS** | Used for navigation toggling to practice DOM manipulation without framework overhead. |
| **Modular CSS** | Separated core layout styles and specific media queries for better maintainability across multi-page templates. |

## What I'd do differently now

The current desktop-first approach using `max-width` breakpoints made managing responsive overrides across multiple sections complex. I would now implement a mobile-first approach using `min-width` breakpoints, which is more scalable and results in cleaner, more efficient CSS for smaller screens.

## Technologies Used

- **HTML5** (including the `<video>` element for the hero background)
- **CSS3** (Flexbox, Grid, CSS Custom Properties)
- **JavaScript** (Vanilla)
- **Fonts**: Google Fonts — Abril Fatface (display) & Poppins
- **Icons**: Font Awesome 6.1.1

## Pages & structure

```
the-bbq-place-restaurant/
├── index.html      # home — video hero, featured delicacies, testimonials
├── about.html      # about the restaurant
├── menu.html       # menu listing
├── contact.html    # contact page
├── css/
│   ├── style.css        # core layout & theming
│   └── media-query.css  # responsive overrides (desktop-first, 1280px → 576px)
├── js/
│   └── script.js   # mobile hamburger-nav toggle
└── media/
    └── video/
        └── home-bg-video.mkv   # hero background video
```

## Getting Started

1. **Clone the Repository**: Clone the repository to your local machine:
   ```bash
   git clone git@github.com:mahmud035/the-bbq-place-restaurant.git
   ```
2. **Open the Project**: Navigate to the project directory and open the files in your preferred code editor.

3. **Run the Project**: Open the `index.html` file in your browser to view the website.

## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.
