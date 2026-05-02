# 🐾 Pumpkin's Purrfect Meme Picker

A fun, interactive web application designed to serve up the perfect cat meme based on your current mood. Built with pure Vanilla JavaScript, HTML, and CSS, this project showcases foundational DOM manipulation, event handling, and conditional rendering techniques.
## 📸 Screenshots
<img width="1907" height="918" alt="Capture d&#39;écran 2026-05-02 031003" src="https://github.com/user-attachments/assets/9ea60cf6-5f0e-4556-8aac-ec412dc4f7b5" />
<img width="1901" height="914" alt="Capture d&#39;écran 2026-05-02 031011" src="https://github.com/user-attachments/assets/2b2b4ee0-568b-4dde-ae35-7316fddb195e" />
<img width="1906" height="917" alt="Capture d&#39;écran 2026-05-02 031019" src="https://github.com/user-attachments/assets/d87ad289-731b-4653-8e7d-56ee640129e8" />


## ✨ Core Features

*   **Dynamic Emotion Rendering:** The application dynamically generates radio buttons based on an array of emotions (e.g., moody, insomniac, confused, sad, dominant, happy, relaxed, hungry, scared) pulled from a local data structure.
*   **Targeted State Management:** Tracks the user's selected emotion and updates the UI to reflect the active choice.
*   **GIF Filtering Toggle:** Includes a checkbox option allowing users to strictly filter results to only display animated GIFs.
*   **Randomized Selection Logic:** If multiple memes match the user's criteria (emotion + GIF preference), the application utilizes mathematical randomization (`Math.random()`) to ensure a fresh, unpredictable result each time the "Get Image" button is clicked.
*   **Custom Modal Display:** Presents the resulting meme in a clean, overlay modal window that dims the background, focusing attention on the image. Includes a functional close button (`X`) to return to the selection screen.

## 🛠️ Technologies Used

*   **HTML5:** Semantic structure for the interface and modal elements.
*   **CSS3:** Styling for layout, typography, radio button customization, and the modal overlay effects.
*   **Vanilla JavaScript (ES6+):** Handling the core logic, including rendering the input options, processing user clicks, filtering the data array, generating random selections, and manipulating the DOM to show/hide the modal.

