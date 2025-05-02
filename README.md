
# EJS Partials Project

This project demonstrates the use of **EJS Partials** with **Node.js** and **Express** to create a modular and reusable web application. It includes a home page, about page, and contact page, all styled with static assets.

## Features
- **EJS Partials**: Reusable header and footer components.
- **Static Files**: CSS and other assets served using Express.
- **Dynamic Routing**: Routes for home, about, and contact pages.

## Project Structure
```
4.3 EJS Partials/
├── index.js                # Main server file
├── views/
│   ├── index.ejs           # Home page
│   ├── about.ejs           # About page
│   ├── contact.ejs         # Contact page
│   └── partials/
│       ├── header.ejs      # Header partial
│       └── footer.ejs      # Footer partial
├── public/
│   ├── styles/             # CSS files
│   └── images/             # Static images
├── package.json            # Project metadata and dependencies
```

## Prerequisites
- Node.js installed on your machine.
- A package manager like `npm`.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```sh
   cd "c:/Users/PABLO/Desktop/Data Base/BACK- END/4.3+EJS+Partials/4.3 EJS Partials"
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Usage
1. Start the server:
   ```sh
   node index.js
   ```
2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Routes
- `/`: Home page
- `/about`: About page
- `/contact`: Contact page

## Dependencies
- **express**: Web framework for Node.js.
- **ejs**: Template engine for rendering dynamic HTML.

## Author
Nwogbo Prince Miracle Ebube
```

Save this content as `README.md` in your project directory. Let me know if you need further assistance!
