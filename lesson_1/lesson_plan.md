# План 1 занятия по верификации

- Введение
    - Вступительная теория
        - Маршрут проектирования СБИС и место верификации в нем
            - Схема маршрута
            - Время на верификацию в общем маршруте
        - Определение верификации
        - Возврат к схеме маршрута и определение типов верификации
            - Рассказ про типы
            - Оговорка о том, что мы касаемся только функциональной верификации
        - Что такое SystemVerilog
            - Потомок Verilog
            - Почему появилась необходимость в нем (как раз упрощение верификации)
    - Что будем делать и зачем
        - Разбирать простые примеры и простейшие подходы к верификации
- Теория, необходимая для выполнения заданий
    - Введение в новые типы данных
        - `bit`
        - ...
        - `queue`
    - Введение в новые конструкции
        - `always_ff`
        - `always_comb`
    - Время моделирования
    - Параллельное исполнение
        - процессы
        - события
    - Последовательность выполнения событий
        - Схема event regions
        - Active
        - NBA
        - Итог
    - Контроль времени
        - \``timescale`
        - `timeunit`, `timeprecision`
        - Процедуры контроля
            - `#`
            - `@`
            - `wait`
- Задания
    - 16_ff_fifo_wrapped_in_valid_ready
    - 18_a_plus_b_using_fifos
