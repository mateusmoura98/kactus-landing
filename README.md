# Kactus — Landing Page

Landing page estática (HTML/CSS/JS puro, sem build) para direcionar visitantes ao grupo VIP do WhatsApp da Kactus.

- Instagram: https://www.instagram.com/lojakactusoficial
- WhatsApp da loja: https://wa.me/5571982459149
- Botão do grupo: https://chat.whatsapp.com/JLhl3FEWfo8LN2ecGwJcOk?mode=gi_t

## Trocar o link do grupo

Substitua o link nos botões (busca e troca de `https://chat.whatsapp.com/JLhl3FEWfo8LN2ecGwJcOk?mode=gi_t` no `index.html`).

## Rodando localmente

```bash
python -m http.server 8123
```

## Deploy (EasyPanel)

`Dockerfile` (Nginx servindo os arquivos estáticos), pronto para deploy no EasyPanel via GitHub, auto-deploy a cada push na `main`.
