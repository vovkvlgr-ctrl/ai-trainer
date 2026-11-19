# ШІ-тренажер Академії Viatec

Безкоштовний практичний тренажер до курсів «ШІ-старт» (курс 0) і «ШІ-грамотність» (курс 1).

Слухач пише запит до робочої задачі, тренажер одразу перевіряє його за формулою «роль — ситуація — завдання — вигляд» і шукає персональні дані. Потім слухач запускає запит у своєму ШІ-помічнику (ChatGPT, Claude, Gemini) і отримує оцінку від «ШІ-тренера».

Сторінка нічого нікуди не надсилає і не потребує ключів чи сервера. Прогрес зберігається в браузері слухача.

## Адреси

Після увімкнення GitHub Pages (Settings → Pages → Deploy from a branch → `main` / `root`):

| Що | Посилання |
|---|---|
| Головна | https://vovkvlgr-ctrl.github.io/ai-trainer/ |
| Лист клієнту про затримку поставки (0.3 · 1.4) | https://vovkvlgr-ctrl.github.io/ai-trainer/#lyst |
| Підсумок регламенту для новачка (1.2) | https://vovkvlgr-ctrl.github.io/ai-trainer/#dokument |
| Тренди ринку з перевіреними джерелами (1.3) | https://vovkvlgr-ctrl.github.io/ai-trainer/#poshuk |
| Зведення продажів по менеджерах (1.5) | https://vovkvlgr-ctrl.github.io/ai-trainer/#tablytsia |
| Відповідь клієнту без персональних даних (0.4 · 1.6) | https://vovkvlgr-ctrl.github.io/ai-trainer/#znesob |
| Спокійна відповідь на різкий лист (1.4) | https://vovkvlgr-ctrl.github.io/ai-trainer/#ton |

## Вбудувати в Kwiga

У редакторі уроку → блок HTML/код:

```html
<iframe src="https://vovkvlgr-ctrl.github.io/ai-trainer/#lyst" width="100%" height="1400" style="border:0;border-radius:16px" loading="lazy"></iframe>
```

Замініть `#lyst` на потрібну задачу.

## Як змінити задачі

Усі задачі — в `index.html`, у масиві `TASKS`: сценарій, факти, матеріал, поради, чек-лист результату і приклад сильного запиту.
