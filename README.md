# My Portfolio Node

This project is a Node.js application that serves a portfolio website. It utilizes Express to handle server requests and serves static files from the public directory.

## Project Structure

```
my-portfolio-node
├── src
│   ├── server.js          # Entry point of the Node.js application
│   └── routes
│       └── index.js       # Defines application routes
├── public
│   ├── index.html         # Main HTML structure of the portfolio website
│   ├── css
│   │   └── styles.css     # CSS styles for the portfolio website
│   └── js
│       └── main.js        # JavaScript code for client-side functionality
├── package.json            # Configuration file for npm
└── README.md               # Documentation for the project
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd my-portfolio-node
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Run the application:**
   ```
   npm start
   ```

4. **Access the portfolio website:**
   Open your browser and navigate to `http://localhost:3000`.

## Usage Guidelines

- The application serves static files from the `public` directory.
- You can modify the `public/index.html`, `public/css/styles.css`, and `public/js/main.js` files to update the portfolio content and styles.
- The server is configured to listen on port 3000 by default. You can change this in `src/server.js`.

## License

This project is licensed under the MIT License.