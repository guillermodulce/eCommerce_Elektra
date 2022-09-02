#eCommerce 💻 Elektra

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

## Sections

* Home

The main categories are located on the initial screen, as well as the entry to the administrator's registry and login.

* Category view

When entering the view by category, you can see the list of items, with their respective image, brand, name, weight, price in US dollars and its equivalent in Bitcoins. For this we use the Currency Data API live/endpoint <url https://apilayer.com/marketplace/currency_data-api>, which provides a simple REST API with real-time and historical exchange rates for 168 world currencies, delivering currency pairs in universally used, compatible JSON format. with any of your applications. Spot exchange rate data is retrieved from several major forex data providers in real time, validated, processed and delivered every hour, every 10 minutes or even within the 60 second market window.

![Image text](https://github.com/guillermodulce/eCommerce_Elektra/blob/main/app_ecommerce/static/elektrascr.png)


* Product detail view

The product detail section contains, in addition to what is indicated in the category view, a detailed description of the article and up to three related images.

* Register as admin

In the register as administrator section, you must enter the user name, email, password with their respective confirmation. The system validates if there is repeated information in username or email, and gives a response accordingly.

* Login

In the login section you can request the reset of the password, in case it has been forgotten.

* Create a category

The administrator can create a new main category or subcategory within the main ones. To do this, you must enter the create a category section, enter the name, optionally put a representative image of the category, and then in the drop-down menu, choose whether it will be a main category or it will be within another already created category.

* Create a product

In the create a product section, the administrator must complete the following fields: Name, brand, description, weight, price in dollars. Up to three images per product can also be entered. Then you must indicate to which category the created product belongs. The system performs a validation so that the characters in the description do not exceed 1000 and in the name and brand, up to 50 characters can be used.

![Image text](https://github.com/guillermodulce/eCommerce_Elektra/blob/main/app_ecommerce/static/127.0.0.1_5000_products_new.png)


* Reset password

If you want to use the password restoration function, you must configure the environment variables with your email and password.





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


