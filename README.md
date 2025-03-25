# 📚 BooksCollector — Автотесты (Спринт 4)

Улугбек Шарипов  
Тестирование класса `BooksCollector` с использованием `pytest`

---

## 🧪 Реализованные тесты

1. `add_new_book_success` — добавление новой книги в коллекцию  
2. `add_multiple_books` — добавление нескольких книг  
3. `set_book_genre_success_book_is_added` — установка жанра  
4. `set_book_genre_book_not_in_genre` — проверка для несуществующей книги  
5. `get_books_for_children` — проверка детских книг  
6. `add_book_in_favorites` — добавление книги в избранное  
7. `add_book_duplicate_not_in_favorites` — дубликаты в избранное  
8. `delete_book_from_favorites` — удаление из избранного  
9. `get_books_with_specific_genre` — книги по жанру  
10. `get_books_genre` — список всех жанров  
11. `get_one_book_genre` — жанр конкретной книги  

---

## 🧪 Как запустить

### ✅ Запуск всех тестов

```bash
pytest -v tests.py

pytest --cov=main --cov-report=term tests.py
open htmlcov/index.html