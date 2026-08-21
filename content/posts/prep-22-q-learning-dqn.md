---
date: '2026-08-21T10:22:00+03:00'
draft: false
title: '22 · Q-обучение, DQN, experience replay, double DQN'
categories: ["Прикладные"]
tags: ["Чеклист", "Подготовка"]
summary: "Зачем DQN нужны target network и replay buffer."
weight: 22
---

> Приоритет: высокий · Материалы: AlMahamid, RL overview

## Что нужно знать
- [ ] Q-learning: off-policy, обновление по `max_a Q`
- [ ] Approximate Q (аппроксимация функции), DQN
- [ ] **Experience replay:** зачем — декорреляция примеров, переиспользование данных
- [ ] **Target network:** зачем — стабилизация цели обучения
- [ ] Double DQN: борьба с overestimation bias
- [ ] Автокорреляция последовательных состояний как проблема

## Проверь себя
1. Зачем нужен replay buffer?
2. Зачем target network?
3. Какую проблему решает Double DQN?

## Материалы
- AlMahamid et al., обзор по Reinforcement Learning
