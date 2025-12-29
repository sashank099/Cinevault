# CINEVAULT

**Name:** Sashank Sekhar Sahoo
**Roll Number:** 125CH0027

CINEVAULT is a curated, interactive web directory showcasing legendary film directors and their masterpieces. The project features a dark-themed, responsive user interface with dynamic content loading and smart search functionality.

## 🔗 Live Demo
Check out the live version of the project here:
**[https://cinevault-directors.netlify.app/](https://cinevault-directors.netlify.app/)**

## 🌟 Features

* **Director Showcase:** A grid layout displaying cards for various directors (e.g., Christopher Nolan, Akira Kurosawa, Rajkumar Hirani) with their images and masterpiece counts.
* **Smart Search:** Filter directors not just by their **names**, but also by their **movies**. For example, searching for "Inception" will display Christopher Nolan's card.
* **Dynamic Details Page:** Clicking a director card loads a dedicated profile page (`director.html`) populated dynamically using URL parameters and JavaScript objects—eliminating the need for separate HTML files for each director.
* **Responsive Design:** Fully optimized for desktop and mobile devices.
* **Immersive UI:** * Custom CSS animations (`inAnimation`).
    * Hover effects on cards and images.
    * Dynamic background generation on detail pages using the director's image with a gradient overlay.

## 📚 Learning Sources

* **MDN Web Docs:** Used for understanding `URLSearchParams`, JavaScript DOM manipulation, and CSS Flexbox properties.
* **YouTube:** Referenced tutorials for building responsive card grids and implementing search filter logic.
* **AI Tools (Gemini):** Utilized for code debugging, optimizing the search algorithm, and generating project documentation.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure for the `index` and `director` pages.
* **CSS3:** Custom styling, Flexbox layouts, Media Queries for responsiveness, and CSS variables.
* **JavaScript (Vanilla):** DOM manipulation, URLSearchParam handling, and client-side data rendering.
* **FontAwesome:** Used for social media icons in the footer.

## 📂 Project Structure

To run this project correctly, ensure your file structure matches the references in the code:

```text
/project-root
│
├── index.html          # Main landing page with the search bar and grid
├── director.html       # Template page for individual director details
├── style.css           # Global stylesheets
├── script.js           # Data object and logic for search/rendering
└── assets/
    └── directorImg/    # Directory containing images (e.g., nolan.jpeg, hirani.jpeg)
