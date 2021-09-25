### Running the project:

Cloning the repository and accessing it through terminal:

```
git clone https://github.com/selectcoma/api_final_yatube.git
```

```
cd api_final_yatube.git
```

Create and activate the virtual environment:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Install the requirements from requirements.txt:

```
pip install -r requirements.txt
```

Migrations:

```
python3 manage.py migrate
```

Launch the project:

```
python3 manage.py runserver
```

Access the documentation:

```
project_url + /redoc
```

