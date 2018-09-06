# Healthy Kitchen CMS PHP Restful API

Healthy Kitchen CMS PHP Restful API is an online grocery shop. The project is developed by using PHP/MySQL/Slim Restful API. The project has powerful backend CMS to manage grocery shop online. it has features like add items, remove items, update price, manage orders etc. Restful API ready to embed in Application using JSON data.

### Features

- Powerful Dashboard
- Add , Manage Items
- Add , Manage Category
- Update Price
- View Orders (Confirmed, Preparing, On Way, Dilivered)
- Generate Bills
- Manage Customers

| Screenshot | Screenshot |
| --------------------- | -------------------- |
| <img src="/sc/1.PNG"> | <img src="/sc/2.PNG"> |
| <img src="/sc/3.PNG">| <img src="/sc/4.PNG"> |

### App API Requests

Get all Category:  
Link : yoursite.com/app/allcategory 

```
Request Body :
{ 
 "token":"app963" 
} 

Response: 
{ 
    "feedData": [ 
        { 
            "id": "9", 
            "categry": "Fruits" 
        }, 
        { 
            "id": "10", 
            "categry": "Juice" 
        }, 
        { 
            "id": "11", 
            "categry": "Vegetables" 
        }, 
        { 
            "id": "12", 
            "categry": "Salad" 
        } 
    ] 
} 

```


