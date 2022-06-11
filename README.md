# Build an API with Django, React, and Docker

This is a simple example of how to build an API with Django, React, and Docker. You can find the
article concerning this code here [blog](https://koladev.xyz/posts/django-react-crud/).


## Starting with Django and React

First launch the API server.

```bash
cd restaurant-menu-api
pip install -r requirements.txt
python manage.py runserver
```

The API server will be available at `http://localhost:8000/`.

Then launch the React client.

```bash
cd restaurant-menu-front
yarn install
yarn start
```

The React client will be available at `http://localhost:3000/`.

Feel free to open issues on the [GitHub repository](https://github.com/koladev32/restaurant-menu-tutorial) if you have any questions.