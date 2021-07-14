# Instructions and General Information

## Instructions
The project is based on a small java program to simulate the retail discounts which uses the following technologies:

* Java 1.8
* JUnit for Unit Tests
* Eclipse to run and test the program

Since the program is created in Eclipse it is recommended to also run and test it by importing it into Eclipse though other IDE's can also be used. You can run the program by executing shopping.Main.java file in Eclipse

Furthermore, unit tess are provided that can run by executing shopping.test.TestDiscounts and shopping.test.TestWithoutDiscounts. To get the complete test coverage just run JUnit Tests in IDE.

Comments are provided in the code and test cases for briefly describe the functionality and approach.

In case of any errors make sure that the jars under the lib folder is included in the buld path.


## General Information regarding the solution

- **Items** represent goods/products that can be placed in the cart.

- A **cart** contains a number of items, and can compute the total price of its contents.

- Cart items can either be actual **products** with a fixed unit price, or products with a **pricing policy** attached for any dicounts that are calculated based on items and not the overall discount policy of current cart.

- **DiscountPolicy** is used to calculate or apply different discounts based on overall cart value of contents.

