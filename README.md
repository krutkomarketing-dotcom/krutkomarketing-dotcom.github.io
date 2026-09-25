# krutkomarketing-dotcom.github.io

В этой репе лежат два независимых сайта, оба публикуются через GitHub Pages из ветки `main`.

## Резюме — https://krutkomarketing-dotcom.github.io/

Файлы резюме (правь только их, когда работаешь с резюме):

| Файл | Что это |
|---|---|
| `index.html` | страница резюме / портфолио кейсов |
| `ivan-krutko-cases.pdf` | PDF с кейсами |

Новые файлы резюме класть в корень или в свои папки. Папку `centr-otoplenia/` не трогать.

## Сайт «Центр отопления» — https://krutkomarketing-dotcom.github.io/centr-otoplenia/

| Файл / папка | Что это |
|---|---|
| `centr-otoplenia/` | весь сайт, **сгенерированная копия** — руками не править |
| `.nojekyll` | общий для репы: без него GitHub Pages не публикует папку `centr-otoplenia/_astro` (стили). Резюме не мешает, не удалять |
| `README.md` | этот файл |

Исходник сайта — отдельная репа
[`krutkomarketing-dotcom/centr-otoplenia.pages.dev-`](https://github.com/krutkomarketing-dotcom/centr-otoplenia.pages.dev-)
(ветка `main` = версия с прода centr-otoplenia.pages.dev). Сайт правится там, а сюда копируется заново.
Как обновить копию — в README той репы.

Если сайт переедет на свой домен или в свою репу — папку `centr-otoplenia/` можно удалить,
резюме от этого не пострадает. `.nojekyll` можно оставить.
