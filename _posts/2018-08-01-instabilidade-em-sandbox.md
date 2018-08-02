---
layout: post
title: Instabilidade em sandbox
categories:
- instabilidade
---

O ambiente de sandbox do PagSeguro está passando por uma instabilidade deste as 11h30 AM, onde intermitentemente é retornado "Internal Server Error" (http status 200) do servidor independente da requisição realizada.
  
<!--more-->

Ainda não temos nenhuma resposta oficial do PagSeguro referente ao ocorrido, porém estamos monitorando e atualizaremos esse post conforme for atualizando.

Fique a vontade de usar os comentários para dizer se isso está afetando você, e como você está contornando a situação.

[Update 18:48]

Instabilidades parece ter parado, porém maioria das requisições na média de 60 segundos (algumas mais outras menos). Nesse caso aumentem o timeout da aplicação...

[Update 20:27]

O problema continua, agora de forma mais agravada, pouquissimas requisições estão passando e nenhum comunicado oficial sobre o caso.
