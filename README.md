# Kactus — Landing Page

Landing page estática (HTML/CSS/JS puro, sem build) para direcionar visitantes ao grupo VIP do WhatsApp da Kactus.

- Instagram: https://www.instagram.com/lojakactusoficial
- WhatsApp da loja: https://wa.me/5571982459149
- Botão do grupo: https://wa.me/5571982459149?text=Ol%C3%A1%21%20Quero%20entrar%20no%20grupo%20VIP%20de%20ofertas%20da%20Kactus.

## Trocar o link do grupo

Substitua o link nos botões (busca e troca de `https://wa.me/5571982459149?text=Ol%C3%A1%21%20Quero%20entrar%20no%20grupo%20VIP%20de%20ofertas%20da%20Kactus.` no `index.html`).

## Rodando localmente

```bash
python -m http.server 8123
```

## Deploy (EasyPanel)

`Dockerfile` (Nginx servindo os arquivos estáticos), pronto para deploy no EasyPanel via GitHub, auto-deploy a cada push na `main`.
