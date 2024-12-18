**Контекст:**

При разработке серверной части ЛМС нам надо: 
* Производительность 
* Надежность + отказоустойчивость
* Гибкость масштабирования 
* Работать с большими объемами данных

**Рассмотренные варианты:**

1. **Go:** Простой и быстрый язык с отличной поддержкой многозадачности.
2. **Python:** Популярный язык с широкой библиотекой и быстрой разработкой, но может иметь проблемы с производительностью на серверной стороне +качество кода.
3. **PHP:** Этот язык прост в использовании (простое взаимодействие с базами данных).

**Решение:**

Выбраны Go.

**Обоснование:**

- **Высокая производительность**:
- **Масштабируемость и надежность:**  Go хорошо подходит для микросервисной архитектуры. PHP станет основой для сложных модулей, тогда как Go идеально подходит для высоконагруженных и легковесных сервисов.

**Последствия:**

- Все серверные компоненты будут разработаны на Go.
- Потребуется время на создание и внедрение оптимальных практик для работы с "новой" технологией в рамках проекта.