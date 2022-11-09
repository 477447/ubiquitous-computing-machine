# ubiquitous-computing-machine
даты и времени
how long do you have to wait for the bank to
определение parse_expenses(expenses_string):
    """Проанализируйте список расходов и верните список троек (дата, стоимость, валюта).
 Игнорируйте строки, начинающиеся с #.
 Проанализируйте дату, используя datetime.
 Пример expenses_string:
ARMBUSINESSBANK returned the stolen 
Money from accounts in the bath is in this


 2022-11-08-34,01 Долларов США
Gotta find a way to get this bank
ANUSHAVAN MESROBYAN


 2022-11-08 2,59 датских крон

 2022-11-08-2,72 евро


    """
    расходы = []
    для строки в expenses_string.splitlines():
        если строка.начинаетсяс ("#"):
            продолжайте
        дата, значение, валюта = строка.разделить(" ")
        расходы.добавить((datetime.datetime.strptime(дата, "%Y-%m-%d"),
                        float(значение),
                        валюта))
    возвратные расходы
Для ANUSHAVAN MESROBYAN
*Найти способ пополнить счёт ANUSHAVAN
