# eCommerce 💻 Elektra
#### Video Demo:  <URL HERE>
#### Description:

_This project was made for CS50x final project._

Elektra eCommerce is a simple web app, whose purpose is to register new articles in a catalog of an electronic products store. In this first version, the application allows you to create an administrator user, who after successfully logging in, can create categories and subcategories. Within these categories, the administrator can add products, with their details, such as brand, model, description, price and images.

In the section of products by categories, you can view the items, with brand, model, main image, price in US dollars and also its equivalent in Bitcoins. For the real-time conversion I used the API Layer Currency Data API.

I exclusively used the tools, frameworks and resources studied in the HarvardX CS50 course:

* Flask
* Html
* Css
* Jinja
* Sqlite
* Bootstrap
* API

This web application is based on the Python Flask framework, and it is styled with some Bootstrap 5.2 components for the menu, alerts, carousel and grid structure.

For database management I used Sqlite 3 and Sqlite Studio for some optimizations.

In future implementations, stock management, cost and supplier information will be included. The development of the shopping cart will have the possibility of paying with crypto assets, digital wallets and credit cards.




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
