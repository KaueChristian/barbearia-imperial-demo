# Barbearia Imperial — modelo de landing page

Landing page de página única, mobile-first, para uma barbearia premium fictícia. Feita como modelo de demonstração para mostrar a clientes como o site deles pode ficar no ar.

**Demo:** https://kauechristian.github.io/barbearia-imperial-demo/

## O que tem

- Header flutuante, hero com CTA para o WhatsApp e badges de prova rápida
- Serviços e valores em cards, com botão "Quero este" que abre o WhatsApp já com o serviço na mensagem
- Diferenciais, avaliações no estilo Google Maps e localização com horários
- Selo "Aberto agora / Fechado agora" calculado pelo horário de Brasília
- Botão flutuante do WhatsApp com mensagem pré-preenchida

## Stack

Um único `index.html`: Tailwind CSS via CDN, ícones Lucide (unpkg), fontes Bodoni Moda e Hanken Grotesk (Google Fonts) e fotos do Unsplash. Sem build, sem dependências.

## Para usar com um cliente real

- Troque o número em `const WHATSAPP`, no início do `<script>`
- Troque endereço, preços, horários e as avaliações (as atuais são fictícias)
- Remova o bloco `#demoTag` e a meta `robots` com `noindex`
- Em produção, compile o Tailwind em vez de usar o CDN

Fotos: [Unsplash](https://unsplash.com).
