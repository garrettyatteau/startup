# This is Garrett Yatteau's startup project for CS260

[Link to Notes](notes.md)

## Elevator Pitch

Tier lists are commonly used to compare different items witihin the same genre. These can range from ranking TV shows to vacation spots. On this website you will have the chance to rank a list of various different foods within a tier list. After logging in and creating your tier list, the data from your tier list will be sent towards a community ranking, where the average ranking of each food item on each users tier list will be compiled into one tier list.

## Key Features

+ First webpage asks the user for a username and password, then stores this login information.
+ After logging in, the tier list creator web page will be accessed, where the user can then begin ranking items into tiers.
+ The user can rename tiers, add and subtract tiers and place as many different items into each tier as they desire.
+ The user will be able to submit their tier list and make changes later if they change their mind.
+ The user will be able to view the community ranking of each food item on a separate linked web page.

## Technologies Represented
+ HTML: At least three webpages will be structured using HTML: one for login, one for creating a tier list and one for viewing the community ranking.
+ CSS: Applies consistent style across the site including font, background color/images, white space and headings.
+ Javascript: Allows user to login, drag items into the tier list, edit the tier list, and submit the tier list.
+ Web server: Runs the website and accesses database.
+ Authentication: A username and password will be requested, then stored in the database after it is input.
+ Storing data: A database will store login information for each user, as well as each tier list and item value to be displayed in the community tier list.
+ WebSocket: When a user submits a tier list, the ranking of each food item will be added to the community list database, in turn updating the community ranking for that specific item.
## Sketch

![Sketch of my startup website using NinjaMock.com](/startup_image.png)
