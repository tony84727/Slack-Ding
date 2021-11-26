### Create an OrderList

1. Use an interactive shortcut to create a new orderlist
1. Optionally attach a image menu or URL 
1. Optionally set a ending time
1. The bot returns a interactive message to allow users to click to place orders

### Place order to the orderlist
1. When the order is placed, the bot return the similar interactive message but with the new order added.
1. An order contains: Dish name, price and count
1. Optionally with a buyer name for the order, or by default, the buyer name is the Slack message author's name.


### Edit the order
1. Each order should have a number to allow user specify the order in the list to order

### Conclude the OrderList

1. Automatically conclude the order list if the ending time is set
1. Use an interactive shortcut to conclude the orderlist