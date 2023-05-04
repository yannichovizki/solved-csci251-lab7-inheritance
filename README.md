Download Link: https://assignmentchef.com/product/solved-csci251-lab7-inheritance
<br>
Following completion of this task, students should be able to:

<ul>

 <li>Write C++ programs using inheritance.</li>

</ul>

<h1>Question 1 (Inheritance)</h1>




Declare and implement a class named Payment that contains a member variable of type float that stores the amount of the payment, a default constructor, a non-default constructor, a setField() function that receives parameters to set the data member, and a member function named paymentDetails() that outputs the amount of the payment.




Next, declare and implement a class named CashPayment that is derived from Payment.  Include balance due as the data member for this class. This class should override the paymentDetails() function to add a message to indicate that the payment is in cash and display the balance due if any. Include also a default constructor, a nondefault constructor and overload the setFields() function.




Declare and implement another class named CreditCardPayment that is also derived from Payment. This class should contain member variables for the name on the card, expiration date, and credit card number. Include a default constructor, a non-default constructor, overload the setFields() functions, and finally, override the paymentDetails() function to include all credit card information in the printout apart from the payment amount.




Create a main function that creates two CashPayment and two CreditCardPayment objects with different values.  Show that some objects are initialized using the non-default constructor and some are initialized using the default constructor and then set using the setFields() functions.  Display the payment details for each of the objects.<strong> </strong>

<h1>Question 2 (Multiple Inheritance)</h1>

Write a C++ program to implement multiple inheritance.  There should be two base classes: House and

Investment.

The Investment class should contain fields to hold the initial value of an investment, the current value, the profit (different between the previous two fields), and the percentage profit (profit divided by initial value).  It should have a non-default constructor that requires parameters for the initial and current values, and a display function.

The House class should have fields for street address and size (in square meters).  It should also have a nondefault constructor that sets both fields using values passed as parameters, and a display function.

Create also a HouseInvest class which inherits from both Investment and House.  It includes a non-default constructor that receives arguments for a house details and also an investment details, and a display function which uses both the base classes display functions.




Write a main() function that declares a HouseInvest object and displays its values.





