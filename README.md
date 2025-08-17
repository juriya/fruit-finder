# Fruits Search

Fruits Search is a simple React-based web application that allows users to search for different fruits by name. As you type in the search box, the app fetches matching fruit names from an external API and displays them in real-time.

## Features

- **Live Search:** Type in the search box to instantly see matching fruits.
- **Debounced Requests:** The app waits for you to finish typing before searching, reducing unnecessary API calls.
- **Clean UI:** Simple and responsive design for easy use.

## How It Works

1. Enter a fruit name (or part of it) in the search box.
2. The app waits briefly (700ms) after you stop typing, then sends a request to the fruit API.
3. Matching fruit names are displayed below the search box.
4. If no matches are found, a "No results found" message appears.

## Local Setup

To run the project locally:

1. **Clone or Download the Repository**

   Download the project files to your computer.

2. **Open the Project Folder**

   Open the folder in [Visual Studio Code](https://code.visualstudio.com/) or your preferred editor.

3. **Start a Local Server**

   You can use any static server. Here are two simple options:

   - **Using VS Code Live Server Extension:**

     - Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).
     - Right-click on `index.html` and select "Open with Live Server".

   - **Using Python (if installed):**
     - Open a terminal in the project folder.
     - Run:
       ```
       python -m http.server
       ```
     - Open `http://localhost:8000` in your browser.

4. **Open the App in Your Browser**

   Navigate to `index.html` in your browser. You should see the Fruits Search interface.

## File Structure

- [`index.html`](index.html): Main HTML file, loads React and the app.
- [`index.jsx`](index.jsx): React component for the fruit search functionality.
- [`styles.css`](styles.css): Styles for the app.

## Dependencies

- [React](https://react.dev/) and [ReactDOM](https://react.dev/) (loaded via CDN)
- [Babel Standalone](https://babeljs.io/docs/babel-standalone/) for JSX support in the browser

## API Used

- [Fruit Search API](https://fruit-search.freecodecamp.rocks/api/fruits?q=)

## License

This project is for educational purposes only and is not officially licensed. Please use and modify the code as needed for learning or personal projects.
