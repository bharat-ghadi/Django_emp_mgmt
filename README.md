
# Employee management app Django

This app is based Django framework. It consist of 4 pages, you can check them in screenshot section below.
This apps frontend is handled by Html, CSS , Bootstrap 5.0 along with djnago framework.
Backend is handled by djnago framework which is based on python. The Database creation ORM is automatically handled by django itself, by default Sqlite Database is there but you can change it manually if required.
## Deployment / Installation

To deploy this project you need following things installed.
- python 3 or above
- Django
- any IDE would be better i.e Pycharm, VS code


Open project folder in your IDE. To run this project do following.

change directory where projects manage.py is located, in case  of this project it would be 
```bash
  cd emp_mgmt_dj
```


check if you have django installed , if not then install django using pip in current directory. 
```bash
  pip install django
```

Apply migrations on your machine
```bash
   python manage.py makemigrations
   python manage.py migrate

```

Then runserver.
```bash
   python manage.py runserver

```

Then click on the link or copy the link from terminal in your browser.
It will be like this. copy the http link

```bash
   Starting development server at http://127.0.0.1:8000/
python manage.py runserver

```

## Documentation

- [Django Documentation](https://docs.djangoproject.com/en/4.1/)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

## Screenshots
### View all employees:
- This allows us to view all records in the database
![View All Empployee](https://github.com/bharat-ghadi/Django_emp_mgmt/blob/main/screenshots/view_all_emp.PNG)
### Add employee:
- This allows us to add employee records in the database.
- The styling is done by bootstrap classes i.e. form-label , form-control
![Add Empployee](https://github.com/bharat-ghadi/Django_emp_mgmt/blob/main/screenshots/add_emp.PNG)
### Remove employee:
- This allows us to remove employee records in the database.
- The dropdown reocrds are fetched from database.
![Remove Empployee](https://github.com/bharat-ghadi/Django_emp_mgmt/blob/main/screenshots/remove_emp.PNG)
### Filter employee:
- This allows us to Filter employee records in the database.
- The employee can be filter by name, role or dept.
- magical method icontains is  used to achieve filter action i.e. emps.filter(role__name__icontains=role)

![Filter Empployee](https://github.com/bharat-ghadi/Django_emp_mgmt/blob/main/screenshots/filter_emp.PNG)

## Support

For support, email bgaonkar96@gmail.com.


## FAQ

#### Django sometimes throws error for bootstrap.

pip install django-bootstrap5
or relevent version you are trying

#### Question 2 manage.py : [Errno 2] No such file or directory
Change directory into your project where manage.py is located.

Answer 2


![Logo](https://github.com/bharat-ghadi/bharat-ghadi/blob/main/Beige%20Minimalist%20Profile%20LinkedIn%20Banner%20(1)_page-0001.jpg)
