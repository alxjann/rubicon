## 🚀 Features

* **Shape Creation**: Draw basic shapes like Lines, Rectangles, and Ellipses.
* **Text Tool**: Add and edit text on the canvas.
* **Image Imports**: Place raster images (PNG, GIF, JPG) into the drawing.
* **Select & Manipulate**: Select, move, and scale objects.
* **Undo/Redo**: Full undo/redo support implemented using the Command pattern.
* **Property Editor**: A dynamic side panel shows properties (color, fill, location, dimensions) for any selected shape.
* **Save & Open**: Save drawings to and open them from a custom XML format.

---

## 🏁 Getting Started

### Prerequisites

* Java JDK 17 or higher.
* Apache Maven

### Building the Project

1.  Clone the repository:
    ```sh
    git clone https://github.com/alxjann/rubicon.git
    ```
2.  Navigate to the project's root directory:
    ```sh
    cd rubicon
    ```
3.  Build the project using Maven:
    ```sh
    mvn clean install
    ```

### Running the Application

You can run the main drawing application directly from Maven using the `exec-maven-plugin` configured in the `draw` module:

```sh
mvn -pl draw exec:java
