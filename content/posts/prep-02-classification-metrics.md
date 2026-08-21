---
date: '2026-08-21T10:02:00+03:00'
draft: false
title: '02 · Метрики классификации: accuracy, precision, recall, F1, ROC-AUC'
categories: ["Базовое ML"]
tags: ["Чеклист", "Подготовка"]
summary: "Матрица ошибок, precision/recall, ROC-AUC и его вероятностный смысл."
weight: 2
---

> Приоритет: низкий · Материалы: ШАД handbook / Соколов

## Что нужно знать
- [ ] Матрица ошибок: TP, FP, TN, FN
- [ ] `accuracy = (TP+TN) / all`; когда вводит в заблуждение (дисбаланс классов)
- [ ] `precision = TP / (TP+FP)`, `recall = TP / (TP+FN)`
- [ ] F1 — гармоническое среднее precision и recall; `Fβ`
- [ ] Порог классификации; PR-кривая
- [ ] ROC-кривая (TPR vs FPR), ROC-AUC и его вероятностная интерпретация: `P(score⁺ > score⁻)`
- [ ] macro / micro / weighted усреднение для многоклассовой

## Проверь себя
1. Почему accuracy — плохая метрика при дисбалансе 99/1?
2. Дай вероятностную интерпретацию ROC-AUC.
3. Когда предпочесть PR-AUC вместо ROC-AUC?
4. Как precision и recall меняются при сдвиге порога?

## Материалы
- ШАД handbook, конспекты Е. Соколова
