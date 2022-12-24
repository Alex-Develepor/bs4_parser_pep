# Парсер документации python
Парсер документации python c https://docs.python.org/3/ и https://peps.python.org/

## Технологии
- [Python](https://www.python.org/)
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)

## Использование
Склонируйте репозиторий  
Создайте виртуальное окружение 
```
python -m venv venv
```
Активируйте виртуальное окружение  
Установить зависимости 
```
pip install -r requirements.txt
```
Обновите зависимости 
```
pip install --upgrade pip
```

### Режимы работы:
#### whats-new:
Парсит список изменений python
#### latest_versions:
Парсит список версий python и ссылки на документацию
#### download:
Cкачивает архив с документацией в папку ./downloads
#### pep:
Парсит список статусов документов pep и подсчитывает количество документов для каждого статуса

## Проект выполнил
- Александр Дворецкий