---
layout: post
title: Primeiro ataque do PagSeguro
date: 2018-07-30 16:56:00 -03:00
categories:
- comunicados
---

No blog sounoob, temos um "health check" que utiliza Pingdom para analisar as APIs do PagSeguro. Provavelmente para inibir o uso do Pingdom o PagSeguro incluiu um limite no Sandbox de 1000 requisiçõse por hora, o que fez nosso "health check" parar de funcionar para o ambiente de sandbox.

No momento estamos trabalhando para uma soluçao alternativa, e algumas opções já voltaram a operar normalmente, mas não em sua totalidade, pedimos um pouco de paciência que já já tudo volta ao normal.

