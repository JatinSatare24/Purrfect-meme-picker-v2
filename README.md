# 🐈 Purrfect Meme Picker: V2
This is the refined version of the Purrfect Meme Picker. V2 focuses on solidifying the **HTML/CSS/JS connection** and ensuring the code follows professional naming conventions and logical structures.
---

## 🚀 Refined Features

* **Logical Filtering:** Uses JavaScript to scan a data set and return specific memes based on user-selected moods.
* **BEM Methodology:** Styled using **Block-Element-Modifier** syntax to keep the CSS organized and prevent specificity issues.
* **Conditional Rendering:** A functional checkbox system that determines whether to display static images or animated GIFs.
* **Dynamic DOM Updates:** Uses template literals and JS logic to inject the "Purrfect" meme into the modal in real-time.

---

## 🛠️ The Technical "Machine"

### 1. The Structure (HTML)
* Used **Semantic HTML** to ensure the meme-picking interface is accessible and structured correctly.
* Leveraged **Data Attributes** to link the HTML radio inputs to the JavaScript logic.

### 2. The Style (CSS)
* Implemented the **Box Model** with `border-box` to ensure perfect layout alignment.
* Used **Flexbox** for a responsive, centered layout that works across different screen sizes.
* Followed **BEM naming** (e.g., `.meme-modal__inner`) for a flat and readable stylesheet.

### 3. The Logic (JavaScript)
* **Array Methods:** Used `.filter()` and `.includes()` to handle the search logic within the meme data.
* **Event Listeners:** Managed user interactions through clean, non-intrusive event handling.
* **Memory Management:** Handled data objects as **Reference Types** to ensure efficient processing in the Heap.

---

## 🧠 Why V2?
This version serves as a "Final Review" of the core frontend fundamentals—Logic, Layout, and Structure—before progressing into Asynchronous JS and API integration.
---

## 🔧 How to Run
1. Open `index.html` in any browser.
2. Choose a mood.
3. Click "Get Image" to see your meme!
