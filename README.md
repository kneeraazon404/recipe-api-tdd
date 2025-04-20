# Recipe API (TDD)

This is a **Recipe API** built using **Test-Driven Development (TDD)**. The API allows users to manage recipes, ingredients, and tags, and is designed to be scalable, maintainable, and extensible.

---

## Features

- **User Authentication**: Secure user registration and login functionality.  
- **Recipe Management**: Create, update, delete, and retrieve recipes.  
- **Ingredient Management**: Add and manage ingredients for recipes.  
- **Tagging System**: Add tags to categorize recipes.  
- **TDD Approach**: Developed with a focus on test-driven development to ensure robust and reliable code.  

---

## Technologies Used

- **Python**: Core programming language.  
- **Django & Django REST Framework (DRF)**: For building the API.  
- **Docker**: For containerization and easy development setup.  

---

## Getting Started

### Prerequisites
- [Docker](https://www.docker.com/)
- [Python 3.9+](https://www.python.org/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kneeraazon404/recipe-api-tdd.git
   cd recipe-api-tdd
   ```

2. Build the Docker containers:
   ```bash
   docker-compose build
   ```

3. Run the containers:
   ```bash
   docker-compose up
   ```

4. Run the tests to ensure everything is working:
   ```bash
   docker-compose run app sh -c "python manage.py test"
   ```

---

## Usage

- Access the API locally at `http://localhost:8000/api/`.  
- Documentation for endpoints can be found [here](#). *(Add link to API docs if available.)*  

---

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/kneeraazon404/recipe-api-tdd/blob/main/LICENSE) file for details.
