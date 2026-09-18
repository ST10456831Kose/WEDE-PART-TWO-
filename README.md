# WEDE-PART-TWO- ## Changelog - Part 1 Feedback

### 1. HTML Structure & Semantics
*   **Feedback:** "HTML structure has minor errors/inconsistencies."
*   **Action Taken:** I fixed broken paragraph `<p>` tags in the Home and Services sections. I removed unnecessary closing tags in the product cards. I also replaced empty `alt=""` attributes on all images with descriptive text (e.g., `alt="Voluminous Cateye lash extensions"`).

### 2. Navigation Clarity
*   **Feedback:** "Navigation is functional but the menu may lack clarity."
*   **Action Taken:** I added CSS `padding` and a `:hover` background color to the navigation links in `style.css` to make them look more like clickable buttons and improve the user experience.

### 3. Content & Structure Fixes
*   **Feedback:** "Content is sufficient but could be improved."
*   **Action Taken:** I restructured the About Us section into an unordered list (`<ul>`) to make the information easier to read. I also fixed the Workshop section by properly nesting the workshop info inside the `workshop-container` div.

### 4. Code Comments
*   **Feedback:** "Comments made, but not enough for code clarity."
*   **Action Taken:** I ensured all major HTML sections have clear comments (e.g., `<!-- ===== HEADER ===== -->`) and added descriptive comments in the CSS to explain what each style block does.
*   ### 6. Navigation & Button Functionality Fixes
*   **Feedback:** Navigation "may lack clarity" and buttons felt unresponsive.
*   **Action Taken:** I changed the `<section id="Services">` to `<section id="products">` so the "Products" navigation link scrolls to the correct section. I also updated all product "Enquire" buttons to use `mailto:` links, so they now open the user's email client with the product name pre-filled in the subject line.
