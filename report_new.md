# Отчёт о тестировании программы Credit Card Number Validator

## Кусок приложения, направленный на проверку валидации номера банковской карты.

13 апреля 2021 г. было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 3 ч

В результате тестирования выявлены следующие дефекты:
* [Credit Card Number Validator] Валидный номер карты, содержащий больше 16 символов, определяется как не валидный 
https://github.com/EkaterinaSkobeleva/11JavaHomeworkEx1/issues/1
* [Credit Card Number Validator] Валидный номер карты, содержащий меньше 16 символов, определяется как не валидный 
https://github.com/EkaterinaSkobeleva/11JavaHomeworkEx1/issues/2



## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* чек-лист проверок валидации номеров банковских карт https://docs.google.com/spreadsheets/d/10lkMhsIE-GDRAt5ygQhue3cH1iTb08YMAEA7HeyO_Tg/edit?usp=sharing


В качестве тестовых данных использовались данные с ресурса freeformatter.com:

* банковские карты с фейковыми номерами. Ожидаемый результат при проверке номеров карт - номер валиден.


Тестирование производилось в следующем окружении:

*  OS Microsoft Windows 10 Домашняя, Версия 19042.867, Разрядность x64
*  Окружение Java OpenJDK11U-jdk_x64_windows_hotspot_11.0.10_9
*  IntelliJ IDEA Community 2020.3.3