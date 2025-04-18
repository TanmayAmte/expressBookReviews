# expressBookReviews

A Node.js and Express-based web application for managing and reviewing books. This project is a fork of the [IBM Developer Skills Network's expressBookReviews repository](https://github.com/ibm-developer-skills-network/expressBookReviews).

## Features

- **User Authentication**: Secure login and registration system.
- **Book Management**: Add, update, and delete book entries.
- **Review System**: Users can post, edit, and delete reviews for books.
- **RESTful API**: Provides endpoints for all major functionalities.
- **Responsive Design**: User-friendly interface accessible on various devices.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/TanmayAmte/expressBookReviews.git
   cd expressBookReviews
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Configure environment variables**:

   Create a `.env` file in the root directory and add necessary environment variables. For example:

   ```env
   PORT=3000
   DB_URI=mongodb://localhost:27017/bookreviews
   SESSION_SECRET=your_secret_key
   ```

4. **Start the application**:

   ```bash
   npm start
   ```

   The application will run on `http://localhost:3000`.

## Usage

- Navigate to `http://localhost:3000` in your browser.
- Register a new account or log in with existing credentials.
- Add new books to the collection.
- Browse books and read reviews.
- Post your own reviews for books you've read.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/YourFeature
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add YourFeature"
   ```

4. Push to the branch:

   ```bash
   git push origin feature/YourFeature
   ```

5. Open a pull request.

## License

This project is licensed under the [Apache-2.0 License](LICENSE).
