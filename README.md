## Pydantic Practise

This project demonstrates the functionality of a support agent using Pydantic and SQLAlchemy. The support agent can help users with their accounts, check subscription plans, and determine if their query should be escalated to an admin.

### Project Structure


- `__init__.py`: Initializes the package.
- `agent.py`: Contains the support agent implementation using Pydantic and SQLAlchemy.
- `database.py`: Configures the database connection and session.
- `main.py`: Contains the main function to test the support agent.
- `models.py`: Defines the database models.
- `seed.py`: Seeds the database with initial data.

## Usage

1. Clone the repository.
2. Run the `seed.py` script to create and seed the database:
    ```sh
    python main.py
    ```
