# OnlineShoppingSystemCaseStudy
Online Shopping System Case Study

Case Study: Online Shopping System

This scenario will involve classes representing products, customers, and shopping carts. It will illustrate various Java OOPS concepts such as encapsulation, inheritance, and polymorphism.
 
 
Classes/Entities:
1. Product:
  Properties: Product ID(int), Name(string), Price(double), Stock Quantity(int).
  Methods: Display product details, Update stock quantity, reduce stock quantity
   // Constructors, getters, setters, and methods for displaying details, updating stock
   // reduce stock quantity - throw OutOfStockException if insufficient stock for product
 
2. ElectronicProduct (inherits from Product):
  Additional Properties: Warranty Period(int)
  Methods: Display electronic product details.

3. ClothingProduct (inherits from Product):
  Additional Properties: Size(enum - S,M,L,XL), Color(String).
  Methods: Display clothing product details.

4. DiscountedProduct (inherits from Product):
  Additional Property: Discount Percentage(double).
  Methods: Display discounted product details.
  // Constructors, getters, setters, and methods for displaying discounted product details
 
5. Customer:
  Properties: Customer ID(int), Name(String), Email(String), Address(String).
  Methods: Display customer details.
  // Constructors, getters, setters, and methods for displaying details

6. Promotion:
  Properties: Promotion ID(int), Description(String), Discount Percentage(double).
  Methods: Display promotion details.
  // Constructors, getters, setters, and methods for displaying promotion details

7. ShoppingCart:
  Properties: List of Products, Total Price(double), List of Promotions.
  Methods: Add product to cart, Remove product from cart, View cart, Checkout.
  // Methods for adding/removing products, viewing the cart, applying promotions, and checking out

8. CustomExceptions:
  OutOfStockException: Thrown when trying to add a product with insufficient stock to the cart.
  InvalidPromotionException: Thrown when trying to apply an invalid promotion.

9. Create a class with main method:
  // Create electronic, clothing, and discounted products
  // Create a promotion
  // create a customer
  // Create a product inventory and promotion list ( use hashmap )
  // Customer adds products to the shopping cart (throw OutOfStockException if insufficient stock for product)
  // Display the cart
  // Remove products from the shopping cart
  // Display updated cart
  // Apply promotion to the cart ( throw InvalidPromotionException if provided promotion id not present)
  // Display the shopping cart
  // Customer checks out
  // Display customer details, purchased products, and applied promotions
  // View the cart - cart should be empty after checkout

