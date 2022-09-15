# Automation_Docker_PostgreSql_Configure

# PostgreSQL

# Обучение в Нетологии.

## Курс Автоматизированное тестирование

## Тема: Docker и Docker Compose
- Настройка Docker
- Подготовка приложения(```db-api.jar```) к тестированию на СУБД PostgreSQL

**Для запуска проекта:**
1. Склонировать проект из репозитория командой 

```
git clone https://github.com/holyblaz/Automation_Docker_PostgreSql_Configure.git
```
2. Открыть склонированный проект в Intellij IDEA
3. Запустить команду ```docker-compose up```
4. Для запуска приложения ввести команду ```java -jar ./atrifacts/db-api.jar```
5. Открыть в браузере ссылку [](http://localhost:9999/api/cards)
6. По ссылке должен быть JSON с информацией о картах.
