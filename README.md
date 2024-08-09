# Books Dataset

This repository contains a collection of books stored in a JSON format. The dataset includes various details about each book, such as the title, author, genre, and publication year.

## Dataset Overview

The `books.json` file contains a list of books, each represented as a JSON object with the following attributes:

- `title`: The title of the book.
- `author`: The name of the author(s).
- `genre`: The genre or category of the book.
- `published_year`: The year the book was published.
- `isbn`: The International Standard Book Number (optional).

### Example

```json
[
  {
    "title": "To Kill a Mockingbird",
    "author": "Harper Lee",
    "genre": "Fiction",
    "published_year": 1960,
    "isbn": "978-0-06-112008-4"
  },
  {
    "title": "1984",
    "author": "George Orwell",
    "genre": "Dystopian",
    "published_year": 1949,
    "isbn": "978-0-452-28423-4"
  }
]
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/mouraleonardo/books_dataset.git
   ```
2. Access the JSON file in the repository directory.

You can use this dataset in your applications, for data analysis, or for educational purposes. Feel free to extend and modify the dataset as needed.

## Contributing

Contributions are welcome! If you'd like to contribute to this dataset, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.