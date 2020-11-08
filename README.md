# Postfix-calculator
## Обрабатывает такие операции как:
- Сложение `+`
- Вычитание `-`
- Умножение `*`
- Деление `/`
- Остаток от деления `%`
- Возведение в степень `^`
- Вызов функции `()`

## Поддерживает такие математические функции как:
| Название                   | Назначение                      |
| -------------------------- | ------------------------------- |
| <b>Корни</b>               |                                 |
| `sqrt`                     | Квадратный корень               |
| `cbrt`                     | Кубический корень               |
| <b>Тригонометрические функции</b> |                          |
| `cos`                      | Косинус                         |
| `sin`                      | Синус                           |
| `tg/tan`                   | Тангенс                         |
| `arccos/acos`              | Арккосинус                      |
| `arcsin/asin`              | Арксинус                        |
| `arctg/atan`               | Арктангенс                      |
| <b>Логарифмы</b>           |                                 |
| `ln`                       | Натуральный логарифм            |
| `log2`                     | Логарифм по основанию 2         |
| `log10`                    | Логарифм по основанию 10        |
| <b>Разное</b>              |                                 |
| `abs`                      | Модуль числа                    |
| `ceil`                     | Округление вверх                |
| `floor`                    | Округление вниз                 |
| `round`                    | Округление до ближайщего целого |

## Правила оформления:
- Унарный минус отсутствует, вместо него использовать вычитание из нуля
- Не целые числа могут записываться как через точку, так и через запятую
- Символ новой строки считает за конец выражения
- Между числами и операторами может быть разное количество пробельных символов (пробел или табуляция)
- Разрешается вводить переменные, но при использовании в операциях выдаст ошибку

Может работать в связке с [infix2postfix](https://github.com/evgenyPro/Infix2postfix), например, `echo "2 * (3 + 2)^2 | ./infix2postfix | ./postfixCalc`.
