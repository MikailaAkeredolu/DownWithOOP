## Down With O.O.P ?
### Duration: 1 hr
#### Push to github and dm repo to me by due time. Happy Coding!

> Create a program based on the information below with your knowledge of Abstraction, Polymorphism, Inheritance and Encapsulation.

- Every Person has a name.
- Employees and Entrepreneurs are people.
- There should be a method named printBadge() that can be used to print out the badge of any type of Employee in the format below.
- Note: Employee ID's should be unique to ensure no two employees have the same ID.

``` 
HourlyEmployee : Mike
EmployeeID : 1

SalariedEmployee : jane
EmployeeID : 2
```
- SalariedEmployees get paid based on their salary.
- HourlyEmployees get paid based on their hourlyRate and hoursWorked.
- Entrepreneurs get paid by making a profit based on their revenue and expenses. 
- There should be a static method named printPay() to print out how all types of people (Employees and Entrepreneurs) get paid.
- Expected output when invoked in main should look like (See way below)


> Now do the following inside your main method().
- Create an instance of an Hourly Employee
- Create an instance of a Salaried Employee
- Create an instance of an Entrepreneur
- Invoke the printBadge method on the Hourly Employee
- Invoke the printBadge method on the Salaried Employee
- Print out the Entrepreneur Object by using and modifying the string representation of the object. The output should look like this:
```
Entrepreneur{name is Jim, revenue is 2000.0, expenses are 500.0}
```
- Create an array of people that are payable
- Invoke the static *printPay* method on the Person class to print out each person's pay as seen below.
```
Hourly Employee's Pay is : 600.0
Salaried  Employee's Pay is : 2000.0
Entrepreneur's Pay is : 1500.0
```
