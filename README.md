# Product Catalog with Filters & Search 🚀

This is a front-end college project that demonstrates a responsive product catalog page built with vanilla HTML, CSS, and JavaScript. It features dynamic product rendering, multi-filter functionality, sorting, and a dark/light theme.

![Product Catalog Project Screenshot]
![Uploading Catalog.png…]()

---

## ✨ Features

-   **Dynamic Product Rendering**: Products are rendered dynamically from a JavaScript array, making the catalog easy to update.
-   **Search Functionality**: A debounced search bar to filter products by name in real-time without overwhelming the browser.
-   **Multi-Filter System**: Users can combine filters to narrow down results:
    -   Filter by **Category**
    -   Filter by **Price Range**
    -   Filter by **Availability** (In stock / Out of stock)
-   **Sorting Options**: Sort the filtered products by:
    -   Price (Low to High)
    -   Price (High to Low)
    -   Name (A to Z)
-   **Responsive Design**: A mobile-first design that adapts to all screen sizes using CSS Flexbox and Grid.
-   **Dark & Light Mode**: A theme toggle that saves the user's preference in their browser's `localStorage`.
-   **Product Detail Pages**: Each product card links to its own dedicated detail page.
-   **User Feedback**: "Added to Cart" toast notifications provide instant feedback on product pages.

---

## 🔧 Technologies Used

-   **HTML5**: For the structure and semantic markup of the web pages.
-   **CSS3**: For all styling, including:
    -   CSS Custom Properties (Variables) for easy theming (light/dark modes).
    -   Flexbox and Grid for responsive layouts.
    -   Modern, clean design with smooth transitions.
-   **JavaScript (ES6+)**: For all dynamic functionality:
    -   DOM Manipulation
    -   Event Handling
    -   Implementing search, filter, and sort logic.

---

## ⚙️ Getting Started

This is a static front-end project. No build tools or dependencies are required.

### Prerequisites

You only need a modern web browser (like Google Chrome, Firefox, or Microsoft Edge).

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd YOUR_REPOSITORY_NAME
    ```
3.  **Open the main file:**
    Simply open the `Catalog.html` file in your web browser to view the project.

    > **Tip:** For the best experience, you can use a live server extension in your code editor (like "Live Server" for VS Code) to automatically reload the page when you make changes.

---

## 📁 Project Structure

The project uses a flat file structure for simplicity. All HTML files, along with the product images, must be in the same root directory for the links and images to work correctly.

/
├── Catalog.html            # The main product catalog page
├── classic-t-shirt.html    # Example product detail page
├── comfy-sneakers.html     # Example product detail page
├── ... (other product detail pages)
|
├── Classic T shirt.jpg     # Example product image
├── Comfy sneakers.jpg      # Example product image
└── ... (other product images)

---

## Acknowledgements

-   This was built as a project for my college coursework.
-   Placeholder images and dummy data were used for demonstration purposes.
