# Выявление элементов культурного кода россиян в отзывах о произведениях художественной литературы

Цель — разработать модель, выявляющую отзывы, в которых содержатся элементы культурного кода. Отзыв считается релевантным, если он обладает ценностно-смысловым содержанием, и его автор вписывает эти смыслы и ценности в свой жизненный и культурный контекст, идентифицирует себя с героями, содержанием, исторической судьбой народа.

### Столбцы:
● RecordNo — уникальный идентификатор отзыва  
● Название книги — название книги, на которую оставлен отзыв  
● Автор — автор книги  
● Ссылка на литрес — ссылка на книгу  
● Рейтинг — общий рейтинг книги, рассчитанный на основе всех отзывов  
● Количество оценок — суммарное число оценок книги в обзоре 
● Количество отзывов — суммарное число письменных обзоров книги  
● Имя читателя — имя пользователя, оставившего отзыв  
● Оценка книги читателем (из 5 баллов) — оценка книги конкретным
пользователем
● Отзыв — текст отзыва
● Лайки на отзыв — количество положительных оценок отзыва,
оставленных другими пользователями
● Дислайки на отзыв — количество отрицательных оценок отзыва,
оставленных другими пользователями

### Предсказываемые значения:
● Релевантность — характеристика, отражающая степень соответствия
контента теме исследования (Нерелевантно - 0, Релевантно - 1)
● Ценности — наличие необходимых ценностей в тексте (Нерелевантно
- 0, Релевантно - 1)
● Таксономия релевантные — наличие в тексте отзыва слов,
словосочетаний, связей между словами из словаря синонимических
рядов каждой категории, обозначающих духовно-нравственную
ценность. (не определено - 0, определено - 1)
● Таксономия нерелевантные — наличие в тексте отзыва слов,
словосочетаний, связей между словами из словаря синонимических
рядов каждой категории, обозначающих духовно-нравственную
ценность, не подходящую к теме исследования. (не определено - 0,
определено - 1)
● Длина отзыва — наличие у отзыва оптимального числа слов (не
определено - 0, определено - 1)
