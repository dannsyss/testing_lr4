## Вариант №21
1. По клиенту получены зашумленные данные (объект s1 типа Series) по его транзакциям:
s1 = pd.Series(data=['7', 4, 8.3, 'hi!', 15, -52, 12.42, 's123', 120.1, 58], index=range(6, 26, 2))
Выберите из s1 элементы с индексами 8 и 14, сложите их, из полученного результата
вычтите количество целочисленных элементов (имеющих тип int), ответ сохраните в
переменную s2.
2. Считайте в переменные tr_mcc_codes и transactions из одноимённых таблиц из папки data.
Для таблицы transactions используйте только первые n=500000 строк. Обратите внимание
на разделители внутри каждого из файлов – они могут различаться. Проверьте
содержимое созданных датафреймов.
3. Рассчитайте медиану суммы транзакций по полю amount из таблицы transactions по
строкам, отсортированным по полю amount в порядке убывания, и из которых удалены
дублирующиеся по столбцам [mcc_code, tr_type] строки, причём при удалении
соответствующих дублей остаются только последние из дублирующихся строк
(keep='last').
