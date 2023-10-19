# Walmart2023
React
i)Create a new project "empmanamegement"
Create a component EmployeeList which has array of employee objects.
Each object has three properties (id,name,salary) (Consider 5 objects minimum)
The component should render these in a <table> tag. 

------------------------------------------------------------------------------------
Modify "empmanamegement" project in such way -
We need to create 2 components in application.
i) EmployeeList - which has array of employee objects.
Each object has three properties (id,name,salary) (Consider 5 objects minimum)

ii) Employee component - which renders each record using <tbody> tag.
    this component accept three properties (id,name,salary)

NOTE:- Employee is child component of EmployeeList
           Place the EmployeeList component into the App Component.	


------------------------------------------------------------------------------------
Modify "empmanamegement" project in such way -
Modify Employee component - which renders each record using <tbody> tag with a button with Delete caption
          When user clicks a button , id value should be passed from child(Employee) to parent(EmployeeList) and Parent component prints id on Console

------------------------------------------------------------------------------------

Modify "empmanamegement" project in such way -
Modify Employee component - which renders each record using <tbody> tag with a button with Delete caption
          When user clicks a button , confirm box should be shown by child , if user confirms delete pass confirmation as string along with id value to Parent component (EmployeeList) from child(Employee) and Parent component prints Record deleted with id OR No Message

------------------------------------------------------------------------------------
Modify "empmanamegement" project in such way -
After confirmation from user record is deleted and UI is updated accordingly.



------------------------------------------------------------------------------------

Modify "empmanamegement" project in such way -
After deleting record successfully appropriate message MUST be shown to user.

------------------------------------------------------------------------------------
Modify previous project in such way -
Create a seperate file EmployeeDataService having a function findAllEmployees() which returns array of Employee Objects.
EmployeeList Component should fetch array from findAllEmployees() function



------------------------------------------------------------------------------------

Modify "empmanamegement" project in such way -
Create a Component SearchEmployee which renders a input text which accepts salary from user.
What ever value user has entered all employees whose salary is greater than entered salary should be shown
NOTE: - SearchEmployee is child of EmployeeList


------------------------------------------------------------------------------------

Modify "empmanamegement" project in such way -
While accepting value in search employee make sure to check if user enters number ONLY.
Also make sure that to update GUI only when user enters at least 2 digit number.
Concept:- state management, Validation

-----------------------------------------------------------------------------------------------------------------------
Modify "empmanamegement" project in such way -
Modify Employee component - which renders each record using <tbody> tag with a button with Update caption
          When user clicks a button , form should be shown with selected data with three input fields and a PerformUpdate button.
          NOTE: - form should be shown in EmployeeList Component with data
          NOTE:- Id field is readonly.
          After Clicking PerformUpdate button record should be updated and GUI should be updated and update form should be invisible.
	
----------------------------------------------------------------------------------------------------------------------------------
Modify "empmanamegement" project in such way -
	When user is filling update form if name is NOT entered OR name field contains less than 6 characters error messgae MUST be shown
	also PerformUpdate button should be disabled.
	
------------------------------------------------------------------------------------------------------------------------

Modify "empmanamegement" project in such way -
Modify EmployeeList component - renders a button for add new employee record.
          When user clicks a button , form should be shown with with three input fields and a Add button.
          NOTE: - form should be shown in EmployeeList Component   	
          NOTE:- Id value MUST be automatically incremented.
          After Clicking Add button record should be inserted and GUI should be updated.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Modify "empmanamegement" project in such way -
	When user is filling add form if name is NOT entered OR name field contains less than 6 characters error messgae MUST be shown
	also PerformUpdate button should be disabled.
