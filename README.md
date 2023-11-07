# Ex. No: 4 Creating Procedures using PL/SQL
## Date:

## AIM: To create a procedure using PL/SQL.

## Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

## Program:
```
 create or replace procedure insert_emp_data AS
  2  begin
  3  insert into employeebl1 (Empid,Empname,Dept,Salary)
  4  values(1,'DEEPIKA','FINANCE',190000);
  5  insert into employeebl1 (Empid,Empname,Dept,Salary)
  6  values(2,'MIKE','MD',350000);
  7  insert into employeebl1 (Empid,Empname,Dept,Salary)
  8  values(3,'RAM','HR',750000);
  9  commit;
 10  end;
 11  /

Procedure created.

SQL> begin
  2  insert_emp_data;
  3  end;
  4  /

PL/SQL procedure successfully completed.
```
## Output:
![dbmsexp4new](https://github.com/deepikasrinivasans/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119393935/fff493e7-968b-4903-9847-0b9aa28fb448)
![dbmsexp42newout](https://github.com/deepikasrinivasans/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119393935/024ddaff-6bca-4b23-8fec-5031699524bb)

## Result:
Thus the procedure has been sucessfully created in Pl/SQL.
