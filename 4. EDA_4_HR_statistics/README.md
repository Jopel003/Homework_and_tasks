# Домашняя работа МОДУЛЬ EDA-4: "Статистические тесты в контексте EDA"

## Оглавление  
[1. Описание проекта](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Результат)  
[6. Выводы](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Выводы)     

### Описание проекта    
HR-агентство изучает тренды на рынке труда в IT. Компания хочет провести исследование на основе данных о зарплатах в сфере Data Science за 2020–2022 годы и получить некоторые выводы.

Получены [данные](https://lms-cdn.skillfactory.ru/assets/courseware/v1/9e84f30c5bc84881a5e33262d5e32a8b/asset-v1:SkillFactory+DSPR-2.0+14JULY2021+type@asset+block/ds_salaries.zip)


:arrow_up:[к оглавлению](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Оглавление)


### Какой кейс решаем?    
Исследуйте данные и сделайте выводы по полученным результатам. Подкрепите свои рассуждения и выводы визуализациями и с помощью статистического тестирования проверьте, являются ли выводы статистически значимыми.

**В процессе анализа мы должны ответить на ключевые вопросы HR-агентства:**

* Наблюдается ли ежегодный рост зарплат у специалистов Data Scientist?
* Какие факторы влияют на зарплату у специалистов Data Scientist?
* Как соотносятся зарплаты Data Scientist и Data Engineer в различных компаниях?
* Есть ли связь между наличием должностей Data Scientist и Data Engineer и размером компании?

**Если вы найдёте в данных интересные закономерности, также отметьте их в своём анализе.**

**Продемонстрируйте использование разных тестов для проверки статистической значимости сделанных выводов:**

* тесты для количественного признака:
   * для одной выборки;
   * для двух выборок;
   * для нескольких выборок;
* тест для категориальных признаков.

**Условия задания:**  
Результатом работы должен стать ноутбук (IPYNB-файл) с кодом для исследования, а также с выводами и рассуждениями, полученными на основе разведывательного анализа.


**Категории оценки**
1. **Загрузка и обработка данных (2 балла)**
   * Студент корректно загрузил данные.
   * Студент проверил датасет на наличие пропусков и дубликатов, а также на корректность типов данных столбцов.
   * Студент определил в данных неинформативные признаки, которые не будут участвовать в исследовании.
   * Студент классифицировал все признаки на числовые и дискретные.
   * Студент нашёл основные статистические характеристики для каждого из признаков.

2. **Визуальный анализ данных (2 балла)**

   Студент выполнил визуальный анализ данных.
   * Сделан базовый анализ для каждого признака, участвующего в исследовании:
      * для числовых признаков построены гистограммы, иллюстрирующие распределения;
      * для категориальных признаков определено количество записей для каждой категории и построены соответствующие визуализации.
   * Студент создал корректные визуализации, которые демонстрируют влияние каждого из признаков, участвующих в исследовании, на зарплату по всем наименованиям Data Scientist или на зарплату по всем должностям.
   * Студент на основе визуального анализа дал первичные ответы на поставленные в задании вопросы.
3. **Статистический анализ данных (2 балла)**

   В исследовании студент подтвердил или опроверг свои первичные гипотезы, полученные на этапе визуального анализа, с помощью статистических тестов:
   * Студент корректно сформулировал нулевые и альтернативные гипотезы на основе поставленных бизнес-вопросов.
   * Студент правильно выбрал статистический тест для каждой из гипотез, предварительно проверив условие его применения (там, где это необходимо):
      * проверка на нормальность;
      * проверка равенства дисперсий в группах.
   * Студент успешно протестировал данные, продемонстрировав владение различными статистическими тестами:
   * тесты для количественного признака:
      * для одной выборки;
      * для двух выборок;
      * для нескольких выборок;
   * тест для категориальных признаков.

4. **Соответствие выводов бизнес-вопросам (4 балла)**

   Студент привёл развёрнутые и обоснованные ответы по каждому вопросу:
   * Наблюдается ли ежегодный рост зарплат у специалистов Data Scientist?
   * Какие факторы влияют на зарплату у специалистов Data Scientist?
   * Как соотносятся зарплаты Data Scientist и Data Engineer в различных компаниях?
   * Есть ли связь между наличием должностей Data Scientist и Data Engineer и размером компании?<br>

   Представленные выводы корректны и соответствуют результатам, полученным в ходе статистического анализа.
5. **Дополнительное исследование (2 балла)**

   Студент самостоятельно корректно сформулировал минимум две дополнительных бизнес-гипотезы о влиянии факторов на заработную плату специалистов и для каждой гипотезы:
   * представил визуальный анализ данных;
   * произвёл статистическое тестирование;
   * сделал верные, соответствующие бизнес-вопросам выводы по полученным результатам.
6. **Оформление исследования (2 балла)**

   Студент качественно оформил решение задачи:
   * Описана постановка задачи.
   * На протяжении всего исследования прослеживается логика, ноутбук имеет понятную структуру, разделён на части заголовками.
   * Есть промежуточные выводы.
   * Все визуализации имеют подписи к осям и заголовки и соответствуют стандартам оформления.
   * Сделан финальный вывод по исследованию.
   * Код студента понятный, оформлен по стандартам PEP-8 и сопровождён комментариями.

**Метрика качества**     
Домашнее задание проверит ментор и поставит оценку. 

**Что практикуем**     
- Визуальный анализ данных.
- Статистический анализ данных.
- Учимся делать выводы на основе анализа.


### Краткая информация о данных
Оригинальный датасет: [“Data Science Job Salaries” (kaggle.com)](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)


|НАИМЕНОВАНИЕ СТОЛБЦА|ОПИСАНИЕ|
|-|-|
|work_year|Год, в котором была выплачена зарплата.|
|experience_level|Опыт работы на этой должности в течение года со следующими возможными значениями:<br> EN — Entry-level/Junior; <br>MI — Mid-level/Intermediate; <br>SE — Senior-level/Expert; <br>EX — Executive-level/Director.|
|employment_type|Тип трудоустройства для этой роли:<br>PT — неполный рабочий день;<br>FT — полный рабочий день;<br>CT — контракт;<br>FL — фриланс.|
|job_title|Роль, в которой соискатель работал в течение года.|
|salary|Общая выплаченная валовая сумма заработной платы.|
|salary_currency|Валюта выплачиваемой заработной платы в виде кода валюты ISO 4217.|
|salary_in_usd|Зарплата в долларах США (валютный курс, делённый на среднее значение курса доллара США за соответствующий год через fxdata.foorilla.com).|
|employee_residence|Основная страна проживания сотрудника в течение рабочего года в виде кода страны ISO 3166.|
|remote_ratio|Общий объём работы, выполняемой удалённо. Возможные значения:<br>0 — удалённой работы нет (менее 20 %);<br>50 — частично удалённая работа;<br>100 — полностью удалённая работа (более 80 %).|
|company_location|Страна главного офиса работодателя или филиала по контракту в виде кода страны ISO 3166.|
|company_size|Среднее количество людей, работавших в компании в течение года:<br>S — менее 50 сотрудников (небольшая компания);<br>M — от 50 до 250 сотрудников (средняя компания);<br>L — более 250 сотрудников (крупная компания).|
  
:arrow_up:[к оглавлению](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Оглавление)


### Этапы работы над проектом  
1. Загрузка и обработка данных.
2. Визуальный анализ данных.
3. Статистический анализ данных.
4. Формирование выводов по бизнес-вопросам.
5. Дополнительное исследование.
6. Оформление исследования и итоговых выводов

:arrow_up:[к оглавлению](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Оглавление)


### Результат:  
   1. Свормирован файл с результатами анализа данных в формате IPYNB,
   2. Сформированы выводы и ответы на поставленные вопросы.
   3. Данные датасета сохранены отдельно.

:arrow_up:[к оглавлению](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Оглавление)


### Выводы:  
Провереддный визуальный анализ модет немного искажать понимание некоторых факторов, которые подтверждают или опровергают математические расчеты.
Но он оечнь помогает в быстрой оценке данных.

Оказывается все возможно, если захочешь.

Буду рад зведочке сверху ⭐️⭐️⭐️

:arrow_up:[к оглавлению](https://github.com/Jopel003/My_homework/blob/main/4.%20EDA_4_HR_statistics/README.md#Оглавление)
