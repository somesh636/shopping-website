# Basic Shopping Application

This is a simple Node.js and Express website for shopping items.


## Getting Started

```bash
npm install
npm start
```

The server runs on port 3000.

There are three routes:

- http://localhost:3000/ - homepage
- http://localhost:3000/shop - shop items after logging in as a user.
- http://localhost:3000/basket - view all itmes in a basket for all user.


The server persists using a SQLite3 database named `database.sqlite` in the site root.

## Development

This project uses Editorconfig to standardise text editor configuration.

This project uses ESLint to detect suspicious code in Javascript files.

### Debugging

This project uses https://www.npmjs.com/package/debug for development logging. To start `nodemon` and enable logging:

```bash
npm run debug
```


