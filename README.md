# QRKot Charity Foundation

The QRKot Charity Foundation is a web application built using Python 3.9 and FastAPI 0.78.0. The application allows users to make donations to various cat-related causes, such as medical care for cats in need, setting up cat colonies in basements, and providing food for homeless cats.

## Technologies Used

- Python 3.9
- FastAPI 0.78.0
- FastAPI-Users 10.0.4
- Pydantic 1.9.1
- SQLAlchemy 1.4.36
- aiosqlite 0.17.0
- Alembic 1.7.7
- Flake8 4.0.1

## Getting Started

### Installation

1. Clone this repository:

```bash
git clone https://github.com/PavelFil98/QRKot_charity.git
```
2. Create and activate a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
```
3. Upgrade pip and install the required packages:
```bash
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
4. Create and fill in the .env file:
```bash
touch .env
```
5. Run the database migrations:
```bash
alembic upgrade head
```
6. Starting the Application: To start the application, run the following command:
```bash
uvicorn app.main:app
```
The application will be available at http://127.0.0.1:8000.

## API Documentation

The API documentation is available at the following URLs:

- Swagger: http://127.0.0.1:8000/docs
- Redoc: http://127.0.0.1:8000/redoc

## Author

Pavel Filipovich

## Contact

Email: pf1860525@gmail.com

Please feel free to reach out if you have any questions or feedback.
