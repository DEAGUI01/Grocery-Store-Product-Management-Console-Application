<h1>Grocery Store Product Management Console Application</h1>


<h2>Description</h2>
This assignment explores the creation of a reusable class and separate console application that creates a list of objects. You are to create a console application that has two classes in separate files. One class will contain the Main method and the other will be a public class named Product. Product will represent our initial attempt at representing the products located in a grocery story. Each Product object will have the same details:
<br />
<br />
•	Supplier Name (string)
<br />
•	Product Name (string)
<br />
•	Product ID (int)
<br />
•	Product Type (string)
<br />
•	Product Price (double)
<br />
•	Aisle Location (int)
<br />
•	In Stock Status (bool)


<h2>Requirements</h2>
The specific public requirements for the Product class are listed below. You may not change or add to the public interface described here.
<br />
<br />
 <b>•	A 6-parameter constructor that accepts the supplier’s name (string), product’s name (string), product ID (int), product’s type (string), product’s price (double), and the product’s aisle location (int). When a product is created, it is not in stock yet. Use the set properties for all relevant fields (except the in-stock status which does not have a property) to establish their initial values (instead of directly changing instance variables). No other constructor exists for this class (there is no parameter-less constructor for this class).</b> 
<br />
 <b>•	A String property called SupplierName with a get and set. No validation will need to be done on the supplier name this time. You may use an auto-implemented property. </b>
<br />
 <b>•	A String property called ProductName with a get and set. No validation will need to be done on the product name this time. You may use an auto-implemented property. </b>
<br />
 <b>•	A Int property called ProductID with a get and set. You will need to set up validation in the set accessor. A ProductID cannot be less than 100000 and no higher than 999999. If the ID does not fall within this range, the default value is 0.</b>
<br />
 <b>•	A String property called ProductType with a get and set. The ProductType categorizes what the product is such as “beverage” or “cereal”. </b>
<br />
<b>• 	A Double property called ProductPrice with a get and set. You will need to set up validation in the set accessor. A ProductPrice cannot be less than 0. If the price is less than 0, the default value is 0.</b>
<br />
<b>•	A int property called Aisle with a get and set You will need to set up validation in the set accessor. The aisles of the store range from 1 to 20.  If the aisle does not fall within this range, the default value is 0. </b>
<br />
<b>•	A String property called ProductType with a get and set. The ProductType categorizes what the product is such as “beverage” or “cereal”. </b>
<br />
<b>•	A method named InStock() that returns no data (void) and accepts no parameters. This method will change the product’s in-stock status to reflect that the product is in-stock by setting the in-stock status to true;</b>
<br />
<b>•	A method named OutofStock() that returns no data (void) and accepts no parameters. This method will change the product’s in-stock status to reflect that the product is out-of-stock by setting the in-stock status to false;</b>
<br />
<b>•	A method named IsOutofStock() that returns a bool and accepts no parameters. This method will return a true value when the product is in-stock and a false value when the product is out-of-stock. In other words, return the value of the bool in-stock status instance variable.</b>
<br />
<b>•	A method named ToString() that returns a String and accepts no parameters. Remember, you must also use keyword override when defining a ToString method. This method will create a formatted string that has the supplier’s name, product’s name, product ID, product type, product price, aisle, and if it is in stock each on a separate line. Precede each item with an identifying label. You may use string interpolation to create the formatted text that the method will return. You may concatenate the string literal "\n" to add a newline to the string, you can also use the string constant Environment.NewLine instead. Note well, the ToString method just builds and returns a string. It does not output of its own. That is up to client classes to perform, as the output may be directed to the console or a GUI or a web page. See the PayrollSystem or Time examples from class for an example of how ToString() should be written.</b>
<br />
<br />
<br />
In addition to the Product class, you will need to write a simple Console application to test your products. In your other class file (where the Main method is located), your simple test program must do the following:
<br />
<br />
 <b>•	Create at least 5 Product objects (you may hard code your test data) and store them in an array.
E.g., Product product1 = new Product("PepsiCo","Gatorade", 675134, "Beverage", 3.50, 4);</b> 
<br />
 <b>•	Using a method, print out all the products’ original data to the Console. Your method should be static, void and will accept the array of product objects as its parameter.</b>
<br />
 <b>•	Next, for each product, use the appropriate properties and methods to change any of the product’s properties - you must make at least two products in-stock. These changes can be hard coded (not in a loop).</b>
<br />
 <b>•	Again, using the method you wrote previously, print out all the products’ new data to the console by passing the array of product objects again to the method.</b>
<br />
 <b>•	Call the appropriate Product method to return each product that was checked out.</b>
<br />
<b>•	Finally, print all products’ data to the console (using the method you wrote previously) one last time.</b>
<br />
- <b>If the client indicates that they were in a car accident within the past year, their base rate increases by 30%.</b> 
<br />
- <b>Since our research indicates that students under 25 are likely to get into accidents, we add an extra $10.00/month youth premium to their base rate.</b>
<br />
- <b>If the user drives a car manufactured in 2012 or later, we add an extra $15.00/month new car premium to their base rate.</b>
<br />
<br />
<br />
Other requirements:
<br />
<br />
Since you are printing each product’s data to the console several times, you must write a method to accomplish this task in your test application program. As noted earlier, the method should be static, void and will accept the array of product objects as its parameter.

<h2>Languages and Utilities Used</h2>
- <b>Microsoft Visual Studio</b>
<br />
- <b>C#</b>

<h2>Environments Used </h2>
- <b>Windows 10 Pro</b>


<h2>Examples Outputs</h2>

Before making changes (Products are out of stock) 
<img src="https://i.imgur.com/66jcvxN.png" height="80%" width="80%" alt="Log into Windows"/>
<br />
<br />
After changes (Products are in stock)
<img src="https://i.imgur.com/4RbIJin.png" height="80%" width="80%" alt="dir /r"/>
<br />
<br />

<h2>Conclusion </h2>
The Grocery Store Product Management Console Application, developed using Microsoft Visual Studio in the C# programming language, offers an efficient system for managing and keeping track of grocery store products. This application effectively captures product details, from supplier name to stock status, and provides features to easily update these details. The program emphasizes validation, ensuring that the input data remains within specified parameters. Its test application demonstrates its versatility by creating, updating, and displaying product information in a clear and organized manner. The provided sample outputs showcase the application's functionality and user-friendly interface. This project is a testament to the importance of detail-oriented programming in creating practical and reliable tools for business operations.
