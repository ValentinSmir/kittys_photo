##  Описание проекта Kittygram:
Kittygram — это социальная сеть для любителей котиков, где вы можете публиковать фотографии своих питомцев, рассказывать об их достижениях и следить за другими котиками.

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

`git clone git@github.com:ValentinSmir/api_final_yatube.git`

Запустите проект с помощью Docker Compose:

'docker compose -f docker-compose.production.yml up'

## Примеры запросов:

Получить список всех котиков:

'GET /api/cats/'

Добавить нового котика:

'POST /api/cats/'

'{'
  '"name": "Барсик",'
  '"birth_year": 2020,'
  '"achievements": [1],'
  '"image": "string"'
'}'

## Использованные технологии:

'Docker'
'Docker Compose'
'GitHub Actions (CI/CD)'

## Информация об авторе:
Валентин Смирнов. Студент Яндекс Практикума.