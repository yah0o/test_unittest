Unittest example project
------------------------
- Create virtualenv python3
- Install packages:
```
pip install flask 
```

- Create application DataBase (only 1 time). Open python file app/coffeedb_initiate.py and execute it. DataBase is created.
- Run web application. Open python file coffee_web.py and execute it. 
- Open Chrome web browser. Enter adress: http://127.0.0.1:5000/ 
- Run tests e.g.

```
python -m unittest tests.coffee_tests.TestDbMethods
```

CoffeeForMe web application.

_______________________________________________________________________

Instructions for salesmans:

1. On the main page press on "Salesman" --> be redirected to login page.
2. Enter name. Valid salesmen names are: John, Ann, Ted. Press "login" button --> be redirected to the page with beverages to select.
3. Press beverage to select --> be redirected to the page with additionals to select.
4. Press additional to select --> be redirected to the page with selection displayed. Press "Get price" --> be redirected to the page with your selection and price dispalayed.
5. To write the data (order) to the DataBase press "Make order" button --> be redirected to the page for the next beverage selection.

6. To change salesman, enter adress: http://127.0.0.1:5000/ and be redirected to login page.
7. To navigate between beverages/additionals/prices use browser's "back" button top left.

________________________________________________________________________

Instructions for manager:

1. On the main page press on "Manager" --> be redirected to login page.
2. Enter name. Valid manager name is: Mary. Press "login" button --> be redirected to the page with sales statistics.
