This project is a clone of online food store like swiggy. It is completely build using pure HTML, CSS and JS.

Problem Statement was- 
1)to create a interface were all the food items will be visible and style it using CSS 
2)Make it responsive 
3)When ever a user click any of the food item it should give a pop up showing the details of the order, price and if the price of the item is below 100rs than Additional cost of delivery charges should to added to it and if the price is above 100rs than no additional cost should be added.

Difficulties I faced and how I overcome them - 
1)Struggling with the alignments of the food item in flex. The problem was all the 12 items was getting aligned in a single row which was making the UI look so bad. FIX - Actually fix was simple, just have to add flex-wrap property. 2)Another problem was with event listener. To add event listener to all the 12 food items manually is a tedious task, I a created a array i.e. node list of all the food items using querySelectorAll, as this was returning a array I was not able to add event listener to it, so the fix was to use for each on the node list array and then add the event listener on each item.

How I solved it - 
1)Created a basic page using HTML, created food items using some random data.
2)Style this HTML using CSS, used Flex to make a grid pattern for the food items to make it look much better and used flex wrap to properly distribute this items over the page.
3)Used "addEventListener" to get the information of which food item does the user clicked, done this by passing data in food item which is the parent div which contain all the details about the food item in HTML, there are two data I passed those are - data-title and data-price.
4)So whenever a user clicked anyone of the food item using event listener, I was able to track the title and price of the food item clicked.
5)And at the end using basic js added the functionality of add delivery charges.

The main Features of this project are - Track what food item does the user clicked and automatically do all the calculations.
