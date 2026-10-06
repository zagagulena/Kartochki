# Norsk kort

Карточки для изучения норвежского (Liquid Glass, озвучка через Web Speech API).

- Базовые слова — в `index.html`, в константе `RAW` (формат `норвежский|перевод|тема|пример`). Новые слова дописывайте в конец.
- Добавленные пользователем карточки и прогресс хранятся только в `localStorage` его браузера.

## Публикация на GitHub Pages

```bash
git init
git add .
git commit -m "Norsk kort"
git branch -M main
git remote add origin https://github.com/<ваш-логин>/norsk-kort.git
git push -u origin main
```

Затем на GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**.
Через минуту-две сайт будет доступен по адресу `https://<ваш-логин>.github.io/norsk-kort/`.
