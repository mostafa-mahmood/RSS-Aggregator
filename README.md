# Gator 🐊

Gator is a command-line RSS aggregator that lets you collect, organize, and view articles from multiple RSS feeds. Built with Node.js & MongoDB, it stores feed data in MongoDB and offers an interactive CLI experience. Whether you're a news junkie or just want to streamline your reading, Gator’s got you covered.

![Gator Preview](./preview/vid.gif)

## Features
- **Manage RSS Feeds**: Input URLs to track your favorite sources.
- **Organize Articles**: Stores feed metadata (title, description, language) in MongoDB.
- **Interactive CLI**: Navigate options with a clean, styled interface.
- **Lightweight**: Simple setup, runs anywhere with Node.js.

## Prerequisites
Before installing Gator, ensure you have:
- **[Node.js](https://nodejs.org/)** (v16+ recommended) and **[npm](https://www.npmjs.com/)** installed.
- **[MongoDB](https://www.mongodb.com/)** running locally.

## Installation
Follow these steps to set up Gator and run it globally with the `gator` command:

```sh
# Clone the repository
git clone https://github.com/mostafa-mahmood/Gator.git
cd Gator

# Install dependencies
npm install

# Link the CLI tool globally
npm link
```

After installation, you can run Gator from anywhere in your terminal:

```sh
gator
```

## Usage
Gator provides an intuitive CLI experience to manage RSS feeds. Run the following command to start:

```sh
gator
```

### Available Commands
- **Add a Feed**: Enter an RSS feed URL to track.
- **List Feeds**: View all stored RSS sources.
- **Fetch Articles**: Retrieve and store the latest articles.
- **View Articles**: Display saved articles.
- **Remove a Feed**: Delete an RSS source from storage.
- **Exit**: Close the CLI.


## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## Issues
If you encounter any issues or have suggestions, open an issue on [GitHub](https://github.com/mostafa-mahmood/Gator/issues).
