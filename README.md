# Siteix UI

Минимальный CSS UI-кит для лендингов и небольших сайтов. Один файл, без сборщика и зависимостей.

[Демо](https://siteix-ru.github.io/siteix-ui/) · [Исходники](https://github.com/siteix-ru/siteix-ui)

## Что внутри

- CSS-токены: цвета, радиусы, тень, шрифт;
- контейнер и адаптивная сетка;
- кнопки: primary, copper, ghost, block;
- поля ввода, textarea, чекбокс, состояния focus;
- карточки, бейджи, алерты;
- базовый reset и системный шрифт.

## Подключение

```html
<link rel="stylesheet" href="siteix-ui.css" />
```

Используйте классы `sx-btn sx-btn--primary`, `sx-card`, `sx-field`, `sx-input`, `sx-grid`.

## Пример

```html
<div class="sx-container sx-section">
  <p class="sx-kicker">Услуга</p>
  <h1 class="sx-title">Заголовок страницы</h1>
  <p class="sx-lead">Короткое описание предложения.</p>
  <a class="sx-btn sx-btn--copper" href="#lead">Обсудить задачу</a>
</div>
```

## Токены

```css
--sx-ink: #17251f;
--sx-muted: #56635b;
--sx-paper: #f7f2e8;
--sx-green: #173e30;
--sx-copper: #c4673f;
--sx-line: #dfe4dc;
--sx-radius: 14px;
```

## Лицензия

MIT. См. [LICENSE](LICENSE).
