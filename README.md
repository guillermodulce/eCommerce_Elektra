# eCommerce 💻 Elektra

_This project was made for CS50x final project_

A simple app to register new products in a catalog of an electronic products store. In this first version, the application allows you to create an administrator user, who, after successfully logging in, can create categories and subcategories. Within these categories, the administrator can add products, with their details, such as brand, model, description, price and images.

In the section of products by categories, you can view the items, with brand, model, main image, price in us dollars and also its equivalent in Bitcoins. For the real-time conversion I used the API Layer Currency Data API.


I exclusively used the tools, frameworks and resources studied in the HarvardX CS50 course.

_Flask_
_html_
_css_
_Jinja_
_Sqlite_
_Bootstrap_
_API_

This web application is based on the Python Flask framework. It is styled with some Bootstrap 5.2 components in the menu, alerts, carousel and grid structure.

For database management I used Sqlite 3 and Sqlite Studio for some optimizations.




## How to run this project 🚀

_This project runs within a virtual environment._

## Requirements 📋

### Python 3.6 or higher
### Anaconda 3


_In Windows_
* Clone or download this repository
* Open the downloaded folder
* Open the command line and type the following command:

```
conda create -n env36 python=3.6
```
```
./anaconda3/Scripts/activate
```
```
conda activate env36
```
```
conda install -r requirements.txt
```

## Start this project 

```
python run.py
```

## Finally open loopback URL address  

http://127.0.0.1:5000/

## Note:
If you want to use the password restoration function, you must configure the environment variables with your email and password
