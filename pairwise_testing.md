Логин 
standard_user
locked_out_user
problem_user
performance_glitch_user
неверный логин
пустое поле

Пароль
верный пароль
неверный пароль 
пустое поле

### Тест-кейс №1 standard_user, верный пароль

1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "standard_user"
- В поле Password ввести "secret_sauce"
- Нажать Login
3. **Ожидаемый результат**:
- Откроется страница с каталогам товаров https://www.saucedemo.com/inventory.html 

### Тест-кейс №2 standard_user, неверный пароль
1. **Предшествующие условия**:
Пользователь не авторизован
Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "standard_user"
- В поле Password ввести "asdf"
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Username and password do not match any user in this service
- 
### Тест-кейс №3 standard_user, пустой пароль
1. **Предшествующие условия**:
Пользователь не авторизован
Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "standard_user"
- Поле Password оставить пустым
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Password is required


### Тест-кейс №4 locked_out_user, верный пароль

1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "locked_out_user"
- В поле Password ввести "secret_sauce"
- Нажать Login
3. **Ожидаемый результат**:
- Появится сообщение: Epic sadface: Sorry, this user has been locked out.
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.

### Тест-кейс №5 locked_out_user, неверный пароль
1. **Предшествующие условия**:
Пользователь не авторизован
Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "locked_out_user"
- В поле Password ввести "asdf"
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Username and password do not match any user in this service

### Тест-кейс №6 locked_out_user, пустой пароль
1. **Предшествующие условия**:
Пользователь не авторизован
Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "locked_out_user"
- Поле Password оставить пустым
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Password is required

### Тест-кейс №7 problem_user, верный пароль

1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "problem_user"
- В поле Password ввести "secret_sauce"
- Нажать Login
3. **Ожидаемый результат**:
- Откроется страница с каталогам товаров https://www.saucedemo.com/inventory.html 

### Тест-кейс №8 problem_user, неверный пароль
1. **Предшествующие условия**:
Пользователь не авторизован
Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "problem_user"
- В поле Password ввести "asdf"
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Username and password do not match any user in this service


### Тест-кейс №9 problem_user, пустой пароль
1. **Предшествующие условия**:
Пользователь не авторизован
Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "problem_user"
- Поле Password оставить пустым
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Password is required


### Тест-кейс №10 performance_glitch_user, верный пароль

1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "performance_glitch_user"
- В поле Password ввести "secret_sauce"
- Нажать Login
3. **Ожидаемый результат**:
- Откроется страница с каталогам товаров https://www.saucedemo.com/inventory.html 

### Тест-кейс №11 performance_glitch_user, неверный пароль
1. **Предшествующие условия**:
Пользователь не авторизован
Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "performance_glitch_user"
- В поле Password ввести "asdf"
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Username and password do not match any user in this service

### Тест-кейс №12 performance_glitch_user, пустой пароль
1. **Предшествующие условия**:
Пользователь не авторизован
Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "performance_glitch_user"
- Поле Password оставить пустым
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Password is required


### Тест-кейс №13 неверный логин, верный пароль
1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "Fail"
- В поле Password ввести "secret_sauce"
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Username and password do not match any user in this service

### Тест-кейс №14 неверный логин, неверный пароль
1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "Fail"
- В поле Password ввести "Fail"
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Username and password do not match any user in this service

### Тест-кейс №15 неверный логин, пустой пароль
1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- В поле Username ввести "Fail"
- Поле Password оставить пустым
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Password is required


### Тест-кейс №16 пустой логин, верный пароль
1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- Поле Username оставить пустым
- В поле Password ввести "secret_sauce"
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Username is required

### Тест-кейс №17 пустой логин, неверный пароль
1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- Поле Username оставить пустым
- В поле Password ввести "fail"
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Username is required

### Тест-кейс №18 пустой логин, пустой пароль
1. **Предшествующие условия**:
- Пользователь не авторизован
- Открыта страница авторизации https://www.saucedemo.com/
2. **Шаги**: 
- Поле Username и Password оставить пустым
- Нажать Login
3. **Ожидаемый результат**:
- Поля Username и Password подчеркнуты красным в конце полей появился знак крестика в красном кружке.
- Появится сообщение об ошибке: Epic sadface: Username is required



