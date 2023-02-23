# WLU-Foodorama

*GUI application for "WLU Foodorama" written in Java for course credit in Object Oriented Programming(CP 213 Wilfird Laurier University) taught by Dr. Abdul Raman Yunis.*

Author: Erin Manson, with javadoc and assignment instructions by Dr. Abdul Raman-Yunis and Mr. David Brown

GUI interfaces, polymorphism, event driven programming, and key principles of object oriented programming are used in this assignment to create a user friendly restaurant menu and food ordering application.

The project is contained in a .zip file titled "WLU-Foodorama" containing:
- src folder (containing the main package "cp213" holding all necessary classes)
- menu.txt (text file containing menu items and their prices, this file could be altered to produce different menus)
- testing.txt (used to test/debug/and match actual output to expected output)

The cp213 package contains the following useful classes:
- A05Main.java: Run this class and use in console to see how Cashier, Menu, MenuItem, and Order classes are implemented.
- MenuItem.java: Constructors, getters, setters, and formatted ToString printing method for MenuItem objects which contian a name and price.
- RestaurantText.java: used for testing and console output of A05Main.java.
- Menu.java: Constructor which reads file data converting to MenuItems, getters, setters, and ToString method for formatted printing. Menu objects contain an array of MenuItems to form a Menu.
- Cashier.java: takes user input from console quitting when given 0 as input to take an Order as a cashier would. Simply wraps around Order object(see below).
- Order.java: Order objects have MenuItem objects and quantities, ToString method formats the order in a receipt calulating subtotals, taxes and totals.

  GUI Portion:
  - OrderPanel.java: The OrderPanel class uses JPanel to create an appealing user interface where a menu is displayed and users can input their orders. The User can also choose to print their order or save as a pdf by pressing "Print". Action listeners and error avoidance is used throughout the class for all JComponents to work seamlessly. See screenshot of UserPanel Design:
  
<img width="429" alt="WLU-Foodorama" src="https://user-images.githubusercontent.com/126124271/220811542-54edb6d1-f626-4264-960e-35f9a9f13ab5.png">

  - RestaurantGUI.java: Contains GUI execution for JPanel to be contained in JFrame
  
  
Try it yourself by downloading the zipped eclipse file! Run A05Main.java for console use and RestaurantGUI.java to launch GUI menu and ordering interface print your pdf by pressing print.

email me with any questions at 0404em@gmail.com

EEM

