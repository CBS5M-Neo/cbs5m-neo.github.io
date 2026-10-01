# Neo — neo.cbs5m.org

Лендинг **Neo** — подкомпании [CBS5M](https://github.com/CBS5M-Neo), создающей
статичные сайты с помощью ИИ (GLM-5.3-flash / Hy3 / Qwen3.8-Flash / Mimo-v2.5,
DeepSeek Harness; при исчерпанном лимите модели автоматически переключаются).

**Живой сайт:** <https://neo.cbs5m.org/>
**Каталог сайтов:** <https://neo.cbs5m.top/> (репозиторий [Sites](https://github.com/CBS5M-Neo/Sites))

## Структура

```
index.html   # одностраничник: возможности, процесс, цены, FAQ, портфолио
logo.png     # логотип (шапка, футер)
logo2.png    # логотип №2
```

Портфолио на лендинге подтягивается автоматически из
[`sites.json`](https://github.com/CBS5M-Neo/Sites) репозитория
[Sites](https://github.com/CBS5M-Neo/Sites) — конвейер Neo обновляет его
при каждом новом сайте.

## Цены

| Услуга | Цена |
|---|---|
| Обычный сайт + 8 правок | 100 ₽ |
| Доп. правка | 10 ₽ |
| Неделя без посетителей (опция) | 20 ₽ / иначе сайт отключается |

Заказ — через [шаблон issue](https://github.com/CBS5M-Neo/Sites/issues/new?template=new-site.yml).

© 2025 Neo — подкомпания CBS5M.
