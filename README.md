# Персональное руководство: Лари (LariKing77)

> Собрано скиллом `/personal-guide-render` 2026-05-10 (first-run).
> Ступень: **Практикующий (2)** по PD.FORM.003. Домен: **Knowledge Worker**.
> Bottleneck: **M1** (методы работы / устойчивый ритм).

## Структура

- `profile.md` — RCS-профиль и ритм
- `worldview.md` — мировоззренческая фаза и мемы
- `methods.md` — методы под bottleneck M1
- `weekly/2026-W19.md` — гипотеза текущей недели (10 мая = воскресенье W19)
- `daily/2026-05-10.md` — тактика дня
- `history/` — архив прошлых weekly/daily (создаётся при пересборке)

## Как обновлять

Это живой репо. Чтобы пересобрать — вызови `/personal-guide-render` снова (после изменений в Память.Derived) или попроси в чате:
- «Собери план на завтра» → новый `daily/<дата>.md`
- «Переделай methods.md под проект Planora» → пересборка методов
- «Итоги недели» → архив `weekly/<неделя>.md` в `history/` + новая гипотеза

Автоматизация по расписанию — Портной (WP-222), лето 2026.

## Локальный клон

```
git clone https://github.com/LariKing77/personal-guide.git ~/IWE/personal-guide
```

После этого правки локально → `git push` → Aisystant MCP подхватит через reindex.

## Источники

- Заготовка ступени: `PACK-personal/.../personal-guide-seeds/stage-2-practicing.md`
- Доменная вставка: `PACK-personal/.../personal-guide-seeds/domain-knowledge-worker.md`
- RCS-модель: `PACK-personal/.../formalizations/PD.FORM.089-learner-rcs.md`
- Дуга мировоззрения: `PD.FORM.087`
- Каталог методов: `PD.CAT.003`
