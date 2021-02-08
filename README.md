## Features

---

- **Space Categorization** - classify food items based on the space they are stored. Add and remove spaces as needed.
- **Type Categorization** - classify food items based on their type.
- **Search Functionality** - search food items by name.

## About

---

PYE - Plan Your Eats - is a pantry tracking application.

## Getting Started

---

### Prerequisites

- Python3 should be installed

### Installation

cd into desired folder, then clone project:

```
git clone https://github.com/AndrewDurrant/pye_api.git
```

Create a .env file in the root of the project (in the same folder as `settings.py`), and add the app's secret key and debug variable:

```
SECRET_KEY=xxx
DEBUG_VAL=xxxx
```

create virtual env:

```
python3 -m venv pye_env
```

activate virtual env:

```
source pye_env/bin/activate
```

make sure you are in directory with the `requirements.txt` file and then run:

```
pip install -r requirements.txt
```

To start the development server run:

```
python manage.py runserver
```

Go to `http://localhost:8000` to check that everything is working correctly
