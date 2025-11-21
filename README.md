# Red Dead Redemption Fan Page (HTML/CSS)

This is a fan-made landing page and login screen dedicated to the critically acclaimed **Red Dead Redemption** series, built using plain HTML and CSS. It showcases key characters, game information, and trailers in a thematic dark-mode design.

---

## ✨ Features

* **Responsive Navigation Bar:** Features the Rockstar Games logo, the Red Dead Redemption title logo, and navigation buttons ("Support," "Buy Now," and "Log in").
* **Cinematic Banner:** A prominent image banner with an overlayed **Rating Box** displaying critic scores (Steam, IGN, Metacritic).
* **Character Introductions:** Detailed, side-by-side sections for the two main protagonists, **John Marston** and **Arthur Morgan**, complete with images and descriptive text.
* **Media Gallery:** A section for embedding two video trailers.
* **Separate Login Page (`log-in.html`):** A dedicated, styled login form for user authentication, linked from the main navigation.
* **Responsive Design:** Utilizes CSS media queries to ensure the layout is optimized and readable on various screen sizes, including mobile devices.

---

## 📁 File Structure

The project is organized into the following core files:

| File Name | Description |
| :--- | :--- |
| **`base.html`** | Main landing page for the Red Dead Redemption series. |
| **`log-in.html`** | Separate page containing the user login form. |
| **`site.css`** | Global styling rules for the main landing page, including navigation and responsiveness. |
| **`login.css`** | Specific styling rules for the `log-in.html` page. |
| **Image/Video Assets** | Includes files for the main banner, character photos, and embedded video trailers (e.g., `rdr_banner_upscalled.jpeg`, `jon marston.jpg`, `v1.mp4`). |

---

## 💻 Technology Used

* **HTML5:** Used for page structure and content.
* **CSS3:** Used for all styling, layout, and responsive design.

---

## 🎨 Styling Highlights

* **Dark Theme:** The design employs a dark background (`#111`) with white text and themed accent colors (e.g., gold `#ffaa00` and red `#d10000`) for a cinematic, western feel.
* **Layouts:** Flexbox is extensively used in `site.css` for aligning elements like the navigation bar and the character rows.
* **Login Form:** The form is centered and contained within a dark background box (`#0c0c0c`), with the submit button styled in a distinct red color (`#d10000`).
* **Responsiveness:** Media queries in both `site.css` and `login.css` ensure the site adapts well to smaller viewports, adjusting image sizes and stacking horizontal content.
