---
title: 'SIEM/EDR Internals #0: Introduсtion'
description: Цикл статей, описывающих R&D процесс погружения и реализации SIEM/EDR систем
# author: kPusta19
date: 2026-09-09 03:00:00 +0300
categories: ['Cyber Security Software']
tags: [r&d, cybersecurity, software]
# pin: true
# toc: false
# math: true
mermaid: true
image:      
  path: /assets/img/posts/correlation.jpg
  lqip: data:image/jpg;base64,UklGRjAAAABXRUJQVlA4ICQAAACQAQCdASoFAAMAAkA4JaQAAudZtgAA/v2xdHF2ayXsBgAAAAA=
  alt: SIEM/EDR Internals
# render_with_liquid: false
---

## Введение

Данный цикл статей будет покрывать более обширный пласт тем и технологий, чем говорится в названии цикла.
Помимо самих [SIEM](https://en.wikipedia.org/wiki/Security_information_and_event_management){: target="_blank" rel="noopener noreferrer"}
и [EDR](https://en.wikipedia.org/wiki/Endpoint_detection_and_response){: target="_blank" rel="noopener noreferrer"}
систем будут разбираться архитектуры и их компромисы,
внутренние компоненты, вплоть до структур данных и алгоритмов, применямых для построения решения.
Также, при случае, каждый из компонентов будет подвержен анализу на возможность улучшения тех или иных аспектов.


## Анализ существующих решений
