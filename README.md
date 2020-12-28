# pizzapi

Congratulations! Your software factory was selected to build the brand new
_pizzapi_, a Pizza API service for developers. We expect a professional work in
every aspect; from coding to production delivery and monitoring.

## Requirements

Our client, [The Pizza Planet Guy][1], had a increasing amount of clients since
lockdown; it seems that, luckily, there is a lot of people working from home.
Strange as it is, a lot of them are programmers: _"how better than hook them up
to the business with funny Internet things?"_ the owner told us, and then asks
us to build something to help him. We resolved that an API would be a good fit
to his needs and collected the following requirements:

* A public API service, able to identify the client, collect the pizza's type
  and size and schedule the delivery.
* The owner is the only one allowed to create new size, flavors or deny the
  service for certain users.
* The client needs to create an user in the service, before asking for pizzas
  or delivery.
* The maximum amount of pizzas per delivery is 8 (of the big ones).
* The user cannot request more than 1 service per day (so, think carefully
  ^.^).
* The API service needs to respond in less than 500 ms.
* The service only understands JSON content types.
* Traffic monitoring is required to understand future behaviors.
* The service needs to be RESTful.

[1]: https://www.youtube.com/watch?v=2hFHGJOaYuc
