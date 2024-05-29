# Gravitational Slingshot Effect Simulation

![Gravitational Slingshot](https://example.com/path-to-your-image.jpg) <!-- You can add a relevant image or screenshot of your simulation here -->

## Overview

This project is a simulation of the gravitational slingshot effect using Pygame. It demonstrates how a spacecraft can gain speed and change direction by passing near a planet, using the gravitational pull of the planet.

## Features

- **Real-time Simulation**: Visualize the gravitational slingshot effect in real-time.
- **Interactive**: Click to launch a spacecraft and observe its trajectory influenced by the planet's gravity.
- **Customizable**: Easily change parameters like planet mass, spacecraft mass, gravitational constant, etc.

## Technologies Used

- **Python**: Programming language used for the simulation.
- **Pygame**: Library used for creating the graphical interface and handling the simulation.

## Installation

Follow these steps to run the project locally:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/gravitational-slingshot-simulation.git
    cd gravitational-slingshot-simulation
    ```

2. **Install dependencies**:
    Make sure you have Python and Pygame installed. If not, install Pygame using pip:
    ```sh
    pip install pygame
    ```

3. **Run the simulation**:
    ```sh
    python main.py
    ```

## Usage

- **Launch a Spacecraft**: Click on the screen to set the initial position, then click again to set the initial velocity and launch the spacecraft.
- **Observe Trajectories**: Watch how the spacecraft's trajectory changes as it passes near the planet.

## Code Explanation

- **Planet Class**: Represents the planet with attributes for position and mass, and a method to draw the planet.
- **Spacecraft Class**: Represents the spacecraft with attributes for position, velocity, and mass, and methods to move and draw the spacecraft.
- **create_ship Function**: Creates a spacecraft object based on the initial position and mouse click for velocity.
- **main Function**: Handles the main game loop, event handling, and drawing/updating all objects.

## Customization

You can customize various parameters in the code:

- **PLANET_MASS**: Mass of the planet.
- **SHIP_MASS**: Mass of the spacecraft.
- **G**: Gravitational constant.
- **FPS**: Frames per second for the simulation.
- **PLANET_SIZE**: Size of the planet.
- **OBJ_SIZE**: Size of the spacecraft.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Built with ❤️ using Pygame.
- Thanks to the Pygame community for providing tutorials and support.

## Contact

For any inquiries or feedback, please reach out to [your-email@example.com](mailto:your-email@example.com).

