
## Installation

### 1. Create a virtual environment

From the **root** directory run:

```
virtualenv venv
```

### 2. Activate the virtual environment

From the **root** directory run:

```
venv\scripts\activate
```

### 3. Install required dependencies

From the **root** directory run:

```bash
pip install -r requirements.txt
```

From the **root** directory run:

```bash
cd static
```
```bash
npm install
```

### 4. Run migrations

From the **root** directory run:

```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

### 5. Create an admin user to access the Django Admin interface

From the **root** directory run:

```bash
python manage.py createsuperuser
```

## Run the application

From the **root** directory run:

```bash
python manage.py runserver
```

## View the application

Go to http://127.0.0.1:8000/ to view the application.
