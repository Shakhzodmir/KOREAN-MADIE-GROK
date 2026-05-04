# Как загрузить на GitHub Pages

## Шаг 1: Создай репозиторий
1. Перейди на https://github.com/new
2. Назови репозиторий: `korean-with-madie`
3. Сделай его **Public**
4. **НЕ** инициализируй с README (мы загрузим свои файлы)

## Шаг 2: Загрузи файлы
Самый простой способ:

```bash
# 1. Скачай эту папку на компьютер

# 2. В терминале перейди в папку
cd korean-with-madie-webapp

# 3. Инициализируй git
git init
git add .
git commit -m "🌸 Korean with Madie - first release"

# 4. Добавь свой репозиторий (замени USERNAME на свой)
git remote add origin https://github.com/USERNAME/korean-with-madie.git

# 5. Загрузи
git push -u origin main
```

## Шаг 3: Включи GitHub Pages
1. Перейди в настройки репозитория → **Pages**
2. В разделе "Source" выбери **Deploy from a branch**
3. Выбери ветку `main` и папку `/ (root)`
4. Нажми **Save**

Готово! Через 1-2 минуты приложение будет доступно по адресу:
`https://USERNAME.github.io/korean-with-madie/`

## Альтернатива (через GitHub Desktop)
1. Скачай GitHub Desktop
2. Создай новый репозиторий
3. Перетащи все файлы из этой папки
4. Commit → Push
5. Включи GitHub Pages в настройках

---

**Нужна помощь?** Напиши Мади — она поможет! 🌸