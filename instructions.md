# Instructions

<details>
  <summary>
    ✅ Create Project in PyCharm
  </summary>

  - Create a project in PyCharm (do not create any sub folders)
  - Create main.py, part1.py
</details>

<details>
  <summary>
    Dictionary Operations: (50 pts)
  </summary>

  - You will be given **ONE** complex dictionary similar to the example given below
  - You will be asked to perform 10 operations
  - All dictionary operations will be performed in a function `employee_ops()`, inside part1.py
  - This function will be called in main.py inside main() function
</details>


## Employee Operations

<details>
  <summary>
    Employee Dictionary Structure:  
  </summary>

  - It is a complex dictionary with integral keys
  - (int) -> (dictionary)
    - "name" -> (string)
    - "dept" -> (string)
    - "projects" -> (list of strings)
    - "titles" -> (set of strings)
    - "certifications" -> (dictionary)
      - (string) certification code -> (string) date taken YYYY-MM-DD format

  Download employees.bin https://github.com/suchialex/CINS3002-CW09/blob/main/employees.bin
</details>

### In employee_ops() function, perform these operations

<details>
  <summary>
    ✅ 1. Unpickle
  </summary>
  
  - Unpickle the dictionary in employees.bin and store in a variable of your choice
</details>


<details>
  <summary>
    ✅ 2. Add certification
  </summary>
  
  - For emp ID 04567 add a new certification EVA-L2 taken on March 22, 2023
</details>


<details>
  <summary>
    ✅ 3. Add title for employee
  </summary>

  - Get user input for employee name
  - Add a new title - `SGA President` for that employee (case-insensitive name search)
</details>


<details>
  <summary>
    ✅ 4. Salary Increment
  </summary>

  - For all the programmers, give a salary **increment** of 5000
  - Must be case in-sensitive, i.e. you have to look for Programmer or PROGRAMMER or programmer as title 
  - Hint: you may have to use list comprehension to convert all the titles to lowercase
  - If the employee doesn't have any salary, set the salary at 30000
</details>


<details>
  <summary>
    ✅ 5. Add new certification
  </summary>
  
  - Get user input for employee ID
  - If that employee is present,
  - Add a new certification OCPL1 for that employee, the date certification is taken is March 10, 2023 (convert this date into the correct format)
</details>


<details>
  <summary>
    ✅ 6. Change project name
  </summary>
  
  - Mayfield Inc project is taken over by Roundpoint Inc, so change all occurences of that project with the new name
</details>


<details>
  <summary>
    ✅ 10. Add title
  </summary>
  
  - For anyone who has a certification that starts with OCPL1, add a title called Oracle Developer
</details>


<details>
  <summary>
    ✅ 11. Display Spring Valley Employees
  </summary>
  
  - Print the name and salaries of all the employees who are working on the project Spring Valley.
  - Choose a nice format and alignment so they are displayed in a tabular fashion. If name or salary not available, print `-`
</details>


<details>
  <summary>
    ✅ 12. Fix missing employee names
  </summary>
  
  - Check the dictionary for any employee who might be missing a name, and if missing, print their ID and ask the user to set a name
  - Make sure that name doesn't have any special characters except space and first letter of each word must be uppercase (You may implement it in a function named validate_name, or just a while loop)
</details>


<details>
  <summary>
    ✅ 13. Pickle dictionary
  </summary>
  
  - Pickle this dictionary and save it in a file named employees2.bin
</details>


<details>
  <summary>
    ✅ 14. Copy Code to replit
  </summary>
  
  - Create a new repl App named Exam2Prep
  - Copy main.py and part1.py
</details>



