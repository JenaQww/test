# main.py

def greet(name: str) -> str:
    """Возвращает приветствие для пользователя."""
    return f"Привет, {name}! Добро пожаловать в проект."

def calculate_sum(a: int, b: int) -> int:
    """Возвращает сумму двух чисел."""
    return a + b

if __name__ == "__main__":
    user_name = "Разработчик"
    message = greet(user_name)
    print(message)

    x, y = 3, 5
    total = calculate_sum(x, y)
    print(f"Сумма {x} и {y} равна {total}")
