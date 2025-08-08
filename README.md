# Kotlin Core Senior Book

Полный учебник по Kotlin для senior разработчиков

## О курсе

Этот курс предназначен для опытных Java разработчиков, которые хотят освоить Kotlin на профессиональном уровне. Курс построен на принципе сравнения с Java, что позволяет быстро понять преимущества и особенности Kotlin.

## Структура курса

- **Основы Kotlin** - синтаксис, null safety, функции, data classes, sealed classes, smart casts
- **Коллекции** - Kotlin collections, sequences, custom collections, operations
- **Coroutines** - асинхронное программирование с structured concurrency
- **Продвинутые возможности** - extensions, DSL, delegation, inline functions
- **Spring Boot с Kotlin** - интеграция с Spring экосистемой
- **Ktor** - Kotlin-native веб-фреймворк
- **Базы данных** - Exposed ORM, JPA с Kotlin
- **Kotlin Multiplatform** - кроссплатформенная разработка
- **Performance** - оптимизация и профилирование
- **Testing** - тестирование Kotlin кода

## Требования

- Java 17+
- IntelliJ IDEA
- Kotlin 1.9+
- Spring Boot 3.x
- Базовые знания Java

## Как использовать этот курс

### 1. Структура файлов

```
kotlin-core-senior-book/
├── README.md          # Этот файл с инструкциями
├── SUMMARY.md         # Содержание курса
├── PROMPTS.md         # Готовые промпты для создания глав
├── RULES.md           # Правила и структура для глав
└── [разделы курса]/   # Директории с главами
```

### 2. Создание новой главы

Для создания новой главы используйте промпты из `PROMPTS.md`:

1. **Выберите подходящий промпт** из `PROMPTS.md`
2. **Следуйте структуре** из `RULES.md`
3. **Создайте директорию** для главы
4. **Создайте README.md** с содержанием главы
5. **Закоммитьте изменения**

Пример:
```bash
# Создать директорию
mkdir -p 01-kotlin-basics/kotlin-syntax

# Создать файл главы
touch 01-kotlin-basics/kotlin-syntax/README.md

# Добавить в git
git add 01-kotlin-basics/kotlin-syntax/README.md
git commit -m "Add Kotlin Syntax chapter"
```

### 3. Структура главы

Каждая глава должна содержать:

1. **Обзор темы** - что это и зачем нужно
2. **Сравнение с Java** - как это реализовано в Java vs Kotlin
3. **Детальный анализ проблем** - что может пойти не так
4. **Принцип работы** - как это работает
5. **Практические примеры** - реальные примеры кода
6. **Performance анализ** - бенчмарки и оптимизация
7. **Troubleshooting** - решение проблем
8. **Best Practices** - что делать и чего не делать
9. **Инструменты** - утилиты для работы
10. **Дополнительные ресурсы** - документация и книги

### 4. Обязательные требования

#### Сравнение с Java
- **ВСЕГДА** включайте сравнение с Java
- Показывайте Java эквивалент для каждого примера
- Объясняйте преимущества и недостатки Kotlin подхода
- Приводите performance сравнения

#### Код
- Используйте Kotlin 1.9+ синтаксис
- Показывайте полные, работающие примеры
- Включайте error handling
- Добавляйте комментарии к сложным участкам
- Всегда показывайте Java эквивалент

#### Структура
- Каждый раздел должен быть самодостаточным
- Используйте заголовки для навигации
- Добавляйте ссылки между разделами
- Включайте summary в конце

### 5. Промпты для создания контента

Используйте готовые промпты из `PROMPTS.md`:

- **Промпт 1**: Обзор темы
- **Промпт 2**: Анализ проблем
- **Промпт 3**: Принцип работы
- **Промпт 4**: Практические примеры
- **Промпт 5**: Performance анализ
- **Промпт 6**: Troubleshooting
- **Промпт 7**: Best Practices
- **Промпт 8**: Инструменты
- **Промпт 9**: Дополнительные ресурсы
- **Промпт 10**: Coroutines специфичные
- **Промпт 11**: Database специфичные
- **Промпт 12**: Ktor специфичные
- **Промпт 13**: Git Workflow

### 6. Специфичные требования

