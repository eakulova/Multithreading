В приложении реализовано два потока: первый поток считывает введенные с клавиатуры числительные на английском языке (от 1 до 9999) и помещает их в память.
Второй поток получает из памяти минимальное значение, удаляет его и выводит данное значение на экран.
В текущей реализации в памяти могут храниться одинаковые значения, при этом при работе потока по удалению минимального значения дубли не удаляются.

Чтобы остановить приложение, необходимо ввести с клавиатуры слово 'stop'.


Для сборки приложения необходимо:
 1) установить при необходимости maven и JDK 1.8(и выше). 
 2) из директории проекта выполнить команду:
 
 ` mvn clean install`
 
 ` mvn exec:java`


