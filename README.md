# Атлас веб-стилей

Справочник визуальных стилей веб-дизайна для более точной генерации сайтов. 44 направления, у каждого живое превью мини-сайта и готовый промпт-фрагмент: палитра, шрифты, формы, тени, фактура и движение.

**Открыть:** https://oz-the-magician.github.io/web-style-atlas/

## Что внутри

| Семейство | Стили |
| --- | --- |
| UI-парадигмы | Skeuomorphism, Flat, Material, Neumorphism, Glassmorphism, Liquid Glass, Claymorphism, Aurora |
| Минимализм и типографика | Minimalism, Swiss Style, Editorial, Big Type, Bento Grid, Dark SaaS, Japandi |
| Экспериментальные | Web Brutalism, Neo-Brutalism, Anti-design, Y2K, Vaporwave, Acid Graphics, Cyberpunk, Memphis, Retro 90s Web, Retro OS, Terminal, Pixel Art |
| Арт-движения | Bauhaus, Art Deco, Art Nouveau, Constructivism, Mid-century Modern, Psychedelic, Collage / Zine, Hand-drawn, Risograph |
| 3D и движение | Immersive 3D, Isometric, Scrollytelling / Parallax, Kinetic Typography, Spatial UI |
| Органика и цвет | Organic / Blob, Duotone, Grainy Gradients |
| Гибриды | Swiss Punk, Bento Glass, Neo-Brutal Y2K, Editorial Grain, Terminal SaaS, Riso Collage, Aurora Glass, Isometric Clay |

## Как пользоваться

1. Найдите стиль поиском или фильтром по семейству.
2. Нажмите «Промпт», чтобы скопировать описание стиля, или «Подробнее», чтобы увидеть большое превью.
3. Вставьте фрагмент в запрос к генератору сайтов. Стили можно смешивать, например Swiss + Dark SaaS.

## Устройство

Один файл `index.html` без сборки и зависимостей. Интерфейс атласа оформлен в классическом Material Design: app bar с поиском и вкладками, карточки на 1dp с подъёмом до 8dp, ripple, FAB «Случайный», диалог и снекбар. Превью нарисованы на CSS и масштабируются через container query units, поэтому одна разметка работает и в карточке, и в большом окне. Фоновые анимации идут только у видимых превью и отключаются при системной настройке «уменьшить движение». Поддерживаются светлая и тёмная темы.

Liquid Glass и Spatial UI здесь веб-аппроксимации, а не официальные материалы Apple.

## Авторство

Фотографии: Emil Persson (Humus), [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Шрифты: Google Fonts (SIL Open Font License).
