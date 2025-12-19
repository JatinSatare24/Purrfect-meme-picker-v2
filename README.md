# 🐈 Purrfect Meme Picker

A logical, filter-based web application designed to find the exact cat meme to match your current mood. This project was built to master **JavaScript Array Methods**, **Dynamic DOM Updates**, and **Radio Input handling**.

---

## 🚀 Key Features

* **Mood Discovery:** Dynamically generates a list of unique mood categories from a data set.
* **Animated Only Mode:** A functional toggle to filter results specifically for GIFs.
* **Modal Overlay:** A custom-built UI component to spotlight the "Purrfect" meme.
* **Responsive Layout:** Uses CSS Flexbox to ensure cat memes look great on any screen size.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic structure with a focus on form inputs and accessibility.
* **CSS3:** Custom styling using the **BEM (Block Element Modifier)** naming convention and Flexbox.
* **JavaScript (ES6+):**
    * `.filter()` & `.includes()` for the search engine.
    * `for...of` loops to iterate through data.
    * `classList.toggle` for UI state changes.
    * Template Literals for dynamic HTML injection.
      
---

## 🧠 Technical Deep Dive

During the building of this "Machine," I solved several core logic puzzles:

1.  **The Unique Category Logic:** Rather than hard-coding moods, the app scans the entire data object and extracts only unique tags to build the radio buttons.
2.  **Data Attributes:** Leveraged `data-` attributes to create a clean bridge between the HTML UI and the JavaScript logic.
3.  **Conditional Rendering:** Managed the logic to handle "Animated vs. Static" image display based on user preference.

---

## 🔧 Installation & Usage

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/purrfect-meme-picker.git](https://github.com/YOUR_USERNAME/purrfect-meme-picker.git)
