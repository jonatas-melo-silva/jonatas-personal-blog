---
title: "Duas Formas de Pré-renderização"
date: "2020-01-01"
---

Next.js tem duas formas de pré-renderização: **Geração Estática** e **Renderização do lado do servidor**. A diferença está em **quando** ele gera o HTML para uma página.

- **Geração Estática** é o método de pré-renderização que gera o HTML na **hora da compilação.**. O HTML pré-renderizado é então _reutilizado_ em cada solicitação.
- **Renderização do lado do servidor** é o método de pré-renderização que gera o HTML em **cada solicitação**.

Importante, o Next.js permite **escolher** qual forma de pré-renderização usar para cada página. Você pode criar um aplicativo "híbrido" Next.js usando a Geração Estática para a maioria das páginas e usando renderização do lado do servidor para outros.
