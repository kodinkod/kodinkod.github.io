---
date: '2026-08-21T10:18:00+03:00'
draft: false
title: '18 · Регуляризация в DL: Dropout, BatchNorm, train/eval'
categories: ["Базовое ML"]
tags: ["Чеклист", "Подготовка"]
summary: "Чем поведение Dropout и BatchNorm отличается на обучении и инференсе."
weight: 18
---

> Приоритет: низкий · Материалы: Goodfellow, *Deep Learning*, гл. 7–8

## Что нужно знать
- [ ] Dropout: зануление нейронов на train, масштабирование, выключение на eval
- [ ] BatchNorm: нормализация по батчу; running-статистики на eval; разница train / eval
- [ ] L2 / weight decay, early stopping, аугментации
- [ ] **Различие режимов train vs eval** — типичный источник багов на инференсе

## Проверь себя
1. Что делает dropout на train и на eval?
2. Как BatchNorm ведёт себя на инференсе и почему?
3. Приведи баг из практики, связанный с забытым переключением train/eval.

## Материалы
- Goodfellow, Bengio, Courville, *Deep Learning*, гл. 7–8
