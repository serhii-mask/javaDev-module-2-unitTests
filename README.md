# Module 2 [Unit тести]

Створи Gradle проєкт, у якому є клас `SumCalculator`, з методом `int sum(int n)`. Цей метод має повертати суму чисел від 1 до n включно.

Наприклад, виклик `sum(3)` має повернути `6` (1 + 2 + 3).

Напиши тестовий клас для `SumCalculator`, де протестуй наступну поведінку методу `sum()` (кожний пункт списку - окремий тест):

виклик `sum(1)` повертає `1`
виклик `sum(3)` повертає `6`
виклик `sum(0)` викидає виключення `IllegalArgumentException`
Використай метод з анотацією `@BeforeEach`, щоб конструювати об'єкт класу `SumCalculator` перед кожним тестом.

Переконайся, що твій код запускається з терміналу викликом команди `gradle test`.

Результат виконання домашнього завдання - репозиторій на Github з вихідним кодом.
