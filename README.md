# Django Store

This is a store website built with Django for educational purposes. Please note that this project is not intended for real-life applications and will not be maintained.

## Installation

To run this project, make sure you have Python installed. Then, follow these steps:

1. Clone the repository:

  ```bash
  git clone https://github.com/lopdan/django-store.git
  ```

2. Navigate to the project directory:

  ```bash
  cd django-store
  ```

3. Install the required Python packages:

  ```bash
  pip install -r requirements.txt
  ```

## Usage

To launch the application, run the following command:
```bash
python manage.py runserver
```

## Environment variables

```
SECRET_KEY=your-secret-generated-key
STRIPE_LIVE_PUBLIC_KEY=your-live-public-key
STRIPE_LIVE_SECRET_KEY=your-live-secret-key
STRIPE_TEST_PUBLIC_KEY=your-test-public-key
STRIPE_TEST_SECRET_KEY=your-test-secret-key

DEBUG=False
DB_NAME=your-db-name
DB_USER=your-db-user-name
DB_PASSWORD=your-db-password
DB_HOST=localhost
```