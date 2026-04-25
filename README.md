# K5 Games

This repository contains the source code for the K5 Games website, a platform for educational games featuring English, Bilingual, and Buddhist themes.

## Project Overview
K5 Games is designed to be a lightweight, responsive, and accessible gaming hub. It utilizes a mobile-first design approach to ensure compatibility across a wide range of devices.

## Tech Stack
- **Frontend:** HTML5, CSS3
- **Framework:** [Bootstrap 5](https://getbootstrap.com/)
- **Styling:** Custom CSS with CSS Variables for theme management and complex media queries for responsive layout handling.

## Project Structure
- `/index.html` - The main entry point and home page.
- `/assets/` - Directory for images, icons (GitHub, LinkedIn), and logos.
- `/css/styles.css` - Global and component-specific styles, including custom animations and theme colors.
- `/includes/header.html` - The navigation component shared across the site.
- `/pages/` - Contains content pages such as About, Donate, and specific game categories.

## Local Development
To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/codexmon/k5games.git
   ```
2. **Run a Local Server**:
   Since the project uses absolute and relative paths within various directories, it is recommended to use a local development server.
   - **VS Code:** Use the "Live Server" extension.
   - **Python:** Run `python3 -m http.server` in the root directory.
   - **Node.js:** Use `npx serve`.

## Key Features
- **Responsive Navigation:** A Bootstrap navbar that transitions to an absolute-positioned overlay on mobile to prevent layout shifts.
- **Theming:** Centralized color management using CSS variables located in the `:root` of `styles.css`.
- **Hero Animations:** Custom keyframe animations (`senses`) for the landing page greeting.

## Credits
- **Lead Developer/Designer:** Gloria Ng
- **Portfolio:** arts.gloriang.com
