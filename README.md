## Краткое описание
#### Тестирование выполнил студент QA-6 Мельников Артем

•  Начало тестирование 29.04.20 

•  Конец тестирование 29.04.20

•  На тестирование затрачено: <1 час>

### В процессе тестирования необходимо было протестировать:
1.  Инструкцию по установке OpenJDK11 работает под вашу ОС
2.  Приложение запускается и совместимо с Java 11
3.  Приложение работает согласно руководству использования
#### Выполнялось при помощи видов тестирование:
* Тестирование Установки (Installation Testing)

## Описание процесса тестирования

В процессе тестирования использовались следующие **test case**:

•  Инструкция по установке OpenJDK 11  
•  Руководство использования               

## Bug report: Инструкция по установке OpenJDK 11
При тестировании test case: 
**Инструкция по установке OpenJDK 11**

Дефектов и отклонений выявлено не было.  
Приложение работает под **OC Windows 10pro** и запускается совместимо с **Java 11**

`openjdk version "11.0.7" 2020-04-14`

`OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)`

`OpenJDK Client VM AdoptOpenJDK (build 11.0.7+10, mixed mode)`

Приложение работает согласно руководству использования.

**Status: PASSED**

## Bug report: Руководство использования  KeyValidator
***В качестве тестовых данных использовались данные***:
* [Руководство использования KeyValidator](<https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md>)

## После тестирования было выявлено такие данные:

**java KeyValidator** 00000000-0000-0000-0000-000000000000 00000000-0000-0000-0000-000000000001

**Result for** 00000000-0000-0000-0000-000000000000:**FAIL**

**Result for** 00000000-0000-0000-0000-000000000001:**FAIL**
### Валидные ключи:
* `$ java KeyValidator` 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
**Result for** 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998:**OK**

* `$ java KeyValidator` 80b427f8-92cd-3aae-ba04-3927fbe17c6
**Result for** 80b427f8-92cd-3aae-ba04-03927fbe17c6:***FAIL***

* `$ java KeyValidator` b295bc63-9f03-3b4b-af80-969b39f8c262
**Result for** b295bc63-9f03-3b4b-af80-969b39f8c262:**OK**

* `$ java KeyValidator` 387eedc6-12e9-3b32-9881-63b6b5e85317
**Result for** 387eedc6-12e9-3b32-9881-63b6b5e85317:***FAIL***

* `$ java KeyValidator` c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
**Result for** c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180:**OK**
## Невалидные ключи:
* `$ java KeyValidator` 18252235-78e0-44a5-8720-556f0c7da17a
**Result for** 18252235-78e0-44a5-8720-556f0c7da17a:**FAIL**
* `$ java KeyValidator` e66075b6-ddad-445e-baf6-161b3289522b
**Result for** e66075b6-ddad-445e-baf6-161b3289522b:**FAIL**
* `$ java KeyValidator` b6d53250-f07e-4352-a293-6102ddf7f1ca
**Result for** b6d53250-f07e-4352-a293-6102ddf7f1ca:**FAIL**
* `$ java KeyValidator` c2bc778a-1cb9-46c6-b435-0489649d2a42
**Result for** c2bc778a-1cb9-46c6-b435-0489649d2a42:**FAIL**
* `$ java KeyValidator` 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1
**Result for** 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1:***OK*** 
### В процессе тестирования данного приложения было выявлено отклонения:
#### Валидные ключи:
***80b427f8-92cd-3aae-ba04-3927fbe17c6
387eedc6-12e9-3b32-9881-63b6b5e85317***
#### Невалидные ключи:
***2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1***

**STATUS:FAILED**

## Тестирование производилось в следующем окружении:
* Windows 11pro x86
* Java 11
