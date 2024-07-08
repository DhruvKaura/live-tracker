

# Live Tracker

This project sets up a live tracking application using Node.js, Express, EJS, and Socket.IO.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have Node.js installed. If not, download and install it from [Node.js](https://nodejs.org/).

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/DhruvKaura/live-tracker.git
   cd live-tracker
   ```

2. **Initialize the Project**

   Create a `package.json` file and set up the project:

   ```bash
   npm init -y
   ```

   Modify the `package.json` file to set the main file to `"app.js"`:

   ```json
   "main": "app.js",
   ```

3. **Install Dependencies**

   Install the required packages:

   ```bash
   npm install express ejs socket.io
   ```

### Running the Application

Use `nodemon` to run the application and automatically restart it when changes are detected:

```bash
npx nodemon app.js
```

## Usage

Once the application is running, you can access it in your browser at `http://localhost:3000`.

## Built With

- [Express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
- [EJS](https://ejs.co/) - Embedded JavaScript templating
- [Socket.IO](https://socket.io/) - Enables real-time, bidirectional, and event-based communication

## Contributing

Please read [CONTRIBUTING.md](https://github.com/DhruvKaura/live-tracker/CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/DhruvKaura/live-tracker/LICENSE) file for details.

## Acknowledgments

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [EJS](https://ejs.co/)
- [Socket.IO](https://socket.io/)

---

This revised README provides a clearer structure, more detailed instructions, and a professional format.

