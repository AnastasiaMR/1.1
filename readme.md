
# Отчёт о тестировании "KeyValidator"

## Краткое описание

22.02.2021-22.02.2021 были проведены тестирование установки и функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 4 часа

В результате тестирования выявлены следующие дефекты:
* [Ключ не валидный 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 валиден](https://github.com/AnastasiaMR/1.1/issues/1#issue-807481990)
* [Ключи валидные 387eedc6-12e9-3b32-9881-63b6b5e85317, 80b427f8-92cd-3aae-ba04-3927fbe17c6 не валидены](https://github.com/AnastasiaMR/1.1/issues/2#issue-807482499)



## Описание процесса тестирования


В качестве тестовых данных использовались данныеиз документов «Инструкция по установке OpenJDK 11» и «Руководство использования KeyValidator»:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 ОК
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 
* b295bc63-9f03-3b4b-af80-969b39f8c262 ОК
* 387eedc6-12e9-3b32-9881-63b6b5e85317 ОК
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 ОК
* 18252235-78e0-44a5-8720-556f0c7da17a Fail 
* e66075b6-ddad-445e-baf6-161b3289522b Fail
* b6d53250-f07e-4352-a293-6102ddf7f1ca Fail
* c2bc778a-1cb9-46c6-b435-0489649d2a42 Fail
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 Fail


Тестирование производилось в следующем окружении:
* Windows 10 Pro 64-разрядная операционная система 
* Java 11.0.10
