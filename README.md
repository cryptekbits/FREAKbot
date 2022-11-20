
# Food Reservation and Edibles Acquisition Keeper (FREAK) Bot

### What is FREAK Bot ?
FREAK Bot is an initiative for Managing the Reservations for a meal at our flat and the associated inventory.

### Why do we need FREAK Bot ?
Over the last few years, while staying in flats with other flatmates that have varying schedules, commitments, tastes
and meal preferences, I have noticed that managing meals, instructing the cook on time, ensuring availability of the
right ingredients and also avoiding wastage/shortage of food has been a cumbersome task. And since usually, this
caused by a communication gap and lack of Single point of contact and management, I decided to automate the process
and offload this to a Bot.

### What are the (projected) capabilities for the FREAKBot ?
1. Maintaining the Menu and regularly informing the flatmates at a preset time before the cook's arrival
2. Taking a Poll if someone will be skipping a meal
3. Availing option to request additional food to be prepared for a guest(s)
4. Forwarding the menu to the cook at the cutoff time.
5. Facility to update a menu entry temporarily or permanently
6. Reminding the Flatmates to order items from the grocery app (BigBasket,BlinkIt, etc,) at schedule times by selecting the person by roundrobin
7. Possibly, if I finish the above list in this week (ending 27 Nov 22) will initiate a layer to automate order from BigBasket
8. Finally, if the entire list above is completed and my flatmates and friends see a utility here, will move to development of a iOS/Android App

### Where is FREAKBot hosted ?
Currently, in its development phase, the bot will be available to host on PythonAnywhere/Heroku or other similar offerings

### How does FREAKBot work ?
* Written in Python
* Using the Flask WebServer
* Twilio Whatsapp Messaging API

* [MIT License](LICENSE)
