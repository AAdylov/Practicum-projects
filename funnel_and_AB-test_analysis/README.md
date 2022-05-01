### Исследование поведения пользователей мобильного приложения.
#### Описание исследования.
В данном исследовании мы поставим себя на место аналитика стартапа, который продаёт продукты питания. Нужно разобраться, как ведут себя пользователи нашего мобильного приложения. Дизайнеры захотели поменять шрифты во всём приложении, а менеджеры испугались, что пользователям будет непривычно. Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. Выясним, какой шрифт лучше.

#### Цель исследования.
Определить по результатам исследования поведения пользователей:

- на каких этапах воронки продаж могут быть проблемы,
- по результатам А/А/В теста определить перспективность гипотезы смены шрифта в приложении.

#### Суть исследования: 
Изучить воронку продаж и проанализировать результаты А/А/В-теста.

#### Задачи исследования.
В нашем исследовании мы ознакомимся с входными данными, подготовим их для исследования, изучим и проверим данные, проанализируем воронку событий, постараемся найти слабые места, проанализируем результаты А/А/В-теста, сделаем вывод о результатах эксперимента.

#### Исходные данные.
У нас в распоряжении лог с действиями пользователей мобильного приложения. В нём хранится информация о: названии события, id пользователя, времени события, номере группы эксперимента.

#### Используемые библиотеки:
*pandas, matplotlib, scipy, plotly*