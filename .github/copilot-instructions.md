# Copilot Instructions for Food_Galleria

## Project Overview
- **Food_Galleria** is a simple, static HTML project showcasing favorite foods.
- The main entry point is `Home.html`.
- There are no build steps, frameworks, or external dependencies currently present.

## File Structure
- `Home.html`: Main HTML file for the homepage. Contains inline CSS and navigation sections.
- `README.md`: Brief project description.
- `LICENSE`: MIT License.

## Patterns & Conventions
- Inline CSS is used within the `<style>` tag in the HTML `<head>`.
- Navigation is implemented as a series of `<p>` elements with color styling.
- No JavaScript, backend, or asset folders are present as of this version.

## Developer Workflows
- No build, test, or deployment scripts are defined. All changes are made directly to HTML.
- To preview changes, open `Home.html` in a web browser.

## Extending the Project
- To add new pages, create additional `.html` files and link them via navigation.
- For styling, continue using inline CSS or consider extracting to a separate `.css` file if the project grows.
- If adding scripts or assets, create appropriate folders (e.g., `js/`, `css/`, `images/`).

## Example: Adding a New Recipe Page
1. Create `Recipes.html` in the root directory.
2. Add a navigation link in `Home.html`:
   ```html
   <a href="Recipes.html">RECIPES</a>
   ```
3. Follow the same inline CSS pattern or link to a shared stylesheet.

## Key Files
- `Home.html`: Main content and navigation structure.
- `README.md`: Project intent and summary.

---

*Update this file if you introduce new workflows, dependencies, or architectural changes.*
