# Калькулятор

Простой калькулятор на Python. Текущая версия: 1.0.0.

## Возможности

- Сложение — `add(a, b)`
- Вычитание — `subtract(a, b)`
- Умножение — `multiply(a, b)`

## Установка зависимостей

```bash
pip install -r requirements.txt
```

## Запуск тестов

```bash
pytest
```

## Пример использования

```python
from calculator import add, subtract, multiply

print(add(2, 3))       # 5
print(subtract(5, 3))  # 2
print(multiply(4, 3))  # 12
```