
# ToDo List Application

**ToDo List** is a web-based application that allows users to manage their daily tasks efficiently. Built using Node.js, Express.js, EJS, and MongoDB, this application provides a seamless experience for creating, viewing, and deleting tasks.

## Features

* Add new tasks to your to-do list
* View all existing tasks
* Delete tasks that are no longer needed
* Responsive design for various devices

## Demo

You can view the live demo here: [ToDo List Live Demo](https://murtadhajasim.github.io/todolist/)

## Getting Started

### Prerequisites

* [Node.js](https://nodejs.org/) (version 14 or higher)
* [MongoDB](https://www.mongodb.com/) (local or cloud instance)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/MurtadhaJasim/todolist.git
   cd todolist
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:

   ```env
   PORT=3000
   MONGODB_URI=your_mongodb_connection_string
   ```

4. **Start the application:**

   ```bash
   npm start
   ```

5. **Open your browser and navigate to:**

   ```
   http://localhost:3000
   ```

## Project Structure

```
todolist/
├── public/
│   └── css/
│       └── styles.css
├── views/
│   ├── partials/
│   └── pages/
├── app.js
├── package.json
└── README.md
```



## Technologies Used

* [Node.js](https://nodejs.org/)
* [Express.js](https://expressjs.com/)
* [EJS](https://ejs.co/)
* [MongoDB](https://www.mongodb.com/)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Submit a pull request

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

* Inspired by the need for efficient task management
* Built with [Express.js](https://expressjs.com/) and [MongoDB](https://www.mongodb.com/) for robust backend support
