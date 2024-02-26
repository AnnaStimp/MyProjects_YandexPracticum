# Анализ поведения пользователей мобильного приложения


## Данные

- ``EventName`` — название события;
- ``DeviceIDHash`` — уникальный идентификатор пользователя;
- ``EventTimestamp`` — время события;
- ``ExpId`` — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

## Задача

Есть стартап, который продает продукты питания. В распоряжении имеются логи пользователей. Так же был проведен A/A/B-эксперимент, целью которого является выяснение, какой шрифт лучше. Нужно разобраться, как ведут себя пользователи риложения, изучить воронку продаж, исследовать результаты A/A/B-эксперимента.

## Использующиеся бибилотеки
*pandas*, *matplotlib*, *numpy*, *scipy*, *math*, *datetime*, *plotly.express*