# Lab 4 — CI/CD Pipeline

Лабораторная работа №4 по дисциплине «Промышленное программирование».

## Выполнил
Цыкало Сергей Евгеньевич
Группа ИДБ-25-06

## Тема работы
Настройка промышленного CI/CD пайплайна с использованием GitHub Actions.

## Реализовано
- Автоматическая сборка C++ приложения
- Unit и integration тестирование
- Нагрузочное тестирование (wrk)
- Статический анализ clang-tidy
- Docker build + push в GHCR
- Deploy в staging
- Production deploy (blue-green)
- Rollback workflow
- Сохранение логов и метрик как artifacts

## Используемые технологии
- GitHub Actions
- Docker
- CMake
- clang-tidy
- ccache
- wrk
- Ubuntu runners

## Репозиторий
Лабораторная работа выполнена в рамках курса МГТУ «СТАНКИН».