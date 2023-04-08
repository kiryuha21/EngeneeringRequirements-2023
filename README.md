# EngeneeringRequirements-2023

## Краткое описание продукта:

__Назначение:__ Создание профиля с информацией о профессиональных навыках, умениях и достижениях, который можно использовать для создания резюме различных форматов и под разнообразные платформы поиска вакансий.

__Цель__: ускорить процесс создания и подачи профессионального резюме для соискателя работы

__Основные функции__: 
* Заполнение профиля как вручную, так и с помощью различных уже созданных аккаунтов посредством API
* Конвертация необходимой части профиля в различные форматы
* Интеграция с платформами для поиска вакансий и платформами, где необходимы профессиональные данные

## Интервью:

_Аналитик:_ Какие функции важны?<br />
_Заказчик:_ Пользователю нужно позволить создавать резюме, давать доступ к резюме работодателям, экспортировать на сайты агрегаторы


_Аналитик:_ Каких клиентов нам нужно поддерживать?<br />
_Заказчик:_ Нужна поддержка Desktop-версии


_Аналитик:_ Сколько у нас планируется ежемесячных пользователей?<br />
_Заказчик:_ 10 000


_Аналитик:_ Сколько раз пользователь обычно посещает сайт?<br />
_Заказчик:_ Если создает резюме с нуля, то может редактировать хоть каждый день, в будущем достаточно заходить раз в месяц, чтобы актуализировать информацию.


_Аналитик:_ Нужно ли нам поддерживать международных пользователей?<br />
_Заказчик:_ Поддержка возможна, т.к. резюме нужно составлять по всему миру, но на текущий момент в качестве MVP достаточно поддержки только для российских пользователей.


_Аналитик:_ Какие форматы резюме поддерживаются?<br />
_Заказчик:_ Возможность создать индивидуальное резюме, а также оптимизировать их с сайтов-агрегаторов.


_Аналитик:_ Требуется ли авторизация через различные сервисы?<br />
_Заказчик:_ Да, для пользователя это было бы удобно


_Аналитик:_ Какие-либо требования к формату резюме?<br />
_Заказчик:_ Я считаю, что должны быть следующие разделы в обязательном порядке: образование, карьера, навыки, достижения, общая информация.

## BPMN-диаграмма:

![](diagrams_preview/BPMN.drawio.png)

## Customer Journey Map:

![](diagrams_preview/CustomerJourneyMap.png)

## Функциональные требования:

### User Story:

__Вопросы:__

* Что это за пользователь?
*	Какое действие он хочет выполнить в продукте или какой результат от продукта хочет получить?
*	Зачем это ему?

__Ответы:__

* Как соискатель сайта по созданию резюме, я хочу формировать релевантное резюме, которое будет визуально привлекательным, содержательным и информативным, а также поможет пройти собеседование и получить приглашение на работу.

* Как администратор сайта, я могу редактировать оформление сайта, создавать шаблоны для резюме, реализовать новые способы регистрации пользователя и экспорта файлов, что поможет повысить рейтинг сайта и исполнителя, которым является администратор, а также при платной версии поможет заработать деньги.

__Функционал:__
*	Получить данные о клиенте из профиля
*	Сформировать и отправить клиенту резюме
*	Регистрация и авторизация пользователей
*	Дополнение профиля данными
*	Экспорт в различные форматы (PDF, PNG)
*	Экспорт в сайты агрегаторы

## Прототипы интерфейсов в Figma:

#### Main page
<img width="885" alt="Снимок экрана 2023-03-25 в 12 35 01" src="https://user-images.githubusercontent.com/100151145/227709244-aa22ec4d-79a7-4d97-bf27-aa2448f34862.png">

#### My summaries
<img width="897" alt="Снимок экрана 2023-03-25 в 12 35 36" src="https://user-images.githubusercontent.com/100151145/227709267-8135440a-aeac-4037-87f6-5336d96db4bc.png">

#### New summary
<img width="900" alt="Снимок экрана 2023-03-25 в 12 37 49" src="https://user-images.githubusercontent.com/100151145/227709398-bff99815-12ed-4c82-8b68-ea57d89d8700.png">

#### Responses
<img width="899" alt="Снимок экрана 2023-03-25 в 12 37 11" src="https://user-images.githubusercontent.com/100151145/227709359-ee186f35-3ce9-4a67-bec9-d07bd74ce727.png">

#### Example of mobile view
<img width="275" alt="Снимок экрана 2023-03-25 в 12 41 38" src="https://user-images.githubusercontent.com/100151145/227709593-c9e1e49f-2d24-433b-b536-adf97a7ee5b2.png">

Link: https://www.figma.com/file/aGQKJmmzmkGQSUk4OiAXet/ConceptScheme?node-id=0%3A1&t=3Qz1lKbF4chJkv3Z-1

## Концептуальная диаграмма данных:

![](diagrams_preview/concept.drawio.png)

## Физическая диаграмма данных:

![](diagrams_preview/phys.png)
