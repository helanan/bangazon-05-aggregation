# bangazon-05-aggregation
Modified the Department class so that Employees can be aggregated into them

Bangazon Orientation - Aggregation

Instructions

For this exercise, you need to modify the Department class so that Employees can be aggregated into them. In its constructor, initialize an empty set named self.employees.

Create three new methods.

add_employee(self, employee) - Add an employee to the set. The employee parameter accepts an existing instance of an employee.
remove_employee(self, employee) - Removes an employee from the set. The employee parameter accepts an existing instance of an employee.
get_employees(self) - Returns the set of employees.
Write a module that creates an instance of each of your Departments that you have defined. Then create two or three Employee instances for each Department, and add them to the appropriate Department instance.

Once you have defined all of your Employees and Departments, write logic to output the name of each Department, and the first/last name of each employee it contains to the command line.

Example CLI Output

Department: Sales
   Andri Alexandrou
   Wayne Hutchinson
   Sephora Rodriguez
   Matt Qualls
   Jen Solima

Department: Technology
   Caitlin Stein
   Ryan Tanay
   Jessawynn Parker
   Damon Romano
Once you've completed this basic output, modify it to display any other properties that might be applied to either the Department or Employee that you added from the previous exercises (e.g. handicap, employment status, etc.)
