# interpreting_a_b_test_results_variant2

Interpreting A/B test results using diffrenet methods.

### RU Description

Пришло время проанализировать результаты эксперимента, который  провели вместе с командой дата сайентистов. Эксперимент проходил с 2022-12-02 по 2022-12-08 включительно. Для эксперимента были задействованы 2 и 1 группы. 

В группе 2 был использован один из новых алгоритмов рекомендации постов, группа 1 использовалась в качестве контроля. 

Основная гипотеза заключается в том, что новый алгоритм во 2-й группе приведет к увеличению CTR. 

Задача — проанализировать данные АB-теста. 

 - Выбрать метод анализа и сравнить CTR в двух группах (t-тест, Пуассоновский бутстреп, тест Манна-Уитни, t-тест на сглаженном ctr (α=5) а также t-тест и тест Манна-Уитни поверх бакетного преобразования).
 - Сравнить данные этими тестами.
 - Описать потенциальную ситуацию, когда такое изменение могло произойти.
 - Написать рекомендацию, будем ли  раскатывать новый алгоритм на всех новых пользователей или все-таки не стоит.
