# -Behavioural_design_pattern

Use Case 1: Observer Pattern
Scenario: A simple newsletter system where users can subscribe and unsubscribe to receive updates.
Observer Interface: Defines the update method that all observers must implement.
Subscriber Class: Implements the Observer interface and provides the update method.
Subject Interface: Provides methods to register, remove, and notify observers.
Newsletter Class: Implements the Subject interface, maintaining a list of observers and notifying them of new editions.

Use Case 2: Strategy Pattern
Scenario: A simple payment processing system where users can pay using different payment strategies (e.g., Credit Card, PayPal).
PaymentStrategy Interface: Defines the pay method that all payment strategies must implement.
CreditCardPayment and PayPalPayment Classes: Implement the PaymentStrategy interface, providing specific implementations of the pay method.
ShoppingCart Class: Acts as the context, holding a reference to a PaymentStrategy and using it to perform the payment operation.
