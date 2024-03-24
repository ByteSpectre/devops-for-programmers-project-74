### Hexlet tests and linter status:
[![Actions Status](https://github.com/ByteSpectre/devops-for-programmers-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/ByteSpectre/devops-for-programmers-project-74/actions)
<br>
[![CI/CD](https://github.com/ByteSpectre/devops-for-programmers-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/ByteSpectre/devops-for-programmers-project-74/actions/workflows/push.yml)

# Упаковка в Docker Compose

Учебный проект для Hexlet

## Требования к системе

- Node.js (версия 14.x)
- npm (версия 6.x)
- Система управления контейнерами (Docker)
- База данных (PostgreSQL, версия 16.х)

## Инструкции по настройке и запуску

1. Установите требуемые системные компоненты (Node.js, npm, Docker)

2. Клонируйте проект с репозитория:

```bash
git clone https://github.com/ByteSpectre/devops-for-programmers-project-74.git
cd devops-for-programmers-project-74
```
## Run Development

1. `make compose-setup`
2. `make compose-dev`

## Run Tests

1. `make compose-ci`
