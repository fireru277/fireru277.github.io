ОТЧЕТ ПО ЛАБОРАТОРНЫМ РАБОТАМ


Лабораторная 1

Сервис по оформлению документов студентами МГТУ Станкин
Диаграмма IDEF0
![image](https://user-images.githubusercontent.com/62379084/135609190-6df09846-d2f0-4b2a-8704-042900c2de77.png)
Предложение: Студенту необходимо получить документ через бухгалтерию университета в течение 2х дней.

Диаграмма классов
![image](http://www.plantuml.com/plantuml/png/JOynYiCm44LhwnGVLxkmrPx0w_K1J5Aa7gI9BInBpeo42I5tZy0fqZxUV_0xpIIvhC7eukD6GYji85KyJDEJNIP99Rh_59BWCllCflaJIVj1-b2LAYPnB9_eQOvAUyx5SSmjI37MA4vyAwpPN7tqEhF3a6nPgmACjB7iIHPylMSOADCFXY8-JlY5exj-r_Zi7SDwiO5Dnz7L0oy0)

Диаграмма прецедентов
![image](http://www.plantuml.com/plantuml/png/fSwnJWCn30RWkNuAwoOOAl402FNAVD9jp5PYskXoSN4SEb3U7TEZwFOEaQpFVsplgf5QcpFKAPKJASr8mKJn2pPx2jD1fPNuAjdfxPYCOTEhodcHVVQ81qKZwvg-L_DQvK2LxvwO-TtG13KTZeOnAGTBKc2vTtn2gjYTMAkKxW-71IlhPmfyq_6AoX-Dg_r7LzyfOoIZ3cwdzzVcIDu-YquTZBZTuaF_2Fv-om5y__F5gn46XykBxuOTbzZc_0C0)


Лабораторная 2

Диаграмма IDEF0
![image](https://user-images.githubusercontent.com/62379084/137474499-7b2623c5-548c-45a6-b641-12cdaf4e6a76.png)
На диаграмме изображен более полный процесс работы сервиса для студентов по оформлению справок в университете
1. Студент создает запрос на оформление документа;
2. Запрос обрабатывается, если все данные заполнены корректно, и направляется в бухгалтерию;
3. После получения запроса сотрудник обращается к БД бухгалтерии для получения всех необходимых данных;
4. После получения необходимых данных сотрудник заполняет недостающие поля и оформляет документ.

PDC-диаграмма
![image](https://user-images.githubusercontent.com/62379084/137477735-57234a75-df98-4a4d-b4fd-a2387617dd5c.png)

DFD-диаграмма: Обращение к БД
![image](https://user-images.githubusercontent.com/62379084/137477939-b875d236-cb49-4305-9fd7-f7db17baa5c6.png)
1. После обработки запроса и выявлении необходимых данных для оформления документа, сотрудник обращается к базе данных;
2. Используя входные данные от подавшего запрос студента, сотрудник выявляет все оставшие полные и необходимые данные для оформления документа;
3. После получения всех необходимых данных сотрудник, используя шаблон, заполняет все недостающие поля в документе.
