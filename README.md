# Шпаргалка по Git

## Основные команды Git

### 1. Настройка Git
- **Установить Git** 
- **Настроить имя и email:**
  
```bash
  git config --global user.name "Ваше Имя"
  git config --global user.email "ваш.имейл@example.com"
```
  

### 2. Основные команды работы с репозиторием
- **Клонирование репозитория:**
  
```bash
  git clone ссылка_на_репозиторий
  ```

- **Создание нового репозитория:**
  ```bash
  git init
  ```

### 3. Работа с файлами
- **Добавить файл для подготовки к коммиту:**
  ```bash
  git add имяфайла
  ```
  или для всех файлов:
  
```bash
  git add .
```
или:
```bash
git add --all
```
  

- **Коммит :**
  
```bash
  git commit -m "Коммит"
```
  

### 4. Проверка статуса и истории
- **Проверить статус репозитория:**
  
```bash
  git status
```
  

- **Посмотреть историю коммитов:**
  
```bash
  git log
```
  

### 6. Работа с удалёнными репозиториями
- **Доступ к удалённому репозиторию:**
  ```bash
  git remote add origin ссылка_на_репозиторий
```
  

- **Отправка изменений на удалённый репозиторий:**
  
```bash
  git push origin имяветки
  ```
  

## Полезные ссылки
- [Официальная документация Git](https://git-scm.com/doc)
