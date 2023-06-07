## The problem

Using your preferred programming language, design a loyalty program for a coffee shop. Customers collect one stamp per
coffee; when they reach six stamps, they have one free coffee. The application exposes the following public operations:

- Create a customer.
- Create a stamp for a customer.
- List all stamps and free coffees for a customer.
- Redeem a free coffee.

## If the customer reaches six stamps upon adding a new stamp, the application should create a free reward coffee.

The rules

- All methods have a maximum of three lines of code.
- All classes have a maximum of two fields (excluding data classes and POJOs).
- All classes have a maximum of ten lines of code (excluding imports).

These rules have Java and Kotlin in mind; you may need to tweak them to suit your programming language.

## Notes/assumptions

- The app may hold state (customers, stamps, free coffees) in memory.
- Make reasonable assumptions for things like error handling (trying to add stamps to non-exiting customers, for
  example); that part is not that important.
- To ease testing, you can pre-load your application with customers, stamps and free coffees.