//page1

> List of sellers
* http://localhost:1000/sellers

> List of City Location
* http://localhost:1000/location

> List of product cat
* http://localhost:1000/productType



//Page2

> Details of Products data
* http://localhost:1000/productdata

> List of sellers wrt city
* http://localhost:1000/sellers?stateId=4

> List of sellers wrt to product type
* http://localhost:1000/sellers?productTypeId=1

> filter wrt peroduct type & electrical items
* http://localhost:1000/filter/1?electricalId=3

> List of sellers wrt to product & cost
* http://localhost:1000/filter/3?hcost=5000&lcost=2000


//Page3
> user data
* http://localhost:1000/usersdata
> List of orders
* http://localhost:1000/orders


//Page4
> Placed Order (POST)
* http://localhost:1000/placeOrder
body 
{
"order_id": "9",
"date_of_order": "21/10/2022",
"user_name": "naveen Sharma",
"email": "naveen@gmail.com",
"phone_no": 9910964525,
"address": "jangpura",
"product_id": 1.1,
"Quantity": 2,
"price": "Rs. 1800",
"user_id": 1
}
> List of orders wrt to email (POST)
* http://localhost:1000/orders?email=naveen@gmail.com

> Product menu (POST)
* http://localhost:1000/productdata
body
{
    "id":[
        1.2,1.5,1.6
    ]
}


//page 5
> Update Payement Details 
