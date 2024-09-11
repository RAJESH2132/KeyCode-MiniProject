# Event Key Codes

This is a simple mini-project demonstrating how to handle keyboard events in a web application. When a user presses any key, the application displays the key pressed, the corresponding key code, and the key's code name.

## Features

- **Key Press Detection**: Displays the key pressed by the user.
- **Key Code**: Shows the numerical code corresponding to the key.
- **Key Name**: Provides the code name of the key pressed.

## Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Basic styling to enhance the appearance.
- **JavaScript**: Core logic for event handling and dynamic content updates.

## How It Works

1. The project listens for the `keydown` event on the `window` object.
2. When a key is pressed, it captures the event and displays:
   - The `key` (character of the key pressed).
   - The `keyCode` (numerical value of the key).
   - The `code` (physical key on the keyboard).

## Usage

Simply open the `index.html` file in a web browser and press any key on your keyboard. The information about the key will be displayed on the screen.

## Example

When you press the "A" key:

- **Key Pressed**: A
- **Key Code**: 65
- **Code**: KeyA

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/RAJESH2132/KeyCode-MiniProject.git
   ```
2. Navigate to the project directory:
   ```bash
   cd event-key-codes
   ```
3. Open `index.html` in your preferred web browser.
