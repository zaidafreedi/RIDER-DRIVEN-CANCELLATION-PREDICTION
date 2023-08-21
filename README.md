# RIDER-DRIVEN-CANCELLATION-PREDICTION

Given the order and rider details, create a model is developed that can predict rider-driven cancellation in advance (i.e. before getting marked as cancelled or delivered)

The typical order flow goes like this:

A client creates the order in our system.

The order gets allocated to a rider.

The rider accepts the order.

The rider goes to the pickup location.

The rider picks up the order.

The rider goes to the delivery location and delivers the order.

The rider also has the option to get the order cancelled before delivery by calling the client’s call centre. We would like to predict this kind of cancellation before it happens so that we can try and reassign the order to another rider before it gets cancelled.
