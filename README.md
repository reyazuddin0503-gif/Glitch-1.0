# 🌿 Fast Fashion Alternative Finder

## Project Overview

This is a simple web app designed to help users find eco-friendly clothing alternatives to fast fashion.  
Users can enter the name of a clothing item (e.g., jeans, jacket, t-shirt), and the app suggests local thrift stores, repair shops, or ethical brands where they can find sustainable options.

---

## Features

- User-friendly input box to enter any clothing item.
- Hardcoded list of 6 eco-friendly alternatives including thrift stores, repair shops, and ethical brands.
- Displays matching alternatives with details like name, type, location, and website link (if available).
- Responsive design works well on both desktop and mobile devices.

---

## How to Use

1. Open the `index.html` file in a web browser (e.g., Chrome, Firefox).  
2. Type a clothing item in the input box (for example: `jeans`, `jackets`, `t-shirts`).  
3. Click the **Find Alternatives** button.  
4. The app will display a list of eco-friendly stores or brands where you can find alternatives to fast fashion items.

---

## Technologies Used

- **HTML5** — For the page structure and elements.  
- **CSS3** — For styling and responsive design.  
- **JavaScript** — To handle user input, filter data, and dynamically display results.

---

## Code Explanation

- The list of eco-friendly alternatives is **hardcoded** inside the JavaScript as an array of objects, each containing:
  - `name` — Store or brand name  
  - `type` — Category (Thrift Store, Repair Shop, Ethical Brand)  
  - `location` — Physical location (optional)  
  - `website` — Website URL (optional)  
  - `items` — Array of clothing items available at that store

- When the user clicks **Find Alternatives**, the script:
  - Reads the input text.
  - Converts it to lowercase and trims whitespace.
  - Filters the list to find matches for the entered item.
  - Displays results dynamically in the page.
  - Shows a friendly message if no matches are found or if input is empty.

---

## Future Improvements

- Replace the hardcoded data with a real database or API.
- Add location-based filtering using maps or GPS.
- Allow users to add reviews or ratings for stores.
- Improve UI/UX with better styling and animations.

---

## How to Run Locally

1. Clone or download this repository.  
2. Open the `index.html` file in any modern web browser.  
3. No server setup or installation required.

---

## Author

MD REYAZUDDIN ANSARI
reyazuddin05.03@gmail.com

---

## License

This project is open-source and free to use under the MIT License.
