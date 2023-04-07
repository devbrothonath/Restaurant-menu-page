# Restaurant menu-page
## Overview
Thank you for checking out the project. This is a restaurant menu page with content loaded dynamically from javascript file to the html file. This is a static page which shows menu of foods and you can choose a dish according to time of day. This is made as a restaurant specific where the restaurant can use this to show menu.

## Features
The restaurant can use this to show menu on Tablets instead of pre-written menus, some advantages of this approach:
* The restaurant can remove any dishes not available and save the embarrassment from telling "Sorry, this dish is not available" to the customer.
* They can add new dish available to the customers, quickly and easily to the menu page.
* They can change it to make a section for special dishes available on special occassions like 20th anniversary of restaurant.
* There are 5 buttons available primarily. <br>
  1. All 
  2. Breakfast 
  3. Lunch 
  4. Shakes 
  5. Dinner 

The dishes are shown in form of cards with an image, title, price and a description.
## Working
The data is saved as an object in a menu array with 6 key value pairs. <br>
1. id: dish_id
2. title: dish name
3. category: type of dish
4. price: price of dish
5. img: img file source path
6. desc: description of dish

```
{
    id: 1,
    title: "buttermilk pancakes",
    category: "breakfast",
    price: 15.99,
    img: "./images/item-1.jpeg",
    desc: `I'm baby woke mlkshk wolf bitters live-edge blue bottle, hammock freegan copper mug whatever cold-pressed `,
  }
```

## Running the project
  From the repo :  
1. Use `git clone` to download the project locally.
    * cd into project directory
    * Run `git clone https://github.com/devbrothonath/Restaurant-menu-page.git` on terminal
2. To add a new dish, go to "app.js".
3. Then inside app.js, there will be a menu array at the topmost.
4. Create a new object inside the menu array like the above specified key value pairs.

  Live version : <br>
* Deployed this application on netlify. You can check it out here : [Restaurant Menu Page](https://menu-page-dynamic-d7f0b9.netlify.app/)
