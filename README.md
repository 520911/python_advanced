# Import. Module. Package

1. Разработать **структуру** программы "Бухгалтерия". 
- main.py;  
- директория application:  
-- salary.py;  
-- директория db:  
\--- people.py;  
main.py - основной модуль для запуска программы.  
В модуле salary.py функция calculate_salary.  
В модуле people.py функция get_employees.  

2. Импортировать функции в модуль main.py и вызывать эти функции в конструкции.
```
if __name__ == '__main__':
```

\*3. Создать рядом с файлом main.py модуль dirty_main.py и импортировать все функции с помощью
конструкции (необязательное задание)
```
from package import *
``` 
