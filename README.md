# Отчёт о тестировании KeyValidator

## Краткое описание

17.11.2020 было проведено тестирование документации, тестирование установки, тестирование на совместимость, санитарное тестирование приложения KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* <a href="https://github.com/fromkerch/task1-IDE-/issues/2">Некорректная валидация ключей</a>

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md">Инструкция по установке OpenJDK 11</a>
* <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md">Руководство использования</a>



В качестве тестовых данных использовались данные:
* <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md">Инструкция по установке OpenJDK11</a>
Ожидаемый результат: работает на нашей ОС.
*  <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class">Приложение KeyValidator</a> 
Ожидаемый результат: запускается и совместимо с Java 11. Работает согласно руководству использования
 

Тестирование производилось в следующем окружении:
* Windows 10 Pro x64
* java version "11.0.5"