#### Для Kotlin Basics:
- Сравнение с Java синтаксисом
- Null safety и его преимущества
- Data classes vs Java POJO
- Smart casts и type inference
- Sealed classes применение

#### Для Collections:
- Отличие от Java collections
- Sequences и lazy evaluation
- Functional operations
- Performance характеристики
- Thread safety особенности

#### Для Coroutines:
- Отличие от Java threads
- Structured concurrency
- Coroutine contexts и dispatchers
- Testing strategies
- Debugging techniques

#### Для Advanced Features:
- Extension functions
- Operator overloading
- Delegation patterns
- Inline functions и reified generics
- DSL creation

#### Для Spring Boot:
- Kotlin-specific конфигурация
- Null safety в Spring контексте
- Coroutines в Spring
- Kotlin DSL для конфигурации
- Testing approaches

#### Для Ktor:
- Routing DSL
- Plugin system
- Serialization
- Authentication
- Deployment strategies

#### Для Database:
- Exposed ORM
- Kotlin JPA особенности
- Coroutines в database operations
- Kotlin-specific patterns
- Transaction management

#### Для Multiplatform:
- Shared code концепция
- Platform-specific код
- Testing strategies
- Deployment approaches
- Code sharing patterns

#### Для Performance:
- Kotlin-specific benchmarks
- Compiler optimizations
- Memory usage patterns
- Profiling tools
- Optimization techniques

#### Для Testing:
- Kotlin-specific testing
- Coroutine testing
- Integration testing
- Testing tools
- Mocking strategies

### 7. Git Workflow

#### Создание новой главы:
```bash
# 1. Создать директорию
mkdir -p [путь-к-директории]/[название-главы]

# 2. Создать README.md с содержанием

# 3. Добавить в git
git add [путь-к-файлу]/README.md

# 4. Создать коммит
git commit -m "Add [Название главы] chapter"

# 5. Запушить
git push
```

#### Обновление главы:
```bash
# 1. Внести изменения

# 2. Добавить изменения
git add [путь-к-файлу]/README.md

# 3. Создать коммит
git commit -m "Update [Название главы] chapter"

# 4. Запушить
git push
```

### 8. Правила именования

- **Директории**: kebab-case с нумерацией (`01-kotlin-basics`)
- **Файлы**: kebab-case (`kotlin-syntax`)
- **Коммиты**: краткие, информативные сообщения
- **Структура**: всегда README.md в директории главы

### 9. Качество контента

#### Обязательные элементы:
- ✅ Сравнение с Java во всех разделах
- ✅ Полные, работающие примеры кода
- ✅ Performance анализ и бенчмарки
- ✅ Troubleshooting и решения проблем
- ✅ Best practices и антипаттерны
- ✅ Инструменты и утилиты
- ✅ Дополнительные ресурсы

#### Запрещенные элементы:
- ❌ Ссылки на статьи и блоги (только документация и книги)
- ❌ Ссылки на видео
- ❌ Неполные примеры кода
- ❌ Отсутствие сравнения с Java
- ❌ Устаревший синтаксис

### 10. Проверка качества

Перед коммитом проверьте:

1. **Структура** - все 9 разделов присутствуют
2. **Сравнение с Java** - есть во всех разделах
3. **Код** - полные, работающие примеры
4. **Performance** - бенчмарки и анализ
5. **Troubleshooting** - решения проблем
6. **Best Practices** - что делать и чего не делать
7. **Инструменты** - утилиты для работы
8. **Ресурсы** - только документация и книги

## Начало работы

1. **Изучите структуру** курса в `SUMMARY.md`
2. **Ознакомьтесь с промптами** в `PROMPTS.md`
3. **Изучите правила** в `RULES.md`
4. **Выберите главу** для создания
5. **Используйте промпты** для создания контента
6. **Следуйте структуре** из правил
7. **Закоммитьте изменения**

## Вклад в проект

Для добавления новой главы:

1. Создайте issue с описанием главы
2. Создайте feature branch
3. Создайте главу, следуя структуре
4. Создайте Pull Request
5. Пройдите code review
6. Merge в main

## Лицензия

Этот курс создан для образовательных целей. Используйте свободно для изучения Kotlin.
