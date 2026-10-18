# Correia do Nordeste — página de links

Página de links (link-in-bio) do criador de conteúdo **Correia do Nordeste**: dicas de migração, histórias reais e humor nordestino. Reúne TikTok, Instagram, YouTube e WhatsApp em uma página só.

🔗 https://chave-b2b1b.web.app/

## Stack

HTML + CSS puros, sem build. Hospedado no Firebase Hosting.

## Estrutura

```
public/
  index.html    página principal
  style.css     estilos
  404.html      página de erro
  *.png/*.jpg   imagens (fundo e avatar)
```

## Deploy

```bash
npm i -g firebase-tools
firebase login
firebase deploy --only hosting
```
