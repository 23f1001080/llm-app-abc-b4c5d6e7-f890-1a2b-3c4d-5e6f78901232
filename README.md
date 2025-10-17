# Simple HTML Page with highlight.js

## Project Title and Description
This project presents a basic static HTML web page. Its primary purpose is to display a main title, "I am proud of india", which is styled using the `highlight.js` library, and a list of three Indian states in separate paragraphs. It serves as a minimal example demonstrating the integration of `highlight.js` for applying code-like styling to specific text elements.

## Setup Instructions
This is a static HTML page and does not require any server-side setup or complex build processes.
1.  Save the provided `index.html` file to your local machine.
2.  Open the `index.html` file directly in any modern web browser (e.g., Chrome, Firefox, Edge, Safari).

## Usage Guide
Upon opening the `index.html` file in your browser, you will see:
-   A prominent title "I am proud of india" centered at the top of the page. This title will have a distinct background color and font styling applied by the `highlight.js` library, making it stand out like a code snippet.
-   Below the title, three separate paragraphs will list the names of Indian states: "Maharashtra", "Tamil Nadu", and "Rajasthan".

## Code Explanation
-   **`index.html`**:
    -   This is the sole HTML file that structures the web page.
    -   It includes a standard HTML5 boilerplate with a `<head>` and `<body>` section.
    -   The `<title>` tag is now set to "I am proud of india", reflecting the updated project title.
    -   It links to the `highlight.js` CSS theme (`github.min.css`) from a CDN in the `<head>` section, providing the styling for the highlighted text.
    -   A `<style>` block is included for basic body, heading, and paragraph styling. It also contains specific CSS to ensure the `highlight.js` styled `<code>` block within the `<h1>` element looks appropriate as a title.
    -   The main title, "I am proud of india", is wrapped within a `<code>` tag inside an `<h1>` tag, with the class `language-plaintext`. This tells `highlight.js` to treat it as plain text and apply its code highlighting styles.
    -   Three `<p>` tags contain the names of the Indian states.
    -   At the end of the `<body>`, the `highlight.js` JavaScript library (`highlight.min.js`) is loaded from a CDN.
    -   A `<script>` block immediately follows to call `hljs.highlightAll()`, which initializes `highlight.js` and applies the chosen theme's styling to all detected code blocks on the page, including our title.

## License Information
This project is licensed under the MIT License.
