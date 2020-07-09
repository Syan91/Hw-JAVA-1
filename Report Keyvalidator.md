# Отчёт о тестировании KeyValidator

# Краткое описание

07.07.2020 13-30 - 07.07.2020 20-00 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 6,5 часа

В результате тестирования выявлены следующие дефекты:
* [Bug Результат OK при введении невалидного ключа](https://github.com/Syan91/Hw-JAVA-1/issues/1)
* [Bug Результат FAIL при введении валидного ключа](https://github.com/Syan91/Hw-JAVA-1/issues/2)

*Описание процесса тестирования*
В процессе тестирования использовались следующие артефакты:
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

В качестве тестовых данных использовалось [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

*Валидные ключи:*
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 (ответ системы OK-ключ валидный)
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 (ответ системы OK-ключ валидный)
* b295bc63-9f03-3b4b-af80-969b39f8c262 (ответ системы OK-ключ валидный)
* 387eedc6-12e9-3b32-9881-63b6b5e85317 (ответ системы OK-ключ валидный)
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 (ответ системы OK-ключ валидный)

*Невалидные ключи:*

* 18252235-78e0-44a5-8720-556f0c7da17a (ответ системы FAIL-ключ невалидный)
* e66075b6-ddad-445e-baf6-161b3289522b (ответ системы FAIL-ключ невалидный)
* b6d53250-f07e-4352-a293-6102ddf7f1ca (ответ системы FAIL-ключ невалидный)
* c2bc778a-1cb9-46c6-b435-0489649d2a42 (ответ системы FAIL-ключ невалидный)
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 (ответ системы FAIL-ключ невалидный)

# Тестирование производилось в следующем окружении:

* Macbook Pro 13, Os X El Capitan версия 10.11.6, 
* openjdk version "11.0.7" 2020-04-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)
