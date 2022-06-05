## Создать запросы в Postman.

Protocol: `http`
IP: `162.55.220.72`
Port: `5005`

### EP_1
__Method:__ GET

__EndPoint:__ /get_method

__request url params:__ 
*name:* str
*age:* int

>response:
[
    “Str”,
    “Str”
]


### EP_2
__Method:__ POST

__EndPoint:__ /user_info_3

__request form data:__
 *name:* str
 *age:* int
 *salary:* int

>response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'u_salary_1_5_year': salary * 4}}


### EP_3
__Method:__ GET

__EndPoint:__ /object_info_1

__request url params:__
 *name:* str
 *age:* int
 *weight:* int

>response: 
{'name': name,
          'age': age,
          'daily_food': weight * 0.012,
          'daily_sleep': weight * 2.5}

### EP_4
__Method:__ GET

__EndPoint:__ /object_info_2

__request url params:__ 
 *name:* str
 *age:* int
 *salary:* int

>response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }

### EP_5
__Method:__ GET

__EndPoint:__ /object_info_3

__request url params:__ 
 *name:* str
 *age:* int
 *salary:* int

>response: 
{'name': name,
          'age': age,
          'salary': salary,
          'family': {'children': [['Alex', 24], ['Kate', 12]],
                     'pets': {'cat':{'name':'Sunny',
                                     'age': 3},
                              'dog':{'name':'Luky',
                                     'age': 4}},
                     'u_salary_1_5_year': salary * 4}
          }

### EP_6
__Method:__ GET

__EndPoint:__ /object_info_4

__request url params:__ 
 *name:* str
 *age:* int
 *salary:* int

>response: 
{'name': name,
          'age': int(age),
          'salary': [salary, str(salary * 2), str(salary * 3)]}

### EP_7
__Method:__ POST

__EndPoint:__ /user_info_2

__request form data:__ 
 name: str
 age: int
 salary: int

>response: 
{'start_qa_salary': salary,
          'qa_salary_after_6_months': salary * 2,
          'qa_salary_after_12_months': salary * 2.7,
          'qa_salary_after_1.5_year': salary * 3.3,
          'qa_salary_after_3.5_years': salary * 3.8,
          'person': {'u_name': [user_name, salary, age],
                     'u_age': age,
                     'u_salary_5_years': salary * 4.2}
          }
