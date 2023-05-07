Download Link: https://assignmentchef.com/product/solved-inheritance-and-exception-handling
<br>
The ability to use methods and variables from another class is critical to the Java programming language. This week inheritance and exception handling techniques are explored. Since performance is an issue with Exception handling is important to use them only for compiler checked errors. To identify the checked exceptions is essential to developing efficient coding.

<strong>Assignment:</strong>

GoBank has been asked to go back and reprocess the loan payments for a car loan of $18,875. The car loan is a 0% interest loan. The loan is for 60 months. The customer does not believe the bank has the correct outstanding balance for her loan ($12,500). The customer has copies of 20 payments made to the bank. A clerk makes a copy of the payments and enters them into a file.

To verify the banks total, read the file and write a program using a CarLoan class that extends the BankAccount class (found on page 671 – 672 in the textbook).

The CarLoan class has the following features.

<em>1)</em> An overload constructor that initializes the car loan balance. <em>(Hint: Uses super to set the balance.)</em>

<strong>Create a CarLoanClient class that</strong>

<ol>

 <li>Create CarLoan object (see CheckingAccountClient line 9 on page 667).</li>

 <li>Read the file one payment at a time <em>(Include exception handling code see example on page 755</em>).</li>

 <li>Use the payment read from the file to pass the information to method to calculate the outstanding balance. <em>Hint: Use the withdrawal method.</em></li>

 <li>Printout the payment number, payment amount and outstanding balance.</li>

 <li>Continue to process for each payment until the end of the file.</li>

</ol>

Create a text file with the following numbers.

<strong>Monthly Payment</strong>315 451 315 374 353 315 450 484 412 315 495 476 321 315 406 329 326 356 315 325

<em>Make a screenshot of the output and include it as an attachment to the Week 7 Assignment. Also, include the program code in a text file to run on another computer.</em> <em>Comment the code to receive full credit (see page 45).</em>