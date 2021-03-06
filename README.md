# Тестовое задание для фронтенд-разработчика

Привет и спасибо, что нашли время попробовать сделать наше задание.

## Цели задания
- дать представление о работе в нашей команде
- оценить общий уровень соискателя
- понять, как соискатель принимает решения

Задание не требует знаний библиотек, всё можно написать на чистом JS. Но будет круто, если вы попробуете сделать на стеке близком к нашему: React.js, Redux, ES6+, webpack. Отдельным плюсом будет использование [БЭМ-методологии](https://ru.bem.info/methodology/quick-start/) (именование классов, подход к вёрстке).

Мы старались сделать задание, которое не займёт много времени (мы оцениваем его в ~1-2 дня), но вы можете назвать тот срок, который вам комфортен.

## Задание: список навыков

1. Нужно получить и отобразить в виде списка слева список навыков. Endpoint: http://backend.dev.education-team.ru/api/v2/skills/. Список имеет пагинацию. В next/previous пишется следующая/предыдущая страница. Например, запрос 2-й страницы: /api/v2/skills/?page=2. Сделать кнопку "ещё" под списком для догрузки следующей страницы навыков.
1. Справа — таблица навыков пользователя. Изначально пустая. Два столбца: название (строка) и значение (натуральное число). Таблица сортируется по значению (самое большое значение — сверху).
1. Между списком общих навыков и таблицей навыков пользователя есть кнопка "добавить".
1. Из списка слева можно выбрать несколько навыков. Каждый навык выбирается по клику. Снимается выбор по повторному клику. При нажатии на кнопку "добавить" выбранные навыки появляются в таблице справа со значением 1, слева они перечеркиваются и их уже нельзя выбрать.
1. В таблице справа каждый навык можно улучшить (+) или ухудшить (-), что изменяет его значение на 1. Если значение стало 0, то навык удаляется из правой таблицы и снова становится активным в списке навыков.
1. БОНУС. Чтобы навыки не пропадали при перезагрузке, нужно придумать способ хранения на клиенте.
1. БОНУС. Написать юнит-тесты. Не нужно покрывать тестами весь код, нам интересно узнать, как вы их пишете, что используете.
1. БОНУС. Адаптировать под мобильные браузеры.
1. БОНУС. Всё что вы пожелаете!

Дизайн (фактическое расположение левых-правых частей, отображение значения навыка, вычёркивание использованных навыков) — польностью на ваше усмотрение.

## Инструкции

1. Дайте свою оценку, как много времени вам понадобится, чтобы выполнить задание.
1. Форкните этот репозиторий.
1. Напишите свой код в нескольких коммитах, чтобы мы могли видеть весь процесс разработки. Мы не будем смотреть ваш код после каждого действия, но нам очень интересно, в каком порядке вы ставите себе задачи и выполняете их.
1. После завершения сделайте пулл-реквест с необходимыми инструкциями для запуска и объяснением вашего решения.
1. Дайте нам знать, что всё готово. После этого мы проведём ревью и зададим вопросы.

Достаточно поддерживать только последние версии основных браузеров Chrome, Firefox, Edge.
Если возникли вопросы, не стесняйтесь их задавать!

## Критерии

1. Приложение должно работать! :)
2. Нам очень интересно, как вы пишете код, какие используете библиотеки и инструменты, какие средства языка
3. Ответы на вопросы в процессе code review
