Willkommen zu meinem Coffee Shop Projekt
Dieses Projekt zeigt die Automatisierung mit Tosca.

Verwendete Technologien
HTML, CSS, JavaScript
Tosca Testautomatisierung
Screenshots

Tosca Aufgaben Präsentation – präsentiert von Pallavi Kulkarni


Aufgabe 1–3

Beschreibung jeder Aufgabe
Verwendete Module (z. B. TDS, wiederverwendbare Testfälle)
Platz für Screenshot



Verwendete Tosca Module

TDS Module
Wiederverwendbare Testfälle
Testfall-Sektionen



Datengetriebene Tests

Erklärung und Vorteile
Umsetzung mit TDS

Task 1 Level 1

The following information about an order is contained in a test data sheet:
- Item
- Price
- Quantity
- Total

The test case should check on the shop page whether the unit price for the item is correct. Then, the item should be added to the shopping cart in the desired quantity. The total price should then be checked in the shopping cart. (Without logging in)

Task 1 Level 2
Not just one item, but several different items should be added to the shopping cart. The test data sheet should be adjusted accordingly.
1-n rows with items and then the row with the total.

Task 1 Level 3
The items should not be added directly to the shopping cart on the shop page, but rather on the respective detail page. Here, it is necessary to check in advance whether the item image is displayed, and whether the description text and price are correct.

Task 1 Level 4
For each item, it should be checked whether the available quantity (from the detail page) matches the stock in the displayed shopping cart.

Task 2, Level 1
For an item (selectable via the test data sheet), we want to check whether the maximum permitted quantity can be ordered.
Second, we want to check whether the correct message appears on the details page when more than the permitted quantity is ordered.
Third, we want to check if an attempt is made to set the quantity in the shopping cart above the permitted quantity.



Task 2, Level 2
We want to check whether the correct discounts are applied and whether the discounts are displayed in red.

Task 3, Level 1
The test case should be controlled via the test data sheet. (Keyword-driven)
I would like to be able to enter the following keywords, including the necessary data, in the test data sheet:
- Add items
- Adjust the number of items
- Delete items from the shopping cart
- Check the number of items in the shopping cart
- Check the total price in the shopping cart
- Submit the order (Checkout)
- Select the payment method
- Place the order (ORDER)

