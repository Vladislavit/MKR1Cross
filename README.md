# Модульний контроль: Варіант 27
### Опис
Для заданих натуральних чисел $N$ і $K$ потрібно обчислити кількість чисел від 1 до $N$, що мають у двійковому записі рівно $K$ нулів.

#### Приклад:
Якщо $N = 8$ і $K = 1$, можна записати всі числа від 1 до 8 в двійковій системі числення:

1, 10, 11, 100, 101, 110, 111 та 1000.

Числа 10, 101 і 110 мають рівно один нуль у записі, тому правильна відповідь — 3.

### Вхідні дані
У єдиному рядку вхідного файлу `INPUT.TXT` записано два натуральні числа через пропуск $N$ і $K$, що не перевищують $10^9$.

### Вихідні дані
У єдиний рядок вихідного файлу `OUTPUT.TXT` потрібно вивести одне ціле число — кількість чисел від 1 до $N$ з $K$ нулями в двійковому поданні.

### Обмеження
- $0 < N \leq 10^9$
- $0 \leq K \leq 10^9$

### Приклади
| №   | INPUT.TXT | OUTPUT.TXT |
|-----|-----------|------------|
| 1   | 8 1       | 3          |
| 2   | 1000 5    | 210        | 
