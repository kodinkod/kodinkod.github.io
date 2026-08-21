---
date: '2026-08-21T10:17:00+03:00'
draft: false
title: '17 · Функции потерь и активации, Softmax, сложность'
categories: ["Базовое ML"]
tags: ["Чеклист", "Подготовка"]
summary: "Активации, численно стабильный softmax и связка softmax + cross-entropy."
weight: 17
---

> Приоритет: низкий · Материалы: Goodfellow, *Deep Learning*

## Что нужно знать
- [ ] Активации: sigmoid, tanh, ReLU и варианты; проблема затухания градиента
- [ ] Softmax: нормировка в вероятности; численная стабильность (вычитание max)
- [ ] Лоссы: MSE, cross-entropy, hinge
- [ ] Связка softmax + cross-entropy и её простой градиент `(p − y)`
- [ ] Вычислительная сложность слоёв

## Проверь себя
1. Почему ReLU лучше sigmoid против затухания градиента?
2. Как обеспечить численную стабильность softmax?
3. Чему равен градиент softmax + cross-entropy?

## Материалы
- Goodfellow, Bengio, Courville, *Deep Learning*
