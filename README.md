# Code-for-salary-calculation

Name_of_Employee = input('Enter the Name of Employee: ')

Number_of_day_present = int(input('enter the number of days: '))

Post=input('Enter the post: ')
    
if (Post=='Manager'):
    if Number_of_day_present<=31:
        salary_of_manager=2000*Number_of_day_present
        print('Salary of', Name_of_Employee,'is',salary_of_manager,'Rs')
    else:
        print('No. of Days should be less than 31')
        
elif (Post=='Leader'):
    if Number_of_day_present<=31:
        salary_of_leader=1800*Number_of_day_present
        print('Salary of', Name_of_Employee ,'is',salary_of_leader,'Rs')
    else:
        print('No. of Days should be less than 31')
        
elif (Post=='Member'):
    if Number_of_day_present<=31:
        salary_of_Member=1800*Number_of_day_present
        print('Salary of',Name_of_Employee,'is',salary_of_Member,'Rs')
    else:
        print('No. of Days should be less than 31')
        
else:
    print('Please enter then Right Post')
