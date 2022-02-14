# [СЕМИНАРЫ 3-4](https://github.com/fireru277/fireru277.github.io/wiki)  
# [КУРСОВОЙ ПРОЕКТ](https://github.com/fireru277/fireru277.github.io/wiki/Курсовой-проект)

# ОТЧЕТ ПО ЛАБОРАТОРНЫМ РАБОТАМ


## <details><summary><b>Лабораторная 1</b></summary>

Сервис по оформлению документов студентами МГТУ Станкин.

### Диаграмма IDEF0

![image](https://user-images.githubusercontent.com/62379084/135609190-6df09846-d2f0-4b2a-8704-042900c2de77.png)
Предложение: Студенту необходимо получить документ через бухгалтерию университета в течение 2х дней.

### Диаграмма классов

![image](http://www.plantuml.com/plantuml/png/JOynYiCm44LhwnGVLxkmrPx0w_K1J5Aa7gI9BInBpeo42I5tZy0fqZxUV_0xpIIvhC7eukD6GYji85KyJDEJNIP99Rh_59BWCllCflaJIVj1-b2LAYPnB9_eQOvAUyx5SSmjI37MA4vyAwpPN7tqEhF3a6nPgmACjB7iIHPylMSOADCFXY8-JlY5exj-r_Zi7SDwiO5Dnz7L0oy0)

### Диаграмма прецедентов

![image](http://www.plantuml.com/plantuml/png/fSwnJWCn30RWkNuAwoOOAl402FNAVD9jp5PYskXoSN4SEb3U7TEZwFOEaQpFVsplgf5QcpFKAPKJASr8mKJn2pPx2jD1fPNuAjdfxPYCOTEhodcHVVQ81qKZwvg-L_DQvK2LxvwO-TtG13KTZeOnAGTBKc2vTtn2gjYTMAkKxW-71IlhPmfyq_6AoX-Dg_r7LzyfOoIZ3cwdzzVcIDu-YquTZBZTuaF_2Fv-om5y__F5gn46XykBxuOTbzZc_0C0)
</details>

##  <details><summary><b>Лабораторная 2</b></summary>

### Диаграмма IDEF0:

![image](https://user-images.githubusercontent.com/62379084/137474499-7b2623c5-548c-45a6-b641-12cdaf4e6a76.png)


### PDC-диаграмма:

![image](https://user-images.githubusercontent.com/62379084/137477735-57234a75-df98-4a4d-b4fd-a2387617dd5c.png)
На диаграмме изображен более полный процесс работы сервиса для студентов по оформлению справок в университете
1. Студент создает запрос на оформление документа;
2. Запрос обрабатывается, если все данные заполнены корректно, и направляется в бухгалтерию;
3. После получения запроса сотрудник обращается к БД бухгалтерии для получения всех необходимых данных;
4. После получения необходимых данных сотрудник заполняет недостающие поля и оформляет документ.

### DFD-диаграмма: Обращение к БД

![image](https://user-images.githubusercontent.com/62379084/137477939-b875d236-cb49-4305-9fd7-f7db17baa5c6.png)
1. После обработки запроса и выявлении необходимых данных для оформления документа, сотрудник обращается к базе данных;
2. Используя входные данные от подавшего запрос студента, сотрудник выявляет все оставшие полные и необходимые данные для оформления документа;
3. После получения всех необходимых данных сотрудник, используя шаблон, заполняет все недостающие поля в документе.

!!!(P.S. Не нашла как сделать БД в виде хранилища. Подразумеваю, что на диаграмме серый прямоугольник - хранилище, а не внешняя сущность.)!!!

### Диаграмма прецедентов

![image](https://www.plantuml.com/plantuml/png/fSwnQWCn30RWENeASLCx1Fe0fUIkNGzkwonivMBEPnsoJ8QcxrudRahs3WRn-KU_3jb8hQmHyXBIHaehaZDH_8BTG6wPLKhoxn8hVPw2CUnwLJat6MADrA2ePtsaxuTz9REZpF_U6FbeQ88QvfEX3yhEWYHezqulI1cxi-Z2sltYsD2BAoidk_FKb8p-WZSvbXYnyVte_lP1syOKGvgl_Hz31nFkz_ZKFqDzrt64slzwgTC4OuNBM-s60oTVrlW3)
</details> 
  
##   <details><summary><b>Лабораторная 3</b></summary>

### DFD-диаграмма (А2)

![image](https://user-images.githubusercontent.com/62379084/139420183-02c2e41f-7c33-4d51-814b-06519d00f7a3.png)

#### Диаграмма последовательности:
[текст](http://www.plantuml.com/plantuml/uml/JO_FIWCn4CRFdQS8FGfz0m-rFe17psaIR6Xs8vEi7bJe7y-2KF3i6onYKRHkNs7oHcRDXdW8kpE_-RwPR-eyHzzK1jnIrzSSUSM4uSwnEnZDk5XUeMrgUMwDHNQvq5x1w0pHtgREpCIHE6XHAlpVUW18DaxXZHQASSV6z4hxiA8t-WnhHaVg67NXCRuL7UYRzlGJoTCuIozwqoHyePQESQmBw_50jVn3yKCVXLARkRGYQNVKqLVOqg5V43QPn-2-SSDTOKDjs8HjiP_BX9vfLnIDLBNFaZXExzaJSixJ-yca5qDy_NzA0IdBIQorB4L_PAc6aqeZRmHOQAbOfQgvGfSAeL4ObO5VMEbWgchPLEON)

![image](https://user-images.githubusercontent.com/62379084/139420067-494af6e5-22c4-43cb-9716-fb8c37399da5.png)

Студент направляет запрос по оформлению документа в сервисе.
Сервис обрабатывает запрос с помощью данных БД и после направляет сотруднику.
Сотрудник обрабатывает данные (обработка состоит с проверке, нахождении необходимых дополнительных данных, проверке корректности и тд).
После сотрудник оформляет документ и направляет заказчику уведомление о готовности.
Данные записываются в БД и после получения документа студентом запрос закрывается.

### ER-диаграмма:
[текст](http://www.plantuml.com/plantuml/uml/JO_FIWCn4CRFdQS8FGfz0m-rFe17psaIR6Xs8vEi7bJe7y-2KF3i6onYKRHkNs7oHcRDXdW8kpE_-RwPR-eyHzzK1jnIrzSSUSM4uSwnEnZDk5XUeMrgUMwDHNQvq5x1w0pHtgREpCIHE6XHAlpVUW18DaxXZHQASSV6z4hxiA8t-WnhHaVg67NXCRuL7UYRzlGJoTCuIozwqoHyePQESQmBw_50jVn3yKCVXLARkRGYQNVKqLVOqg5V43QPn-2-SSDTOKDjs8HjiP_BX9vfLnIDLBNFaZXExzaJSixJ-yca5qDy_NzA0IdBIQorB4L_PAc6aqeZRmHOQAbOfQgvGfSAeL4ObO5VMEbWgchPLEON)

![image](https://user-images.githubusercontent.com/62379084/139420928-91e7c09c-a5c9-4338-873d-cbaf10179024.png)

"Запрос" является частью Базы данных, которая используется в сервисе, и состоит из: id запроса, Документа, Студента и Статуса.
</details>
