# colorblockDAO_3D_City

This is a dynamic 3D virtual city project built with **Three.js**, inspired by the "**Colorblock DAO**" concept. It showcases a procedurally generated urban landscape that blends unique curved roads with futuristic architecture. This project aims to create an interactive digital space where users can explore a cyberpunk metropolis filled with randomly generated buildings, roads, and green spaces. We welcome contributions and further development.

The city's design rejects a rigid grid system in favor of a more fluid and organic layout, giving it a distinct and novel visual experience.

---

## Key Features

-   **Procedural Generation**: The city is built dynamically on page load, with a unique layout generated each time you refresh. This includes:
    -   **Non-Grid Road Network**: Main and secondary roads are designed with curves, avoiding a static grid layout.
    -   **Dynamic Building Placement**: Buildings are intelligently placed alongside roads with varying heights and a futuristic color scheme.
    -   **Special Landmarks**: Unique structures like a stadium and an administrative center are strategically placed to add visual interest.
-   **Overlap-Free Design**: The generation logic ensures that buildings do not overlap with each other or with the road network, creating a clean and cohesive urban environment.
-   **Interactive Exploration**: Users can navigate the city from a third-person perspective using mouse or touch controls to zoom, rotate, and pan.
-   **Object Information**: Clicking on any building, road, or landmark will display its name, type, and precise coordinates, allowing for deeper engagement with the digital world.

---

## Technologies Used

-   **Three.js**: The core library for creating and rendering the 3D scene.
-   **OrbitControls.js**: Provides intuitive camera controls for easy navigation.
-   **JavaScript**: The primary language for all procedural generation and interaction logic.
-   **HTML/CSS**: Used for structuring the web page and styling the information panels.

---

## How to Run

1.  **Clone the repository**:
    ```sh
    git clone [your-repository-url]
    ```
2.  **Navigate to the project directory**:
    ```sh
    cd [your-project-directory]
    ```
3.  **Open `index.html` in your browser**.
    -   No local server is required. The project runs directly from the HTML file.

---

## Future Enhancements

-   **First-Person Mode**: Implement `PointerLockControls` for a more immersive, ground-level exploration experience.
-   **More Architectural Variety**: Add more complex building geometries and diverse architectural styles.
-   **Day/Night Cycle**: Introduce dynamic lighting to simulate a day-night cycle.
-   **Performance Optimization**: Enhance rendering performance for larger and more complex cityscapes.


