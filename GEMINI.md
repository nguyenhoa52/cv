# Project Overview

A static personal CV/portfolio website for **Hoa**, an Appian and Web Developer. The project showcases skills, experience, and hobbies using a clean, CSS-styled interface.

## Core Technologies
- **HTML5**: Structural markup for multiple pages (`index.html`, `hobbies.html`, `contact-me.html`).
- **CSS3**: Layout and styling, primarily located in `css/style.css`.
- **Google Fonts**: Uses 'Merriweather', 'Montserrat', and 'Sacramento'.

## Project Structure
- `index.html`: The main landing page featuring a profile, skills, and contact section.
- `css/`:
    - `style.css`: The primary stylesheet for `index.html`, implementing a modern, centered layout with custom button styles.
    - `styles.css`: A simpler stylesheet used by secondary pages like `hobbies.html`.
- `images/`: Contains all visual assets including clouds, mountains, and profile pictures.
- `HTML_Lesson/`: A sub-directory containing earlier or tutorial-based versions of the project files.
- `index_plainHtml.html`: A version of the main page without advanced styling.

## Building and Running
As a static website, there is no build process or server-side dependency.

- **To View**: Open `index.html` in any modern web browser.
- **Development**: Edit HTML and CSS files directly. Changes will be reflected upon browser refresh.

## Development Conventions
- **Vanilla Approach**: The project strictly uses standard HTML and CSS without frameworks (like Bootstrap) or preprocessors (like Sass).
- **Asset Management**: Images are stored locally in the `images/` folder.
- **Responsive Design**: Some basic responsiveness is handled via percentage-based widths (e.g., `.skill-row`, `.contact-msg`).
- **Styling**: Prefer using `css/style.css` for new features to maintain consistency with the main landing page.
