# project
Project (final)
Проект: вариант 1
Представьте, что вы работаете в компании, которая разрабатывает мобильные игры. К вам пришел менеджер с рядом задач по исследованию нескольких аспектов мобильного приложения:

В первую очередь, его интересует показатель retention. Напишите функцию для его подсчета.
Помимо этого, в компании провели A/B тестирование наборов акционных предложений. На основе имеющихся данных определите, какой набор можно считать лучшим и на основе каких метрик стоит принять правильное решение.
Предложите метрики для оценки результатов последнего прошедшего тематического события в игре.
 
Задание 1
Retention – один из самых важных показателей в компании. Ваша задача – написать функцию, которая будет считать retention игроков (по дням от даты регистрации игрока). Данные лежат в папке shared и имеют следующую структуру:

shared/problem1-reg_data.csv – данные о времени регистрации

shared/problem1-auth_data.csv – данные о времени захода пользователей в игру

Функция должна быть написана на python. В ходе решения можно тестировать работу функции как на полном датасете, так и на части (сэмпле) данных.

Задание 2
Имеются результаты A/B теста, в котором двум группам пользователей предлагались различные наборы акционных предложений. Известно, что ARPU в тестовой группе выше на 5%, чем в контрольной. При этом в контрольной группе 1928 игроков из 202103 оказались платящими, а в тестовой – 1805 из 202667.

Какой набор предложений можно считать лучшим? Какие метрики стоит проанализировать для принятия правильного решения и как?

Задание 3
В игре Plants & Gardens каждый месяц проводятся тематические события, ограниченные по времени. В них игроки могут получить уникальные предметы для сада и персонажей, дополнительные монеты или бонусы. Для получения награды требуется пройти ряд уровней за определенное время. С помощью каких метрик можно оценить результаты последнего прошедшего события?

Предположим, в другом событии мы усложнили механику событий так, что при каждой неудачной попытке выполнения уровня игрок будет откатываться на несколько уровней назад. Изменится ли набор метрик оценки результата? Если да, то как?
(English version)
Project: option 1
Imagine that you work for a company that develops mobile games. A manager has come to you with a number of tasks to research several aspects of a mobile application:

First of all, he is interested in the retention indicator. Write a function to count it.
In addition, the company conducted A/B testing of sets of promotional offers. Based on the available data, determine which set can be considered the best and on the basis of which metrics it is worth making the right decision.
Suggest metrics for evaluating the results of the last thematic event in the game.
 
Task 1
Retention is one of the most important indicators in the company. Your task is to write a function that will count the retention of players (by days from the date of registration of the player). The data is in the shared folder and has the following structure:

shared/problem1-reg_data.csv – registration time data

shared/problem1-auth_data.csv – data about the time when users logged into the game
The function must be written in python. During the solution, you can test the function on both the full dataset and a part (sample) of the data.

Task 2
There are results of an A/B test in which two groups of users were offered different sets of promotional offers. It is known that ARPU in the test group is 5% higher than in the control group. At the same time, in the control group, 1928 players out of 202103 turned out to be paying, and in the test group – 1805 out of 202667.

Which set of offers can be considered the best? What metrics should be analyzed to make the right decision and how?

Task 3
In the game Plants & Gardens, themed events are held every month, limited in time. In them, players can get unique items for the garden and characters, additional coins or bonuses. To get a reward, you need to complete a number of levels in a certain time. What metrics can be used to evaluate the results of the last past event?
